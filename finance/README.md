# 金融と貿易 (Finance & Trade)

9 datasets — 4,372 records

> Browse at [listbase.org/ja/finance/](https://listbase.org/ja/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [全国銀行コード一覧 (Bank codes of Japan)](ja-banks.json) | 1,152 | 339 KB | [CSV](ja-banks_JA.csv) | [Excel](ja-banks_JA.xlsx) | [View](https://listbase.org/ja/finance/ja-banks/) |
| [三菱ＵＦＪ銀行支店コード一覧 (Branch codes of MUFG Bank (Mitsubishi UFJ Bank))](ja-mufg-bank-branches.json) | 717 | 214 KB | [CSV](ja-mufg-bank-branches_JA.csv) | [Excel](ja-mufg-bank-branches_JA.xlsx) | [View](https://listbase.org/ja/finance/ja-mufg-bank-branches/) |
| [SWIFT/BICコード — 日本](ja-swift-codo.json) | 712 | 98 KB | [CSV](ja-swift-codo_JA.csv) | [Excel](ja-swift-codo_JA.xlsx) | [View](https://listbase.org/ja/finance/ja-swift-codo/) |
| [三井住友銀行支店コード一覧 (Branch codes of Sumitomo Mitsui Banking Corporation (SMBC))](ja-smbc-bank-branches.json) | 567 | 163 KB | [CSV](ja-smbc-bank-branches_JA.csv) | [Excel](ja-smbc-bank-branches_JA.xlsx) | [View](https://listbase.org/ja/finance/ja-smbc-bank-branches/) |
| [みずほ銀行支店コード一覧 (Branch codes of Mizuho Bank)](ja-mizuho-bank-branches.json) | 494 | 136 KB | [CSV](ja-mizuho-bank-branches_JA.csv) | [Excel](ja-mizuho-bank-branches_JA.xlsx) | [View](https://listbase.org/ja/finance/ja-mizuho-bank-branches/) |
| [りそな銀行支店コード一覧 (Branch codes of Resona Bank)](ja-resona-bank-branches.json) | 319 | 90 KB | [CSV](ja-resona-bank-branches_JA.csv) | [Excel](ja-resona-bank-branches_JA.xlsx) | [View](https://listbase.org/ja/finance/ja-resona-bank-branches/) |
| [横浜銀行支店コード一覧 (Branch codes of Yokohama Bank)](ja-yokohama-bank-branches.json) | 203 | 57 KB | [CSV](ja-yokohama-bank-branches_JA.csv) | [Excel](ja-yokohama-bank-branches_JA.xlsx) | [View](https://listbase.org/ja/finance/ja-yokohama-bank-branches/) |
| [埼玉りそな銀行支店コード一覧 (Branch codes of Saitama Resona Bank)](ja-saitama-resona-bank-branches.json) | 114 | 34 KB | [CSV](ja-saitama-resona-bank-branches_JA.csv) | [Excel](ja-saitama-resona-bank-branches_JA.xlsx) | [View](https://listbase.org/ja/finance/ja-saitama-resona-bank-branches/) |
| [ゆうちょ銀行支店コード一覧 (Branch codes of Japan Post Bank (Yucho))](ja-yucho-bank-branches.json) | 94 | 29 KB | [CSV](ja-yucho-bank-branches_JA.csv) | [Excel](ja-yucho-bank-branches_JA.xlsx) | [View](https://listbase.org/ja/finance/ja-yucho-bank-branches/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.ja.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.ja.listbase.org/finance/ja-banks.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ja/finance/)
