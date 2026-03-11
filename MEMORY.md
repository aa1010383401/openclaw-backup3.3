# MEMORY.md - 长期记忆

## SWQ（爷爷）

**工作:** 办公 + 写作
**交流风格偏好:** 幽默一点
**称呼偏好:** 爷爷 👴（2026-03-10 起）
**首次见面:** 2026-03-03

---

## 🛠️ 技术环境

### OpenClaw
- **版本:** 2026.3.7+
- **工作目录:** `/Users/swq/.openclaw/workspace`
- **模型:** bailian/qwen3.5-plus (通义千问)
- **时区:** Asia/Shanghai

### 抖音视频系统
- **存储位置:** `/Volumes/ThinkPlus/douyin-hot-videos/`
- **API:** TikHub API v3 (`https://api.tikhub.dev/api/v1/douyin/app/v3/fetch_one_video`)
- **自动同步:** 每天 5:00 AM  cron 任务
- **脚本:** `sync_likes_daily.py` (自动下载喜欢列表新视频)
- **视频格式:** `排名_标题_视频 ID.mp4`

### 飞书机器人
- **机器人 ID:** `ou_14dc877790a7ed4f30a9fb2c0b3d2872`
- **连接方式:** WebSocket 长连接
- **事件订阅:** `im.message`

### 依赖
- Python 3.9+
- Node.js v24.14.0
- requests 库
- @larksuiteoapi/node-sdk

---

## 📋 待办事项 (持续)

- [ ] 收藏视频 API 404 问题排查
- [ ] 视频清单报表生成
- [ ] 旧视频自动清理 (30 天)
- [ ] 定时任务监控

---

*持续更新中...*
