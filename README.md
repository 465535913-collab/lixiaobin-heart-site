# 李小兵医生个人主页

纯静态单页网站，可直接部署到 Vercel / GitHub Pages / Cloudflare Pages / 任意静态服务器。

## 文件
- `index.html`：完整网站
- `assets/li-xiaobin.jpg`：医生照片
- `assets/heart-anatomy.png`：心脏解剖视觉图

## 部署
将整个文件夹作为项目根目录部署即可，无需构建命令。

Vercel：Framework Preset 选择 `Other`，Build Command 留空，Output Directory 留空或 `.`。

## 注意
留言板为 localStorage 演示，不会上传服务器。如果需要真正在线提交留言，需要后续接入数据库/API。
