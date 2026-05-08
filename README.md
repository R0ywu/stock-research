# stock-research

個股深度研究報告，以靜態 HTML 呈現，透過 GitHub Pages 公開。

## Live Site

https://r0ywu.github.io/stock-research/

## Reports

| Ticker | Name | Date |
|--------|------|------|
| 2645 | 長榮航太 | 2026.04.23 |

## Enable GitHub Pages

首次推送後，到 repo 設定啟用 Pages：

1. 進入 **Settings → Pages**
2. **Source**：`Deploy from a branch`
3. **Branch**：`main` / `/ (root)`
4. 儲存後等待約 1–2 分鐘部署完成

## Add a New Report

1. 將新的 HTML 檔以股票代號命名（例：`2330.html`）放入 repo 根目錄
2. 編輯 `index.html`，在 `<ul class="report-list">` 中新增一個 `<li>`
3. Commit & push，Pages 會自動更新

## Disclaimer

本 repo 內容僅為個人研究筆記，不構成任何投資建議。
