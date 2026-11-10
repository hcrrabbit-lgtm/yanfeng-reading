# 炎峰國小 閱讀大補帖

給家長和老師用的閱讀網站整理頁，收錄 8 個線上閱讀網站。

- 網址：https://yanfeng-reading.hcrrabbit.workers.dev
- 網頁檔案：`public/index.html`（整個網站就這一個檔案）
- 這個網站只放連結和介紹，不存任何學生資料。

## 怎麼修改

**最簡單：請 AI 幫忙**
把 `public/index.html` 上傳給 Claude（或其他 AI），直接說要改什麼，例如：
- 「幫我新增一個網站：○○○，網址是 ○○○，簡介是 ○○○，分類放在繪本故事」
- 「把瓜瓜漂流的登入方式改成 ○○○」
- 「刪掉第 5 個網站」

拿到新檔案後，用它取代 `public/index.html`，存回 GitHub，1～2 分鐘後網站就會自動更新。

**小地方自己改**
在 GitHub 打開 `public/index.html`，按鉛筆圖示，找到要改的中文字直接改，按「Commit changes」存檔即可。

## 運作方式

GitHub 這個資料夾的 main 分支 → 自動發布到 Cloudflare Workers。
免費方案，固定網頁不限瀏覽次數。

## 交接

1. GitHub：Settings → 最下方 Transfer ownership，轉給接手者的帳號。
2. Cloudflare：接手者用自己的帳號重新連結這個 GitHub 資料夾（網址會換成新帳號的名稱）。
3. 建議定期（每學期一次）點過所有連結，確認沒有失效。
