# PROGRESS

## 2026-06-18

- 已依 `https://github.com/chunyifish/codex-project-template` 的 `INIT.md` 流程初始化專案。
- 已確認專案名稱為 `markdown語法練習器`。
- 已確認專案類型為靜態網頁。
- 已確認部署目標為 GitHub Pages。
- 已確認不使用 Firebase。
- 已建立專案文件與標準資料夾。
- 已建立 GitHub Pages workflow 草稿。
- 已初始化 Git 並建立初始 commit。
- 已建立 GitHub repo：https://github.com/chunyifish/markdown-syntax-practice
- 已啟用 GitHub Pages workflow 模式。
- 已加入題目區、自動檢查與 `marked` Markdown 預覽。
- 已產出 `outputs/Codex懶人包-初始化可接續專案工作區.md`，整理為可直接交給 Codex 執行的專案初始化懶人包。
- 已將懶人包加入 `chunyifish/codex-project-template` 的 `docs/01-初始化可接續專案工作區.md`，並在 README 新增入口連結；已推送 commit `4d7817e`。
- 已依使用者要求將懶人包獨立為新 repo：https://github.com/chunyifish/codex-lazy-guides
- 已將 `codex-project-template` 中的懶人包文件與 README 入口移除，避免與模板 repo 綁定；已推送 commit `edaedf9`。

## 目前狀態

專案已有可操作的 Markdown 練習器初版，可選題、輸入、即時預覽並自動判斷完成狀態。

## 收工交接

- 目前遠端 repo：https://github.com/chunyifish/markdown-syntax-practice
- 目前公開網站：https://chunyifish.github.io/markdown-syntax-practice/
- 獨立懶人包 repo：https://github.com/chunyifish/codex-lazy-guides
- 最新提交：`88c2aef Add Markdown lesson checks`
- GitHub Pages 最新部署已成功，公開網址回應 `200 OK`。
- 本機瀏覽器自動化驗證已通過：頁面載入、5 題產生、二級標題題與連結題完成判斷、Markdown 預覽、console 無錯誤。
- 已知注意事項：GitHub Actions 仍有 Node 20 deprecation annotation，但部署成功；本機曾出現 `.git/AUTO_MERGE.lock` 殘留提示，但 `git status`、`commit`、`push` 均可正常運作；本機 `working/` 內保留了 `codex-lazy-guides` 與 `codex-project-template` 兩個工作副本。

## 下一步

檢查手機版互動體驗，並補上更多練習題與答案提示。
