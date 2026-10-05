ActPips 公開網站（GitHub Pages）使用說明
==========================================

呢個資料夾有 3 樣嘢：
  index.html      — 網站檔案（示範數據版，之後會更新做真數據）
  deploy.command  — 你部 Mac 嘅更新工具（雙擊即用）
  README.txt      — 呢份說明

────────────────────────────────────────
第一步：開 GitHub 帳戶（一次過，10 分鐘）
────────────────────────────────────────
1. 開瀏覽器去 https://github.com
2. 撳右上角 Sign up，用你嘅 email 註冊（免費）
3. 完成驗證

────────────────────────────────────────
第二步：開一個 repo（一次過，3 分鐘）
────────────────────────────────────────
1. 登入咗之後，撳右上角 + → New repository
2. Repository name 填：actpips-demo
3. Public（公開）保持揀咗
4. 唔使勾任何嘢，直接撳 Create repository

────────────────────────────────────────
第三步：上傳網站檔案（一次過，2 分鐘）
────────────────────────────────────────
1. 喺新 repo 頁面撳 Add file → Upload files
2. 將呢個資料夾入面嘅 index.html 同 README.txt
   兩個檔拖入去上傳區
3. 撳綠色 Commit changes

────────────────────────────────────────
第四步：開啟 GitHub Pages（一次過，2 分鐘）
────────────────────────────────────────
1. 喺 repo 頁面撳 Settings（設定）
2. 左邊選單撳 Pages
3. Branch 揀 main，Folder 揀 / (root)
4. 撳 Save
5. 等 1-2 分鐘，頁面會顯示你個網站網址，例如：
   https://你的用戶名.github.io/actpips-demo/
   撳入去就見到 ActPips！

────────────────────────────────────────
之後每次更新（約 1 分鐘）
────────────────────────────────────────
1. 喺你部 Mac 雙擊 run.command 跑 scanner（照舊）
2. 雙擊呢個資料夾入面嘅 deploy.command
   （佢會自動將最新 report.html 轉做 index.html）
3. 開 https://github.com/你嘅用戶名/actpips-demo/upload/main
4. 將 index.html 拖入去 → Commit changes
5. 等 1 分鐘，公開網站就更新

────────────────────────────────────────
問答
────────────────────────────────────────
Q: 網站係咪「即時」更新？
A: 唔係。GitHub Pages 放嘅係「快照」——你手動更新一次，
   網站就更新一次。呢個係 demo 版做法（免費）。
   真正即時版本要等正式期（雲端 server），到時呢個網站
   會原封不動搬過去，唔使重寫。

Q: 個網址可唔可以變靚啲（例如 actpips.com）？
A: 可以。正式期將 actpips.com 指去 GitHub Pages 就得
   （GitHub 支援自訂域名，免費 HTTPS）。而家唔使理。

Q: 示範數據會唔會誤導人？
A: 而家 index.html 係示範數據（K 線係模擬），
   日曆係真嘅。你跑一次真 scanner 再 deploy 就係真數據。
   未公開之前，記得更新先好 share。
