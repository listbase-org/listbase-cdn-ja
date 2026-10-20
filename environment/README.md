# 環境 (Environment)

2 datasets — 593 records

> Browse at [listbase.org/ja/environment/](https://listbase.org/ja/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [日本の発電所](ja-hatsudensho.json) | 522 | 194 KB | [CSV](ja-hatsudensho_JA.csv) | [Excel](ja-hatsudensho_JA.xlsx) | [View](https://listbase.org/ja/environment/ja-hatsudensho/) |
| [日本の原子力発電所](ja-genshiryoku-hatsudensho.json) | 71 | 29 KB | [CSV](ja-genshiryoku-hatsudensho_JA.csv) | [Excel](ja-genshiryoku-hatsudensho_JA.xlsx) | [View](https://listbase.org/ja/environment/ja-genshiryoku-hatsudensho/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.ja.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.ja.listbase.org/environment/ja-hatsudensho.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ja/environment/)
