# CHANGELOG

## v1.2 (2026-05-07)

- ♻️ Skill 自包含化：模板内容（人设卡片/推理链/复杂度评估）内联至 persona-forge.md
- 📝 移除外部文件依赖，单文件加载即可使用全部能力
- 📝 README/CLAUDE.md 更新为自包含描述，templates/ 标注为独立参考件

## v1.1 (2026-05-07)

- 🔧 新增 CI 流水线（.github/workflows/check.yml + .markdownlint-cli2.jsonc）
- 🩹 补齐 Step 4 质量自检（5 项逐项确认 + 不通过修正机制）
- 🩹 3 个示例补全「📐 复杂度评估」表格，对齐模板格式
- 🩹 修复 medical-advisor.md 对比表头缺列名
- 📝 工作流从 3 步升级为 4 步，README/CLAUDE.md 同步更新

## v1.0 (2026-05-06)

- 🎉 初始发布
- 核心 Skill: persona-forge.md（问题分析 → 人设锻造 → 人设应答）
- 人设生成标准模板: persona-template.md
- 3 个领域示例: 技术架构师、医学顾问、法律咨询
- Skill 格式自检清单: check-skill.md
