# cold-war-trial

Hugo 網站骨架的測試 repo。站內所有文字、人名、資料都是測試用的假資料。

## 本機預覽

```bash
./bin/hugo server
```

`bin/hugo` 是小腳本，依 `.hugo-version` 從 `~/.local/share/hugo/<版本>/` 取用 Hugo，本機沒有就從官方 release 下載並以 checksums 驗證（僅支援 macOS）。

## 目錄

| 路徑 | 內容 |
|---|---|
| `content/review/` | 測試文章：入口頁與各版章節（網址帶版本號，如 `/review/2026/ch1/`） |
| `content/members/` | 測試成員，每人一頁 |
| `assets/data/publications.tsv` | 出版清單（TSV）；成員頁依 `成員id` 篩出本人條目 |
| `assets/data/activities.tsv` | 活動清單（TSV） |
