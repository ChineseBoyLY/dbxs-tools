# WiFi QR Code Generator 工具说明

这是一个纯静态的网页工具，用于生成符合 WiFi 连接标准的二维码。

## 本地运行
1. 直接用浏览器打开 `wifi_qr_generator.html` 文件。
2. 或者在当前目录下运行 `python -m http.server`，然后访问 `http://localhost:8000/wifi_qr_generator.html`。

## 免费部署方案

由于这是一个纯静态页面，推荐使用以下免费服务进行部署：

### 1. Netlify (推荐)
- 访问 [Netlify Drop](https://app.netlify.com/drop)。
- 将包含本文件的文件夹直接拖入页面。
- 获得即时访问链接。

### 2. GitHub Pages
- 将代码提交到 GitHub。
- 在仓库设置中开启 GitHub Pages。
- 访问 `https://<你的用户名>.github.io/<仓库名>/tools/wifi_qr_generator.html`。

### 3. Vercel
- 在 Vercel 导入你的 GitHub 仓库。
- 部署即可。
