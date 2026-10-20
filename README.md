# ListBase CDN — 日本語 (ja)

Open dataset collection for **日本語** (Japanese).
430 datasets across 11 categories with 422,498 total records.

> Browse and download at [https://listbase.org/ja/](https://listbase.org/ja/)

## Categories

| Category | Datasets |
|----------|----------|
| [文化と宗教 (Culture & Religion)](culture/) | 2 |
| [教育 (Education)](education/) | 2 |
| [環境 (Environment)](environment/) | 2 |
| [金融と貿易 (Finance & Trade)](finance/) | 9 |
| [食品 (Food & Nutrition)](food/) | 1 |
| [地理 (Geography)](geography/) | 126 |
| [政治 (Politics)](politics/) | 48 |
| [リファレンス (Reference)](reference/) | 183 |
| [スポーツ (Sports)](sports/) | 5 |
| [時間とカレンダー (Time & Calendar)](time/) | 1 |
| [交通 (Transport)](transport/) | 51 |

## Usage

### Browse on the web
Visit [listbase.org/ja/](https://listbase.org/ja/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.ja.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.ja.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.ja.listbase.org/geography/th-central-provinces_JA.xlsx
curl -O https://cdn.ja.listbase.org/geography/th-central-provinces_JA.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.ja.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.ja.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_JA.csv   # CSV download
│   └── {dataset}_JA.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
