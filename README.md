# RED Skill 矩阵

> 小红书 AI Skill 开发集合 —— 专注小红书生态的实用 AI 技能包

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![Skills](https://img.shields.io/badge/skills-1%20completed%2F5%20planned-blue)](./skills)

---

## 这是什么？

本仓库收录面向小红书 RED Skill 平台开发的 AI Skill，也兼容 Claude Code、WorkBuddy、OpenClaw 等 AI 编程助手。每个 Skill 都是独立的 `SKILL.md` 文件，可直接被 AI 助手加载使用。

## 已开发 Skill

| Skill | 状态 | 描述 |
|-------|------|------|
| [爆款标题生成器](./skills/title-generator/) | 🚧 开发中 | 为小红书笔记生成高点击率标题 |

## 规划中

| Skill | 方向 | 优先级 |
|-------|------|--------|
| 文案生成器 | 小红书创作 | P1 |
| 标签推荐 | 小红书创作 | P1 |
| 开店预算计算器 | 餐饮创业 | P1 |
| 选址分析助手 | 餐饮创业 | P2 |

## 如何使用

### 在 AI 助手中使用
1. 下载对应 Skill 的 `SKILL.md` 文件
2. 放入 AI 助手的 skills 目录
3. 重启或刷新 AI 助手

### 在小红书 RED Skill 中使用
1. 在小红书搜索 `RED Skill`
2. 找到对应的 Skill（上架后）
3. 复制口令安装

## 项目结构

```
xiaohongshu-skills/
├── skills/              # 所有 Skill 源代码
│   ├── title-generator/ # 爆款标题生成器
│   ├── copywriter/      # 文案生成器（规划中）
│   ├── tag-recommend/   # 标签推荐（规划中）
│   └── ...
├── docs/                # 项目文档
├── .github/             # CI/CD 配置
│   └── workflows/       # GitHub Actions
├── README.md
├── LICENSE
└── CONTRIBUTING.md
```

## 平台规则

所有 Skill 严格遵守小红书 RED Skill 平台规范。详见 [平台规则文档](./docs/platform-rules.md)。

## 贡献

欢迎提交 Issue 和 PR。详见 [CONTRIBUTING.md](./CONTRIBUTING.md)。

## 许可证

MIT License — 详见 [LICENSE](./LICENSE)

---

**作者**：峰哥（psy489963）

**小红书**：待上架

**GitHub**：[https://github.com/psy489963/xiaohongshu-skills](https://github.com/psy489963/xiaohongshu-skills)
