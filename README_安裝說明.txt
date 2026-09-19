AnLedger V0.8 — iPhone / iPad 測試包

檔案：
- index.html：AnLedger 主程式
- manifest.json：PWA App 設定
- sw.js：離線快取
- icons/：iPhone / iPad 主畫面圖示
- AnLedger_V0.8.html：版本備份

iPhone / iPad：
1. 將整個資料夾放到一個 HTTPS 網址上（例如你的網站空間 / GitHub Pages / Cloudflare Pages）。
2. 用 Safari 開啟 index.html。
3. 點「分享」→「加入主畫面」。
4. 主畫面會使用 AnLedger 名稱與橘白貓圖示。
5. 點主畫面圖示後會以獨立 App 介面開啟。

注意：直接從 iPhone「檔案」App 開啟本機 HTML，通常不能完整安裝成 PWA；要用 HTTPS 網站測試最穩定。
