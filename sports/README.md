# スポーツ (Sports)

5 datasets — 20,326 records

> Browse at [listbase.org/ja/sports/](https://listbase.org/ja/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [NPB打撃通算成績 (NPB career batting statistics by season)](ja-npb-dageki-seiseki.json) | 12,066 | 7937 KB | [CSV](ja-npb-dageki-seiseki_JA.csv) | [Excel](ja-npb-dageki-seiseki_JA.xlsx) | [View](https://listbase.org/ja/sports/ja-npb-dageki-seiseki/) |
| [NPB投球通算成績 (NPB career pitching statistics by season)](ja-npb-toukyu-seiseki.json) | 5,862 | 4138 KB | [CSV](ja-npb-toukyu-seiseki_JA.csv) | [Excel](ja-npb-toukyu-seiseki_JA.xlsx) | [View](https://listbase.org/ja/sports/ja-npb-toukyu-seiseki/) |
| [NPB選手名鑑 (NPB player directory)](ja-npb-senshu-meikan.json) | 2,252 | 986 KB | [CSV](ja-npb-senshu-meikan_JA.csv) | [Excel](ja-npb-senshu-meikan_JA.xlsx) | [View](https://listbase.org/ja/sports/ja-npb-senshu-meikan/) |
| [NPB順位表 2019–2026 (NPB final league standings)](ja-npb-junni.json) | 96 | 65 KB | [CSV](ja-npb-junni_JA.csv) | [Excel](ja-npb-junni_JA.xlsx) | [View](https://listbase.org/ja/sports/ja-npb-junni/) |
| [日本のサッカークラブ (Japanese football clubs)](ja-sakka-kurabu.json) | 50 | 15 KB | [CSV](ja-sakka-kurabu_JA.csv) | [Excel](ja-sakka-kurabu_JA.xlsx) | [View](https://listbase.org/ja/sports/ja-sakka-kurabu/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.ja.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.ja.listbase.org/sports/ja-npb-dageki-seiseki.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ja/sports/)
