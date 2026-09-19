# D·BUDDIES STUDIO

D·BUDDIES STUDIO 个人工作室官网，主题为“精准表达，破局出海”。这是一个可直接部署到 GitHub Pages 的静态网站。

## GitHub Pages 部署

1. 将本文件夹内的所有文件上传到 GitHub 仓库的根目录。
2. 打开仓库的 **Settings > Pages**。
3. 在 **Build and deployment** 中选择 **Deploy from a branch**。
4. 分支选择 `main`，目录选择 `/ (root)`，点击 **Save**。
5. 等待 GitHub Actions 部署完成，访问 GitHub Pages 生成的网址。

## 页面

- `index.html`：官网首页
- `quote.html`：自助询价页
- `dbuddies-core-vi.html`：独立 VI 文档，不在官网导航中展示

## 注意

站点使用相对路径，无需构建、Node.js 或后端服务。如需本地预览，可在项目根目录运行任意静态文件服务器。
