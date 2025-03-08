<template>
    <div class="page-footer" v-if="!disableFooter">
        <p>© 2024-{{ thisYear }} Designed by <a class="footer-name" href="https://github.com/MarSeventh" target="_blank">SanyueQi</a> for You!
            
            <a :href="footerLink" target="_blank">
                <font-awesome-icon icon="paper-plane" class="footer-link-icon"/>
            </a>
            <div class="xmy"><a href="https://418121.xyz">返回主页 </a></div>
        </p>
    </div>
</template>

<script>
import { mapGetters } from 'vuex'

export default {
    name: 'Footer',
    computed: {
        ...mapGetters(['userConfig']),
        footerLink() {
            return this.userConfig?.footerLink || 'https://github.com/MarSeventh/CloudFlare-ImgBed'
        },
        thisYear() {
            return new Date().getFullYear()
        },
        disableFooter() {
            return this.userConfig?.disableFooter || false
        }
    }
}
</script>

<style scoped>
.page-footer {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100vw;
    color: var(--page-footer-text-color);
    font-size: large;
    user-select: none;
}
@media (max-width: 768px) {
    .page-footer {
        font-size: small;
    }
}
.footer-name {
    color: var(--page-footer-name-color);
    font-weight: bold;
    text-decoration: none;
}
.footer-link-icon {
    color: var(--page-footer-name-color);
    margin-left: 5px;
}
.xmy a {
    text-decoration: none;
    color: #f0f8ff;
    display: block
}
.mxy a:hover {
    color: #000
}
</style>