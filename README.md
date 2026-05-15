# stock-research

個股深度研究報告，以靜態 HTML 呈現，透過 GitHub Pages 公開。

## Live Site

https://r0ywu.github.io/stock-research/

## Structure

```
.
├── index.html       # 報告索引（台股 / 美股 tabs）
├── tw/              # 台股報告
└── us/              # 美股報告
```

報告檔名慣例：`<TICKER>_<Type>_<YYYYMMDD>.html`（Type 例如 `Report`、`Industry`、`Brief`）

## Enable GitHub Pages

首次推送後，到 repo 設定啟用 Pages：

1. 進入 **Settings → Pages**
2. **Source**：`Deploy from a branch`
3. **Branch**：`main` / `/ (root)`
4. 儲存後等待約 1–2 分鐘部署完成

## Add a New Report

1. 依 `<TICKER>_<Type>_<YYYYMMDD>.html` 命名，放入 `tw/`（台股）或 `us/`（美股）
2. 編輯 `index.html`，在對應 tab 的 `<ul class="report-list">` 中新增一個 `<li>`（`href` 需含 `tw/` 或 `us/` 前綴）
3. Commit & push，Pages 會自動更新

## Disclaimer

本 repo 內容僅為個人研究筆記，不構成任何投資建議。
