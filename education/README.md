# 教育 (Education)

2 datasets — 1,038 records

> Browse at [listbase.org/ja/education/](https://listbase.org/ja/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Japan — Universities (大学)](ja-daigaku.json) | 572 | 158 KB | [CSV](ja-daigaku_JA.csv) | [Excel](ja-daigaku_JA.xlsx) | [View](https://listbase.org/ja/education/ja-daigaku/) |
| [日本の大学院（博士課程）専攻一覧 (Japan — Doctoral Graduate-School Programs)](ja-daigakuin-hakushi-senko.json) | 466 | 102 KB | [CSV](ja-daigakuin-hakushi-senko_JA.csv) | [Excel](ja-daigakuin-hakushi-senko_JA.xlsx) | [View](https://listbase.org/ja/education/ja-daigakuin-hakushi-senko/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.ja.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.ja.listbase.org/education/ja-daigaku.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ja/education/)
