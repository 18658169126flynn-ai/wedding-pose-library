# 拍照姿势参考库 · 备婚影像（Web 版）

从 Android 安装包 `开拍灵感.apk`（包名 `com.posingref.app`）中提取的静态 Web 资源，原应用是 Capacitor WebView 外壳，网页层与本仓库内容一致。

直接访问 GitHub Pages 即可使用；在 iOS / iPadOS Safari 中「分享 → 添加到主屏幕」可当作 PWA 全屏运行。

## 内容

- `index.html` — 单文件应用（样式与逻辑内联）
- `list.json` — 姿势图片索引
- `photos/` — 备婚姿势参考图（webp）
- `img/` — 界面配图
- `manifest.json` / `icon-*` — PWA 清单与图标

## 说明

仅包含原应用的网页层资源，不含任何原生代码、统计 SDK 或联网上报逻辑。
