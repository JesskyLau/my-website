下载文件配置

1. 将 ZIP / APK 等打包文件放到 downloads 文件夹。Windows 请打包完整运行目录。
2. 编辑 config.js，在对应项目的 [] 内添加下载项，例如：
   8: [{ platform: "Windows x64", size: "200 MB", url: "downloads/qingxi-windows.zip" }],
3. 同一项目可添加多个平台，用逗号分隔下载项。size 可省略。
4. 文件也可放在外部存储，将 url 填成完整 HTTPS 链接。
5. 发布时上传 index.html、downloads/config.js 及所需安装包。

未填写下载项时，窗口显示“试玩包暂未上传，敬请期待。”
