部署方式：

方法 A：Netlify Drop（最簡單）
1. 開啟 https://app.netlify.com/drop
2. 將整個 intel_style_gpx_site 資料夾拖進去
3. Netlify 會產生一個 https://xxxxx.netlify.app 網址
4. 用 iPad / Edge / Safari 開啟該網址即可使用

方法 B：GitHub Pages
1. 建立 GitHub repository
2. 上傳 index.html
3. 到 Settings > Pages
4. Source 選 Deploy from branch
5. Branch 選 main / root
6. 等待產生 https://你的帳號.github.io/專案名/

注意：
不要用 edge://external-file 或 file:// 開啟，否則外部地圖圖資可能無法載入。
