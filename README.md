# 🍑 Emby Actor Brief // 深夜图书馆 · 演员动态与新番速查终端

本项目是一个**独立的 Emby 演员/女优元数据情报分析与 MissAV/JavBus 番号自动映射管线**。

## 🌟 核心功能

- 🎬 **Emby 本地 API 提取**：自动同步本地 Emby 媒体库演员数据与持卡片量。
- 🌸 **JavBus 新番元数据补充**：补全演员官方剧照、发行时间与代表作品。
- 🔗 **MissAV 番号精准直达**：自动将作品番号转译为 MissAV 在线播放快捷入口。
- 🛡️ **防盗链与图片优化**：对第三方封面进行 Base64 / 代理优化，彻底解决 404 与挂图问题。
- 💻 **赛博/日式清新双UI**：自适应移动端与桌面端的极简响应式设计。

## 🚀 部署与使用

1. 运行本地生成与推送管线：
```bash
python3 scripts/emby_actor_brief.py --publish
```

2. 部署目标：[GitHub Pages](https://j1nkai.github.io/emby-actor-brief/)

---
*Powered by Rem 💙 // Devoted Guardian for Master JK*
