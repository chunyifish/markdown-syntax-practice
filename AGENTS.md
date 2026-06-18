# AGENTS.md - markdown語法練習器專案指引

本檔案是此專案的專用指引，適用範圍為本專案根目錄與其子資料夾。

## 專案定位

- 專案名稱：markdown語法練習器
- 專案類型：靜態網頁
- 專案目標：製作一個可在瀏覽器中操作的 Markdown 語法練習器。
- 部署目標：GitHub Pages
- Firebase：不使用

## 工作原則

- 先讀 `README.md`、`PROGRESS.md`、`TODO.md`、`DECISIONS.md`、`DEPLOYMENT.md`，再開始實作。
- 保持靜態網頁架構，除非使用者明確要求，不加入框架、建置工具、後端服務或 Firebase。
- 優先使用單純的 HTML、CSS、JavaScript 完成可驗證功能。
- 每次修改後更新 `PROGRESS.md` 與必要的 `TODO.md`。
- 重要技術決策寫入 `DECISIONS.md`。
- GitHub Pages、repo、部署狀態與網址寫入 `DEPLOYMENT.md`。
- 不提交 `.env`、token、金鑰或任何敏感資料。

## 檔案放置規則

- `app/`：放靜態網頁原始碼，例如 `index.html`、CSS、JavaScript。
- `assets/`：放圖片、圖示、字型、樣式素材等前端資產。
- `materials/`：放使用者提供的原始資料；目前無原始資料。
- `outputs/`：放完成輸出、截圖、匯出檔或交付成果。
- `references/`：放 Markdown 規格、語法說明或設計參考。
- `scripts/`：放輔助腳本。
- `working/`：放開發中暫存內容。
- `archive/`：放封存內容，不作為主要工作區。

## 靜態網頁實作方向

- 練習器應以「輸入 Markdown、即時預覽、完成練習」為主要流程。
- UI 需適合反覆練習與快速掃描，避免做成行銷型首頁。
- 若需要 Markdown 解析器，優先選擇成熟、輕量、可由 CDN 使用的套件；使用前更新 `DECISIONS.md`。
- 若加入第三方套件，需確認 GitHub Pages 可直接載入，並在 `DEPLOYMENT.md` 記錄。

## 驗證要求

- 修改前端後，至少以瀏覽器或本機靜態檢查確認頁面可開啟。
- 若尚未能完整驗證，完成回報必須明確說明未驗證項目。

