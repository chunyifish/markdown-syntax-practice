# DECISIONS

## 2026-06-18 - 專案類型

決定建立靜態網頁專案，不加入後端服務。

理由：Markdown 語法練習器可先用 HTML、CSS、JavaScript 完成核心互動，部署到 GitHub Pages 即可使用。

## 2026-06-18 - 部署方式

決定使用 GitHub Pages。

理由：專案是靜態網頁，GitHub Pages 足以承載初版功能，且與 GitHub repo 管理流程一致。

## 2026-06-18 - Firebase

決定不使用 Firebase。

理由：目前需求沒有資料庫、登入、檔案儲存或雲端函式。

## 2026-06-18 - Markdown 解析器

決定使用 `marked@18.0.5` CDN ESM 版本作為 Markdown 預覽解析器。

理由：專案目前是 GitHub Pages 靜態網頁，不需要建置流程；`marked` 支援 GitHub Flavored Markdown，可處理表格、程式碼區塊與常見語法，比自製簡易解析器穩定。固定版本可避免未來 CDN 自動升級造成行為改變；使用 ESM 匯入可配合 `marked@18` 的瀏覽器載入方式。
