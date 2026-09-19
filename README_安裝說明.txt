AnLedger V0.9.1

本版重點：
1. 日記第一次開啟即可直接書寫，不需要先按「清除整頁」。
2. Apple Pencil 手寫引擎改為 requestAnimationFrame + coalesced events。
3. 不再每個 pointermove 都把整張 Canvas 轉 PNG 保存；改為一筆完成後保存。
4. 支援 Apple Pencil pressure line width。
5. Pencil 優先、避免手掌/手指誤觸（觸控 pen 模式下忽略 touch pointer）。
6. 手寫完成後會自動嘗試分析；目前純 PWA 沒有真正 AI API 時，會顯示「等待分析引擎」，旁邊保留「執行分析」按鈕。
7. PWA cache 版本已升級為 v0.9.1，並補上 iOS apple-touch-icon。

使用：
Safari 開啟 GitHub Pages 的 index.html → 分享 → 加入主畫面。
