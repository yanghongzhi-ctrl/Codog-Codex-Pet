# Codog 原生 Codex 宠物

本目录包含 Codex 原生宠物资源，不是外置桌面程序。

- 精灵图：`codog-native-v2.webp`
- 格式：透明 WebP
- 尺寸：1536 × 2288
- 网格：8 列 × 11 行
- 单帧：192 × 208
- Codex 精灵图版本：2

11 行依次对应：空闲、向右移动、向左移动、挥手、跳跃、失败、等待、执行任务、审阅、向右观察/转向、向左观察/转向。

## 发布和安装

将 `index.html` 和 `codog-native-v2.webp` 原样发布到同一个公开 HTTPS 目录，然后访问 `index.html`。页面会自动生成 Codex 原生宠物安装链接。

Codex 不接受本地文件、localhost、HTTP 地址或发生重定向的图片地址。图片必须是 PNG 或 WebP，且小于 20 MB。
