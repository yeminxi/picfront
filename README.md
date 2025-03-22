<div align="center">
    <a href="https://github.com/MarSeventh/CloudFlare-ImgBed"><img width="200px" alt="logo" src="https://imgbed.sanyue.site/file/github/1741863225688_logo.e8dbfa27.png"/></a>
    <p><em>🗂️开源文件托管解决方案，基于 Cloudflare Pages，支持 Telegram Bot 、 Cloudflare R2 ，S3 API 等多种不同存储渠道。</em></p>
    <div>
        <a href="https://github.com/MarSeventh/CloudFlare-ImgBed/blob/main/LICENSE">
        <img src="https://img.shields.io/github/license/MarSeventh/CloudFlare-ImgBed" alt="License" />
        </a>
        <a href="https://github.com/MarSeventh/CloudFlare-ImgBed/releases">
        <img src="https://img.shields.io/github/release/MarSeventh/CloudFlare-ImgBed" alt="latest version" />
        </a>
        <a href="https://github.com/MarSeventh/CloudFlare-ImgBed/releases">
        <img src="https://img.shields.io/github/downloads/MarSeventh/CloudFlare-ImgBed/total?color=%239F7AEA&logo=github" alt="Downloads" />
        </a>
        <a href="https://github.com/MarSeventh/CloudFlare-ImgBed/issues">
          <img src="https://img.shields.io/github/issues/MarSeventh/CloudFlare-ImgBed" alt="Issues" />
        </a>
        <a href="https://github.com/MarSeventh/CloudFlare-ImgBed/stargazers">
          <img src="https://img.shields.io/github/stars/MarSeventh/CloudFlare-ImgBed" alt="Stars" />
        </a>
        <a href="https://github.com/MarSeventh/CloudFlare-ImgBed/network/members">
          <img src="https://img.shields.io/github/forks/MarSeventh/CloudFlare-ImgBed" alt="Forks" />
        </a>
    </div>
</div>

----
# sanyue_imghub

### 本仓库为[MarSeventh/CloudFlare-ImgBed](https://github.com/MarSeventh/CloudFlare-ImgBed)项目的前端仓库，详细介绍及部署方式请移步该仓库。

## Deployment

如果要在**完整项目基础上定制前端**，只需要三步（**前提是你需要有基本的`git`、`nodejs`等工具的使用能力**）：

1. 将该项目拉到本地，`npm install`，修改环境变量`.env`中的`VUE_APP_SITE_URL`为你自己图床的URL
2. 进行DIY，然后`npm run build`，进入打包好的`/dist`目录，将里面的所有内容复制到`CloudFlare-ImgBed`项目的根目录
3. 将修改好的`CloudFlare-ImgBed`项目部署上去即可，具体方法参照完整项目的文档

## TIPS

**一天手搓出来的前端，后续还会继续完善，有bug欢迎提出。**

**如果觉得项目不错希望您能给个免费的star✨✨✨，非常感谢！**
