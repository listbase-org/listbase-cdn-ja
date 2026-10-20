# 時間とカレンダー (Time & Calendar)

1 datasets — 1,503 records

> Browse at [listbase.org/ja/time/](https://listbase.org/ja/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [日本の国民の祝日・銀行休業日 (1949–2030)](ja-shukujitsu-kokka-no-kyujitsu.json) | 1,503 | 726 KB | [CSV](ja-shukujitsu-kokka-no-kyujitsu_JA.csv) | [Excel](ja-shukujitsu-kokka-no-kyujitsu_JA.xlsx) | [View](https://listbase.org/ja/time/ja-shukujitsu-kokka-no-kyujitsu/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.ja.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.ja.listbase.org/time/ja-shukujitsu-kokka-no-kyujitsu.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ja/time/)
