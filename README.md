# AI 顶级会议 Best Paper 汇总（可持续更新）

> 目标：汇总近年来各大 AI 顶级会议（ICML / ICLR / NeurIPS / AAAI / ACL / EMNLP / CVPR / ICCV / ECCV）的 Best Paper（含获奖类型、标题、作者、机构、链接、代码、关键词、主题标签等），便于检索、持续更新与共享。

## 仓库结构
- `index/`：总览索引（按年份 / 按会议）
- `by_conference/`：按会议整理（每年一页）
- `by_topic/`：按主题标签整理（可人工维护或脚本生成）
- `taxonomy/`：字段规范与主题标签体系

```text
.
├─ README.md
├─ index/
│  ├─ by_year.md
│  └─ by_conference.md
├─ by_conference/
│  ├─ NeurIPS/
│  ├─ ICLR/
│  ├─ ICML/
│  ├─ AAAI/
│  ├─ ACL/
│  ├─ EMNLP/
│  ├─ CVPR/
│  ├─ ICCV/
│  └─ ECCV/
├─ by_topic/
│  └─ (topic pages)
└─ taxonomy/
   ├─ fields.md
   └─ topics.md
```

## 快速开始（维护方法）
1. 去 `by_conference/<CONF>/<YEAR>.md` 填表（每条记录一行）
2. 同步更新：
   - `index/by_year.md`（按年份汇总）
   - `index/by_conference.md`（会议入口）
3. `Verified` 置为 ✅ / ⚠️ / ❌  
4. `LastUpdate` 更新为当天日期（建议：2026-02-05 之后持续更新）


## 覆盖情况（2026-02-05）

- ✅ 已填充（含官方来源链接）：EMNLP 2023–2025、ACL 2023–2025（部分奖项）、NeurIPS 2024–2025、ECCV 2024
- ⏳ 待补全：ICML / ICLR / AAAI / CVPR / ICCV / ECCV 2022 等（仓库骨架已准备好，可继续增量补充）
- 说明：部分条目因缺少可公开稳定的论文页链接，当前标记为 ⚠️（Source 已核验，Paper 待补）。

## 贡献与协作（建议）
- 用 PR 提交新增年份/新增奖项：`[NeurIPS 2025] add best paper entries`
- 每条记录至少包含：**Award / Title / Paper 链接 / Source（官方获奖页）**
- 非官方来源必须在 Notes 标注（例如“博客转载，待官方核验”）

## License
- 建议：CC BY 4.0（知识整理更合适）
- 若你后续加脚本：可改用 MIT

