# AI 學習筆記站

生成式 AI 課程「第九週作業 1103」的小專案：一個純靜態的個人筆記網站，並附上讓 AI 能照規則持續擴充的 `AGENTS.md` / `CLAUDE.md`。

## 專案簡介
- 用途：整理課程每週重點
- 技術：純 HTML + CSS，無任何框架與外部依賴
- 規則：見 [AGENTS.md](AGENTS.md)（`CLAUDE.md` 會引用它）

## 本機預覽
直接用瀏覽器開啟 `index.html` 即可。

## 部署到 GitHub Pages
1. 建立新的 GitHub repository，將本資料夾所有檔案上傳（`index.html` 需在根目錄）。
2. 到 repository 的 **Settings → Pages**。
3. Source 選擇 **Deploy from a branch**，Branch 選 `main`、資料夾選 `/ (root)`，按 Save。
4. 約一兩分鐘後，網址為 `https://<你的帳號>.github.io/<repository 名稱>/`。

## 如何新增一份筆記
請 AI 讀完 `AGENTS.md` 後，說：「依規則新增第 10 週筆記，主題是 ○○○」。
