# KonaTaJ-POP

霧裡聽見 — 一份以暗色霧氣、柔光與互動文字呈現的音樂指南。

## 內容

- 12 種 Pop 曲風的聽感與關聯介紹。
- 10 組音樂人的經典曲、代表專輯與 27 張黑膠收藏推薦。
- 曲風、音樂人、交會三個獨立分頁，搭配漂浮導覽。
- 全頁霧氣、游標撥霧、文字浮現與卡片柔光互動。
- 曲風與音樂人搜尋、響應式版面、鍵盤導覽與減少動態效果支援。

## 使用

網站網址：[pop.konataj.com](https://pop.konataj.com)

也可以直接開啟 `index.html` 在本機瀏覽。

這是一個無需建置的靜態網站，CSS、JavaScript 與內容資料包含在 `index.html`。
字型使用 Google Fonts；無法連線時會使用系統字型。

## 更新

網站透過 Cloudflare Pages 連接此 GitHub 儲存庫。
修改 `index.html` 並提交到 `main` 分支後，Cloudflare 會自動建置及部署；部署成功後正式網址會更新。

部署設定：

- Framework preset：None
- Production branch：`main`
- Build command：`mkdir -p public && cp index.html public/index.html`
- Build output directory：`public`

發布目錄只包含網站所需的 `index.html`。
請勿將 API 金鑰、密碼、登入憑證、`.env` 或其他私人資料加入此公開儲存庫。

## 音樂與黑膠資料

各張推薦附發行商、官方商店或零售商的版本來源。
收藏排行依聽感偏好整理，並非銷量或壓片音質排名；庫存、售價與配送以商店為準。
唱片圖形為程式繪製的示意圖。
