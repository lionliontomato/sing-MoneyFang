# 慌慌の存鑽存歌｜GitHub Pages 網站

這是一個可以直接上傳到 GitHub Pages 的靜態網站。

## 本次修改

- 標題改為：慌慌の存鑽存歌
- 背景色改為莫蘭迪藍
- Google 試算表連結改為：`https://docs.google.com/spreadsheets/d/1-Ixjp1Pclti4MfjqAaROtjWZThi4ysXDaxk1SlTuPXk/edit?usp=sharing`

## 內容

- `index.html`：網站主頁
- `style.css`：網站視覺樣式
- `script.js`：自動讀取 Google 試算表 A～E 欄與搜尋功能
- `.nojekyll`：避免 GitHub Pages 額外處理靜態檔案

## GitHub Pages 使用方式

1. 將 ZIP 解壓縮。
2. 把資料夾內的 `index.html`、`style.css`、`script.js`、`.nojekyll` 上傳到 GitHub Repository 根目錄。
3. 到 Repository 的 `Settings` → `Pages`。
4. Source 選擇 `Deploy from a branch`。
5. Branch 選 `main`，資料夾選 `/root`，按 Save。
6. 等 GitHub 產生網址後即可使用。

## 注意

若網站顯示「資料載入失敗」，請到 Google 試算表右上角「共用」確認權限：

- 一般存取權限：知道連結的使用者
- 權限：檢視者
