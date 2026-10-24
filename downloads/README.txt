下载配置维护说明

当前方案：9 个项目统一通过夸克网盘提供下载。

1. 将完整运行包上传到 config.js 中 QUARK_PAN_URL 指向的网盘文件夹。
2. 编辑 config.js 对应项目的 platform、size、url 及中英文 note。note 中的压缩包文件名应与网盘内一致。
3. 如改为独立分享链接，可修改对应项目的 url；同一项目可配置多个下载项。
4. 发布网站时保留 index.html、downloads/config.js、covers 和 videos 等网页资源。
5. .gitignore 已忽略 downloads/*.rar、downloads/*.zip、高清母带和历史基线。安装包不必提交到网站仓库。
6. videos 当前为网页播放文件；更新视频后同步检查 index.html 的 videoSrc。

HTTP / HTTPS 下载项会在新标签页打开；相对路径下载项使用浏览器文件下载。
空下载列表会显示“试玩包暂未上传，敬请期待。”
本地安装包存在不代表网盘已上传，发布前请实际检查分享页和下载权限。
