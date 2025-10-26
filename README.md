# 樑搜尋系統 — 部署說明

這個資料夾已經可以直接部署成網站，index.html 即是首頁。

## 方法一：GitHub Pages（免費且穩定）
1. 到 https://github.com 註冊或登入帳號。
2. 建立一個新 Repository，名稱可自訂（例如 `liang-search`）。
3. 上傳整個資料夾（或直接把這個 ZIP 解壓後全部檔案拖進去）。
4. 在 Repo 內到 **Settings → Pages**：
   - Build and deployment 選擇 **Deploy from a branch**
   - Branch 選 **main**，資料夾選 **/**（root）
   - Save 後等幾分鐘，右上角就會顯示網站網址。

## 方法二：Netlify（免費、自動部署）
1. https://app.netlify.com → New site from Git，連接到你的 GitHub Repo。
2. Build 設定保持預設（因為是純靜態），**Publish directory** 設成 `.`（root）。
3. 完成後會得到 `https://xxxxx.netlify.app` 網址。

## 方法三：Vercel（免費）
1. https://vercel.com → New Project → Import Git Repo。
2. 設定為 **Framework Preset: Other**，Build/Output 保持預設，輸出目錄（Output）為 `.`。
3. 完成後會得到 `https://xxxxx.vercel.app` 網址。

## 本機預覽
直接雙擊 `index.html` 即可在瀏覽器開啟。（若包含 AJAX 讀檔則建議以 Live Server 啟動）
