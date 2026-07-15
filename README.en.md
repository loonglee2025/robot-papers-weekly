# Robot Papers Weekly

> Automated arXiv Paper Aggregation & Archiving for Robotics Research

## 📌 Overview

This project automatically fetches the latest robotics-related papers from arXiv on a weekly basis, categorizes them by topic, generates local Markdown summaries, and pushes them to Feishu documents for dual-end archiving.

The core goal is to provide robotics researchers with a structured entry point for paper tracking, reducing information filtering costs.

## 🗂️ Repository Structure

```
robot-papers-weekly/
├── papers/              # Paper summary Markdown files archived by date
│   └── YYYY-MM-DD-papers.md
├── README.md            # Chinese version (default)
├── README.en.md         # This file
└── ...
```

## 📑 Paper Archive Index

| Date | File | Papers | Topics |
|------|------|--------|--------|
| 2026-07-15 | [papers/2026-07-15-papers.md](./papers/2026-07-15-papers.md) | 50 | Embodied AI & World Models, Manipulation & Dexterous Operation, Humanoid & Bipedal Locomotion, Mobile & Motion Control, Navigation & SLAM, ROS & Robot Middleware |
| 2026-07-07 | [papers/2026-07-07-papers.md](./papers/2026-07-07-papers.md) | 53 | Embodied AI, Manipulation & Grasping, Humanoid Robots, Navigation & Localization, Motion Control, Multi-Agent, Perception & Learning |
| 2026-07-01 | [papers/2026-07-01-papers.md](./papers/2026-07-01-papers.md) | 41 | ROS & Robot Middleware, Embodied AI & World Models, Humanoid & Bipedal Locomotion, Manipulation & Dexterous Operation, Navigation & SLAM, Robot Learning & Control |
| 2026-06-24 | [papers/2026-06-24-papers.md](./papers/2026-06-24-papers.md) | 100 | Embodied AI, Manipulation & Grasping, Humanoid Robots, Mobile & Motion Control, Navigation & Localization, Sim-to-Real, Robot Learning, Perception & Vision, Safety & Reliability, HRI |
| 2026-06-17 | [papers/2026-06-17-papers.md](./papers/2026-06-17-papers.md) | 50 | Embodied AI & Dexterous Manipulation, Manipulation & Grasping, Navigation & SLAM, Humanoid & Motion Control, Robot Learning |
| 2026-06-10 | [papers/2026-06-10-papers.md](./papers/2026-06-10-papers.md) | 45 | Embodied AI, Manipulation & Grasping, Humanoid Robots, Motion Control, Navigation & Localization |

> Each weekly digest is organized by topic and includes paper title, authors, arXiv link, publication date, one-line summary, and full abstract.

## ⏰ Update Schedule

- **Auto-fetch**: Every Wednesday at 02:00 (UTC+8)
- **Delivery**: Feishu document + GitHub dual archiving

## 📋 Coverage Topics

- Mobile Robotics
- Manipulation & Grasping
- Humanoid Robots
- Reinforcement Learning for Robotics
- Perception & Navigation
- Multimodal & Embodied AI

## 🚀 Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/loonglee2025/robot-papers-weekly.git
   cd robot-papers-weekly
   ```

2. View the latest paper summaries:
   ```bash
   ls papers/$(date +%Y-%m-%d)-papers.md
   ```

## 🔗 Related Projects

- [robot-research-weekly](https://github.com/loonglee2025/robot-research-weekly) — In-depth robotics research weekly digest
- [ros2-weekly-digest](https://github.com/loonglee2025/ros2-weekly-digest) — ROS2 technology weekly digest

## 📜 License

MIT

---

*Maintained by [LoongLee](https://github.com/loonglee2025)*
