# 食品 (Food & Nutrition)

1 datasets — 1,095 records

> Browse at [listbase.org/ja/food/](https://listbase.org/ja/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [日本のミシュランガイド掲載レストラン](ja-mishuran-resutoran.json) | 1,095 | 1128 KB | [CSV](ja-mishuran-resutoran_JA.csv) | [Excel](ja-mishuran-resutoran_JA.xlsx) | [View](https://listbase.org/ja/food/ja-mishuran-resutoran/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.ja.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.ja.listbase.org/food/ja-mishuran-resutoran.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ja/food/)
