# Robot Papers Weekly

> 机器人领域 arXiv 论文自动聚合与归档项目

## 📌 项目简介

本项目通过自动化脚本，每周定期抓取机器人学（Robotics）及相关领域在 arXiv 上的最新论文，按主题分类整理并生成本地 Markdown 摘要，同时推送至飞书文档进行双端归档。

核心目标是为机器人研究者提供一个结构化的论文追踪入口，降低信息筛选成本。

## 🗂️ 目录结构

```
robot-papers-weekly/
├── papers/              # 按日期归档的论文摘要 Markdown 文件
│   └── YYYY-MM-DD-papers.md
├── README.md            # 本文件
└── ...
```

## 📑 论文归档索引

| 日期 | 文件 | 收录数量 | 主题分布 |
|------|------|---------|---------|
| 2026-07-15 | [papers/2026-07-15-papers.md](./papers/2026-07-15-papers.md) | 50 篇 | 具身智能与世界模型、操作抓取与灵巧操作、人形机器人与双足运动、移动与运动控制、导航定位与 SLAM、ROS 与机器人中间件 |
| 2026-07-07 | [papers/2026-07-07-papers.md](./papers/2026-07-07-papers.md) | 53 篇 | 具身智能、操作抓取、人形机器人、导航定位、运动控制、多智能体、感知与学习 |
| 2026-07-01 | [papers/2026-07-01-papers.md](./papers/2026-07-01-papers.md) | 41 篇 | ROS 与机器人中间件、具身智能与世界模型、人形机器人与双足运动、操作抓取与灵巧操作、导航定位与 SLAM、机器人学习与控制 |
| 2026-06-24 | [papers/2026-06-24-papers.md](./papers/2026-06-24-papers.md) | 100 篇 | 具身智能、操作与抓取、人形机器人、移动与运动控制、导航与定位、仿真到现实、机器人学习、感知与视觉、安全与可靠性、人机交互 |
| 2026-06-17 | [papers/2026-06-17-papers.md](./papers/2026-06-17-papers.md) | 50 篇 | 具身智能与灵巧操作、操作抓取、导航定位与 SLAM、人形机器人与运动控制、机器人学习 |
| 2026-06-10 | [papers/2026-06-10-papers.md](./papers/2026-06-10-papers.md) | 45 篇 | 具身智能、操作抓取、人形机器人、运动控制、导航定位 |

> 每份周报按主题分类整理，包含论文标题、作者、arXiv 链接、发表日期、一句话总结及完整摘要。

## ⏰ 更新频率

- **自动抓取**：每周三凌晨 02:00（UTC+8）
- **推送渠道**：飞书文档 + GitHub 双归档

## 📋 覆盖主题

- 移动机器人（Mobile Robotics）
- 操作与抓取（Manipulation & Grasping）
- 人形机器人（Humanoid Robots）
- 强化学习在机器人中的应用（RL for Robotics）
- 感知与导航（Perception & Navigation）
- 多模态与具身智能（Multimodal & Embodied AI）

## 🚀 快速使用

1. 克隆仓库：
   ```bash
   git clone https://github.com/loonglee2025/robot-papers-weekly.git
   cd robot-papers-weekly
   ```

2. 查看最新论文摘要：
   ```bash
   ls papers/$(date +%Y-%m-%d)
   ```

## 🔗 关联项目

- [robot-research-weekly](https://github.com/loonglee2025/robot-research-weekly) — 机器人研究深度周报
- [ros2-weekly-digest](https://github.com/loonglee2025/ros2-weekly-digest) — ROS2 技术周报

## 📜 License

MIT

---

*Maintained by [LoongLee](https://github.com/loonglee2025)*
