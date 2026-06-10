# Robot Papers Weekly

> 机器人领域 arXiv 论文自动聚合与归档项目

## 📌 项目简介

本项目通过自动化脚本，每周定期抓取机器人学（Robotics）及相关领域在 arXiv 上的最新论文，按主题分类整理并生成本地 Markdown 摘要，同时推送至飞书文档进行双端归档。

核心目标是为机器人研究者提供一个结构化的论文追踪入口，降低信息筛选成本。

## 🗂️ 目录结构

```
robot-papers-weekly/
├── papers/              # 按 arXiv ID 命名的论文摘要文件
│   └── YYYY-MM-DD/      # 按日期归档
├── README.md            # 本文件
└── ...
```

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
