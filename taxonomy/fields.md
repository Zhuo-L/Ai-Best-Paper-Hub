# 字段规范（fields.md）

本仓库使用表格形式记录每条获奖论文。推荐字段如下（最小可用集：Year / Award / Title / Authors / Links）：

## 推荐字段
- `Year`：年份（如 2024）
- `Conference`：会议简称（如 NeurIPS）
- `Award`：奖项类型（Best Paper / Outstanding Paper / Test of Time / Honorable Mention 等）
- `Title`：论文标题
- `Authors`：作者（建议 “First Author et al.”；完整作者可放 Notes）
- `Affiliations`：机构（可选）
- `Paper`：论文链接（OpenReview / ACL Anthology / CVF / Proceedings）
- `Source`：官方获奖页链接（强烈建议保留）
- `Code`：代码链接（GitHub 等，可选）
- `Keywords`：关键词（建议 3–8 个，英文为主便于检索）
- `Topics`：主题标签（从 topics.md 中选）
- `Verified`：核验状态（✅ / ⚠️ / ❌）
- `LastUpdate`：最后更新（YYYY-MM-DD）
- `Notes`：一句话贡献/亮点 + 口径说明（如“并列获奖”“奖项命名差异”）

## Verified 口径
- ✅ 已核验：至少有官方获奖来源（Source）+ 论文页（Paper）
- ⚠️ 部分核验：缺少代码/作者/机构等次要字段，或链接似乎可疑
- ❌ 未核验：仅占位，等待补全

## 常见注意
- NeurIPS/NIPS 更名：统一写 `NeurIPS`，历史命名可在 Notes 写 `NIPS`
- 多并列奖：建议“多行记录”，不要把多个标题塞进一个单元格
