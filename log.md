---
title: 更新日志
created: 2026-04-21
updated: 2026-04-21
type: meta
tags: [meta]
---

# 更新日志

## [2026-04-21] create | 初始化知识库

### 创建目录
- `原始资料/文章/`
- `raw/papers/`
- `raw/transcripts/`
- `raw/assets/`
- `entities/`
- `核心概念/`
- `概念对比/`
- `问答/`
- `_templates/`

### 创建文件
- `SCHEMA.md` — 知识库规范定义
- `index.md` — 知识库总索引
- `log.md` — 本更新日志
- `README.md` — 知识库说明文档
- `_templates/概念模板.md` — 概念页面模板
- `_templates/问答模板.md` — 问答页面模板

---

## 如何添加记录

在 `## [YYYY-MM-DD]` 下方按以下格式追加：

```
## [YYYY-MM-DD] action | subject
- 变更内容描述
- 涉及的页面/文件
```

action 类型：`create` | `update` | `merge` | `ingest` | `correct`
