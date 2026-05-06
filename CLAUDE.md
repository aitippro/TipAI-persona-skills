# CLAUDE.md — TipAI-persona-skills

🎭 TipAI Persona Skills — 人设分析与生成 Skill 仓库。

## 目录

```
skills/
  persona-forge.md          ← 核心 Skill（3 步工作流：分析→锻造→应答）
templates/
  persona-template.md       ← 人设生成标准输出模板
examples/                   ← 多领域人设生成示例 (3 个)
validator/
  check-skill.md            ← Skill 格式自检清单
.github/workflows/
  check.yml                 ← CI: Markdown 格式检查 + 链接有效性
.markdownlint-cli2.jsonc   ← Markdown 格式规则配置
```

## 加载 Skill

```
仓库: https://github.com/aitippro/TipAI-persona-skills
Skill 文件: skills/persona-forge.md
最佳搭配: Claude Opus 4.7（精准推理 + 长窗口）
```

## 开发规范

- 所有改动基于 `main` 分支，通过 PR 合入
- Skill 内容改动需同步更新 CHANGELOG
- 模板 / 示例 / 质检清单改动需保持与 Skill 文件一致
- 新增示例须跑通完整 3 步工作流后方可提交
- Markdown 格式遵循 `.markdownlint-cli2.jsonc`，CI 自动检查
- 新增示例须对应更新 `validator/check-skill.md` 的覆盖清单

## 约束

- MIT 许可（见 LICENSE）
- 禁止在 Skill / 示例中硬编码任何真实凭证或 API Key
