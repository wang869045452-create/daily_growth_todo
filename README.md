# 我的每日成长计划 Pro PWA

这是一个可以部署成手机桌面小应用的 PWA 版本。

## 文件说明

- `index.html`：主页面，包含 To Do、周统计、折线图、分类完成率、复盘导出
- `manifest.json`：PWA 配置，决定桌面图标、应用名称、打开方式
- `service-worker.js`：离线缓存，让网页部署后可以离线访问
- `icons/`：手机桌面图标

## 重要说明

本地直接双击 `index.html` 可以测试页面，但不能稳定实现“像 App 一样从桌面独立打开”。

要实现真正的手机桌面应用效果，需要部署到 HTTPS，例如：

- GitHub Pages
- Vercel
- Netlify
- Cloudflare Pages

## 最简单的 GitHub Pages 部署步骤

1. 新建一个 GitHub 仓库
2. 上传本文件夹里的所有文件
3. 进入仓库 Settings
4. 找到 Pages
5. Source 选择 `Deploy from a branch`
6. Branch 选择 `main`，目录选择 `/root`
7. 保存后等待生成网址
8. 用手机浏览器打开那个网址
9. 选择“添加到主屏幕”

以后从桌面图标打开，就会更接近独立 App。
