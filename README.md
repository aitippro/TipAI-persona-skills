<div align="center">

# 🎭 TipAI Persona Skills

**人设分析与生成 Skill 模块**

加载 Skill → 分析用户问题 → 生成严谨精准人设 → 以人设视角回答解决客户问题

[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0-blue?style=flat-square)](CHANGELOG.md)

</div>

---

## 📂 结构

```
TipAI-persona-skills/
├── skills/
│   └── persona-forge.md            ← 🎯 核心 Skill（人设锻造）
├── templates/
│   └── persona-template.md         ← 人设生成标准模板
├── examples/                       ← 多领域人设生成示例
│   ├── tech-architect.md           ← 技术架构师场景
│   ├── medical-advisor.md          ← 医学顾问场景
│   └── legal-counsel.md            ← 法律咨询场景
├── validator/
│   └── check-skill.md              ← Skill 格式自检清单
├── .github/workflows/
│   └── check.yml                   ← CI: Lint + 链接检查
├── .markdownlint-cli2.jsonc        ← Markdown 格式规则
├── CHANGELOG.md
├── LICENSE
└── README.md
```

---

## 🎯 核心机制

加载 Skill 后，Agent 执行 3 步工作流：

| 🔍 Step 1 问题分析 | 🎭 Step 2 人设锻造 | 💬 Step 3 人设应答 |
|:---|:---|:---|
| 深度解析用户问题 | 生成与问题最匹配的严谨人设 | 以人设视角精准回答 |
| 提取核心诉求、领域、语境 | 定义身份、知识体系、思维框架 | 全程保持人设一致性和专业性 |

---

## 🚀 使用

```
1. 加载 skills/persona-forge.md 到你的 Agent
2. 直接提问，Agent 自动完成人设分析并以最佳人设回答
3. 不需要手动指定角色，系统全自动匹配
```

详见 [示例](examples/)

---

## 🛡️ 质量原则

| 原则 | 说明 |
|------|------|
| **人设必有据** | 每个人设属性须能从用户问题中追溯依据 |
| **人设不越界** | 严格限定在问题相关领域，不堆砌无关标签 |
| **人设可解释** | 向用户透明展示人设生成逻辑 |
| **应答一致性** | 全程保持同一人设的语境、语言风格和专业深度 |

---

## 📖 工作流

```
用户提问 → 问题深析(领域/诉求/语境/复杂度) → 人设锻造(身份/知识/思维/语气)
              → 人设预览(用户可调) → 人设应答 → 质量自检
```

---

<div align="center">
<sub>MIT License · TipAi Team © 2026</sub>
</div>
