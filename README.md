# keros68

学术投稿全流程 AI Agent Skills，外加两个桌面工具。每个 skill 独立仓库，clone 到 skills 目录即用（Claude Code / Codex 均支持）。

## 学术投稿流水线

```text
写作 → 补引用 → 配图 → 选刊 + 投稿前审查 → 学位论文格式
```

| 阶段 | Skill | 用途 |
|------|-------|------|
| 补引用 / 验证引用 | [academic-reference-matcher](https://github.com/keros68/academic-reference-matcher) | 识别 claim、检索候选文献、验证支撑关系，输出 APA / GB/T 7714 / BibTeX 等格式 |
| 图形摘要 / 概念图 | [abstract-fig](https://github.com/keros68/abstract-fig) | 生成可继续编辑的 draw.io 图形摘要与机制概念图（Codex image2） |
| 选刊 + 投稿前审查 | [sci-select](https://github.com/keros68/sci-select) | 候选期刊发现、IF/分区指标查询、按目标期刊 Author Guidelines 做投稿前定向审查 |
| 学位论文格式 | [cugb-doctoral-thesis-format](https://github.com/keros68/cugb-doctoral-thesis-format) | 中国地质大学（北京）博士论文 Word 格式本地预检，可作为其他学校格式 skill 的起点 |

## 基础设施

| Skill | 用途 |
|-------|------|
| [ai-cross](https://github.com/keros68/ai-cross) | 多模型分工与跨厂商交叉验证：分层派发、互相复查关键产出、派发过程留痕 |

## 桌面工具

- [metrik](https://github.com/keros68/metrik) — 本地优先的 AI Agent 用量统计：官方配额、本地 Token、估算成本三类事实分开呈现（Windows 小组件 / macOS 菜单栏）
- [geoscan](https://github.com/keros68/geoscan) — 扫描地质剖面图半自动矢量化（DXF/GeoJSON + MapGIS 6.7 桥接）

> 已归档：[journal-fit](https://github.com/keros68/journal-fit)（投稿前定向审查，已并入 sci-select）
