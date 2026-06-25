# RED Skill 矩阵

> 小红书 AI Skill 开发集合 —— 专注小红书生态的实用 AI 技能包

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![Skills](https://img.shields.io/badge/skills-4%20completed-blue)](./skills)

---

## 这是什么？

本仓库收录面向小红书 RED Skill 平台开发的 AI Skill，也兼容 Claude Code、WorkBuddy、OpenClaw 等 AI 编程助手。每个 Skill 都是独立的 `SKILL.md` 文件，可直接被 AI 助手加载使用。

**核心理念**：一键安装，打开即用，用即有效果。

## 已开发 Skill（4个）

| Skill | 版本 | 模式 | 安装命令 |
|-------|:---:|------|------|
| [选题生成器](./skills/topic-generator/) | v0.3 | 🚀自动/A研究蓝图/B快速分析 | `openclaw skills install @psy489963/xiaohongshu-topic-generator` |
| [爆款标题生成器](./skills/title-generator/) | v0.3 | 12公式直出标题 | `openclaw skills install @psy489963/title-generator` |
| [文案优化器](./skills/copywriter/) | v0.2 | ✏️代写/🔧优化 | `openclaw skills install @psy489963/copywriter` |
| [封面设计顾问](./skills/cover-advisor/) | v0.2 | 🤖AI生成/🎨设计顾问 | `openclaw skills install @psy489963/cover-advisor` |

### 四件套联动闭环

```
选题生成器 → 标题生成器 → 文案优化器 → 封面设计顾问
  (发什么)     (标题怎么写)   (正文怎么写)    (封面怎么做)
```

---

## Skill 详解

### 🚀 选题生成器（v0.3 — 三模式）

三种模式覆盖所有选题场景：

| 模式 | 适合 | 特点 |
|------|------|------|
| C 自动选题 | 懒人/首次 | AI全网扫描近一周热搜，直接出报告 |
| A 研究蓝图 | 深度调研 | AI给搜索清单，你搜完回来AI分析 |
| B 快速分析 | 已有数据 | 带调研数据来，AI直接出选题 |

### 📝 爆款标题生成器（v0.3）

12个爆款标题公式，统一4列输出。合规检查内嵌，一键出可发布的标题。

### ✏️ 文案优化器（v0.2 — 双模式）

| 模式 | 场景 | 流程 |
|------|------|------|
| 优化模式 | 有草稿 | 4步诊断优化 → 输出优化版+改了什么 |
| 代写模式 | 没草稿 | 收集需求→生成初稿→优化流程→成品 |

### 🎨 封面设计顾问（v0.2 — 双模式）

唯一提供双模式的封面 Skill：

| 模式 | 方式 | AI标注 |
|------|------|:---:|
| 设计顾问 | 给操作指令，自己去工具做 | **无需标注** |
| AI生成 | 一键出图 | **必须标注AI生成** |

> ⚠️ 小红书2026年6月起强制AI内容标注。用AI生成模式时发布必须勾选「包含AI生成内容」。

---

## 安装方式

```bash
# 四件套一键安装
openclaw skills install @psy489963/xiaohongshu-topic-generator
openclaw skills install @psy489963/title-generator
openclaw skills install @psy489963/copywriter
openclaw skills install @psy489963/cover-advisor
```

## 项目结构

```
xiaohongshu-skills/
├── skills/
│   ├── topic-generator/    # 选题生成器 v0.3
│   ├── title-generator/    # 标题生成器 v0.3
│   ├── copywriter/          # 文案优化器 v0.2
│   └── cover-advisor/       # 封面设计顾问 v0.2
├── docs/                    # 项目文档
├── .github/workflows/       # CI/CD
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
