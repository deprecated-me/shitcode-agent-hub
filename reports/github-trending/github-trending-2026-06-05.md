# GitHub Trending 週榜觀察（2026-06-05）

來源：<https://github.com/trending?since=weekly>

## 1) 今日 Top 5
1. [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) — Python — 14,566 stars this week
2. [chopratejas/headroom](https://github.com/chopratejas/headroom) — Python — 9,421 stars this week
3. [microsoft/markitdown](https://github.com/microsoft/markitdown) — Python — 17,165 stars this week
4. [revfactory/harness](https://github.com/revfactory/harness) — HTML — 2,159 stars this week
5. [EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin) — TypeScript — 2,111 stars this week

## 2) 主題趨勢
- 「agent workflow 的實用工具層」還在升溫。[chopratejas/headroom](https://github.com/chopratejas/headroom)、[microsoft/markitdown](https://github.com/microsoft/markitdown)、[revfactory/harness](https://github.com/revfactory/harness)、[EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin) 分別對應 context 壓縮、文件轉 Markdown、agent team 編排、跨代理外掛整合，熱門焦點明顯往可直接接進工作流的組件靠攏。
- Python 仍是這波 AI 應用與周邊基建的主承載語言。今日 Top 5 裡有三個 Python repo，而且分別落在內容生成、token 成本控制、文件處理三個不同切面，表示需求不是集中在單一題材，而是整條工具鏈同時升溫。
- 「少一點 slop、更多 agent engineering」還在首頁前段延燒。[affaan-m/ECC](https://github.com/affaan-m/ECC)、[Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)、[supermemoryai/supermemory](https://github.com/supermemoryai/supermemory) 都圍繞 agent 品質、記憶與 execution 系統化，代表這波熱度不只在模型能力，也在 workflow 的可維運性。
- 開源語音 / 多模態基礎能力開始回到可見區。[OpenBMB/VoxCPM](https://github.com/OpenBMB/VoxCPM) 與 [OpenMOSS/MOSS-TTS](https://github.com/OpenMOSS/MOSS-TTS) 都出現在本週首頁，表示除了 agent tooling，語音生成與 TTS 基模也重新吸到開發者注意力。

## 3) 值得追蹤專案
- [chopratejas/headroom](https://github.com/chopratejas/headroom)：昨天 6,245，今天 9,421，單日增加 3,176，而且連三份保存報告都留在 Top 5；「先壓縮 logs / tool outputs / RAG chunks 再餵 LLM」正好打中真實 agent 成本痛點。
- [EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin)：今天直接打進 Top 5，用完整 repo 名 `rg -F` 在既有保存報告中查無結果，依規則視為未出現 / 新進榜候選；它直接對準 Claude Code、Codex、Cursor 這類 agent coding 工具，擴散速度值得盯。
- [revfactory/harness](https://github.com/revfactory/harness)：昨天剛進 Top 5，今天仍留在前段且 weekly stars 從 2,005 升到 2,159，顯示「自動設計 domain-specific agent teams / skills」不是單日噪音。
- [OpenBMB/VoxCPM](https://github.com/OpenBMB/VoxCPM)：今天榜內有 5,771 stars this week，用完整 repo 名 `rg -F` 在既有保存報告中查無結果，可視為未出現 / 新進榜候選；Tokenizer-free TTS 和 voice cloning 這條線如果持續留榜，可能會變成下一波多模態開源主題。
- [supermemoryai/supermemory](https://github.com/supermemoryai/supermemory)：今天榜內有 2,740 stars this week，和 [chopratejas/headroom](https://github.com/chopratejas/headroom)、[affaan-m/ECC](https://github.com/affaan-m/ECC) 一起把「agent memory / context engineering」推成更完整的副主題，值得觀察是否會再往前排。

## 4) 歷史比對
- 新進榜 / 進出變化：相較 2026-06-04，今天 Top 5 新成員是 [EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin)；[Lum1104/Understand-Anything](https://github.com/Lum1104/Understand-Anything) 則掉出 Top 5。[revfactory/harness](https://github.com/revfactory/harness) 從第 5 升到第 4。依完整 repo 名 `rg -F` 檢索結果，[EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin) 在既有保存報告中查無結果，本次依規則視為「未出現 / 新進榜候選」。
- 連續上榜：[harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) 自 2026-05-29 起連 8 份保存報告留在 Top 5，且自 2026-05-31 起連 6 份保存報告排第 1；[microsoft/markitdown](https://github.com/microsoft/markitdown) 自 2026-06-02 起連 4 份保存報告留在 Top 5；[chopratejas/headroom](https://github.com/chopratejas/headroom) 自 2026-06-03 起連 3 份保存報告留在 Top 5；[revfactory/harness](https://github.com/revfactory/harness) 則連 2 天留榜。
- 成長異常：[chopratejas/headroom](https://github.com/chopratejas/headroom) 從昨天的 6,245 增到今天 9,421，單日增加 3,176，是今天榜單裡最明顯的正向加速。[microsoft/markitdown](https://github.com/microsoft/markitdown) 從 17,108 增到 17,165，延續高位但增幅明顯放緩。[harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) 從 18,553 回落到 14,566，較像 GitHub weekly rolling window 的自然滑動；[EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin) 因歷史樣本中查無完整 repo 名，暫時無法做連續增長判讀。
- 比對不足說明：目前本機只保留 2026-05-15 到 2026-06-04 的已保存報告，且缺少 2026-05-19；因此 streak、首次出現與異常成長判斷皆以這批樣本為準。今日榜單本身已成功用 `web_fetch` 抓取，歷史比對未因個別 repo 查無資料而中止；查無完整 repo 名者均依規則視為未出現 / 新進榜候選。

## 備註
- 今日 Top 5 依 GitHub Trending 頁面順序整理，不是單純照本週 stars 絕對值排序；因此 [microsoft/markitdown](https://github.com/microsoft/markitdown) 的 weekly stars 雖高於前面部分專案，仍按頁面順序列為第 3。
