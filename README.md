# 番茄钟 iPhone 网页版

无广告、无需注册，支持专注计时、短休息/长休息、任务管理、统计、计时长度设置、提示音、自动切换、本地 JSON 备份恢复。界面跟随系统深浅色，适配 iPhone Safari 与 iPhone 17 Pro Max。

## 发布到 GitHub Pages（iPhone 可操作）
1. Safari 登录 https://github.com 并新建 Public 仓库，例如 `tomato-timer`。
2. 将本 ZIP 解压，把 `index.html`、`manifest.webmanifest`、`sw.js`、`icon-192.png`、`icon-512.png`、`README.md` 上传到仓库根目录。
3. 仓库 Settings → Pages → Build and deployment，选择 `Deploy from a branch`；Branch 选 `main`，目录选 `/(root)`，按 Save。
4. 等待 Pages 显示 published URL，通常形如 `https://用户名.github.io/tomato-timer/`。
5. 用 iPhone Safari 打开链接；可通过分享菜单 → 添加到主屏幕。

## 说明
- 这是网页/PWA，不是原生 iOS App，也不是 TestFlight。
- 数据保存在当前浏览器 localStorage；清除 Safari 网站数据、换浏览器或设备可能导致数据丢失，请定期导出备份。
- iOS 可能限制网页后台计时与声音/通知；返回页面时计时会按结束时间校准，但不保证后台通知。
