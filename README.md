# markdown語法練習器

這個專案要製作一個可在瀏覽器中使用的 Markdown 語法練習器，讓使用者能輸入 Markdown、即時查看預覽，並透過練習題熟悉常見語法。

## 專案目標

- 建立一個靜態網頁版 Markdown 練習器。
- 支援基礎 Markdown 語法練習，例如標題、清單、連結、圖片、引用、程式碼區塊與表格。
- 讓後續 Codex 工作能清楚接續進度、待辦與部署狀態。
- 使用 GitHub Pages 部署，不使用 Firebase。

## 使用對象

- 想練習 Markdown 語法的初學者。
- 需要快速測試 Markdown 顯示效果的使用者。
- 後續接手開發此靜態網頁的 Codex 或開發者。

## 專案結構

```text
.
├── AGENTS.md
├── README.md
├── PROGRESS.md
├── TODO.md
├── DECISIONS.md
├── DEPLOYMENT.md
├── app/
├── assets/
├── materials/
├── outputs/
├── references/
├── scripts/
├── working/
└── archive/
```

## 資料夾用途

- `app/`：靜態網頁原始碼。
- `assets/`：圖片、圖示、樣式資產或其他前端素材。
- `materials/`：使用者提供的原始資料或參考素材。
- `outputs/`：完成版輸出、截圖、匯出成果或交付檔。
- `references/`：外部參考文件、設計參考、語法規格摘要。
- `scripts/`：輔助腳本。
- `working/`：開發中暫存內容。
- `archive/`：封存的舊版本或不再使用資料。

## 目前狀態

專案已初始化為靜態網頁專案。下一步是實作 Markdown 編輯、預覽與練習題流程。

