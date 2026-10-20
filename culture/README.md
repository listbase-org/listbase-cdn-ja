# 文化と宗教 (Culture & Religion)

2 datasets — 3,265 records

> Browse at [listbase.org/ja/culture/](https://listbase.org/ja/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [日本の博物館 (Museums in Japan)](ja-hakubutsukan.json) | 3,242 | 692 KB | [CSV](ja-hakubutsukan_JA.csv) | [Excel](ja-hakubutsukan_JA.xlsx) | [View](https://listbase.org/ja/culture/ja-hakubutsukan/) |
| [日本の世界遺産](ja-sekai-isan.json) | 23 | 26 KB | [CSV](ja-sekai-isan_JA.csv) | [Excel](ja-sekai-isan_JA.xlsx) | [View](https://listbase.org/ja/culture/ja-sekai-isan/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.ja.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.ja.listbase.org/culture/ja-hakubutsukan.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ja/culture/)
