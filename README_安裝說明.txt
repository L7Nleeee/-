AnLedger V1.0

本版重點：
1. Apple Pencil 手寫區獨立攔截觸控，其他按鈕恢復正常可點。
2. 同一天支援多頁日記，可新增頁面。
3. 所有頁面視為同一篇日記，AI hook 可一次取得全部頁面。
4. 書寫結束後會自動嘗試呼叫 window.AnLedgerAI.analyze({date,pages,mode}).
5. 若分析引擎尚未注入，會顯示等待 AI 分析引擎，不會假裝已分析。
6. 加入 AnLedger 橘貓助手互動區與輕微浮動動畫。
7. PWA cache 已更新為 anledger-v100。

若 iPad 主畫面仍顯示舊圖示：刪除舊 PWA → Safari 重新開啟 index.html → 再加入主畫面。
