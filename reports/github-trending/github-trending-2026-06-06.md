# GitHub Trending 週榜觀察（2026-06-06）

來源：<https://github.com/trending?since=weekly>

## 1) 今日 Top 5
1. [chopratejas/headroom](https://github.com/chopratejas/headroom) — Python — 11,993 stars this week
2. [microsoft/markitdown](https://github.com/microsoft/markitdown) — Python — 16,376 stars this week
3. [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) — Python — 11,388 stars this week
4. [revfactory/harness](https://github.com/revfactory/harness) — HTML — 2,030 stars this week
5. [run-llama/liteparse](https://github.com/run-llama/liteparse) — Rust — 2,380 stars this week

## 2) 主題趨勢
- 「agent workflow 的工具層」今天更集中在降本增效。[chopratejas/headroom](https://github.com/chopratejas/headroom)、[microsoft/markitdown](https://github.com/microsoft/markitdown)、[run-llama/liteparse](https://github.com/run-llama/liteparse) 分別對應 context 壓縮、文件轉 Markdown、文件解析，熱門焦點明顯朝能直接塞進 AI 工作流的實用組件靠攏。
- Python 仍是本週首頁主承載語言。Top 5 裡三個 Python repo 分別落在影片生成、token 成本控制、文件處理三個不同面向，代表需求不是集中在單點爆款，而是整條 AI 工具鏈同時升溫。
- 「agent engineering」依然壓過純模型題材。[revfactory/harness](https://github.com/revfactory/harness)、[EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin)、[supermemoryai/supermemory](https://github.com/supermemoryai/supermemory)、[affaan-m/ECC](https://github.com/affaan-m/ECC) 都在做 agent team、plugin、memory、execution system，說明開發者現在更在意把 agent 接進真實工作流。
- 多模態 / 語音開源能力也還有存在感。[OpenBMB/VoxCPM](https://github.com/OpenBMB/VoxCPM) 與 [Open-LLM-VTuber/Open-LLM-VTuber](https://github.com/Open-LLM-VTuber/Open-LLM-VTuber) 都留在首頁，表示除了 agent tooling，voice 與互動層仍持續吸引關注。

## 3) 值得追蹤專案
- [chopratejas/headroom](https://github.com/chopratejas/headroom)：昨天 9,421，今天 11,993，單日增加 2,572，且頁面排序從第 2 升到第 1；這條「先壓縮工具輸出再餵模型」的成本優化路線，已從新秀變成首頁核心敘事。
- [run-llama/liteparse](https://github.com/run-llama/liteparse)：今天直接打進 Top 5，用完整 repo 名 `rg -F` 在既有保存報告中查無結果，依規則視為未出現 / 新進榜候選；如果和 [microsoft/markitdown](https://github.com/microsoft/markitdown) 一起留榜，代表文件 ingestion / parsing 會成為更明確的副主題。
- [supermemoryai/supermemory](https://github.com/supermemoryai/supermemory)：今天榜內有 2,944 stars this week，和 [chopratejas/headroom](https://github.com/chopratejas/headroom)、[affaan-m/ECC](https://github.com/affaan-m/ECC) 一起把「agent memory / context engineering」推成更完整的題材，值得觀察是否會往前排。
- [OpenBMB/VoxCPM](https://github.com/OpenBMB/VoxCPM)：今天榜內有 4,398 stars this week，用完整 repo 名 `rg -F` 在既有保存報告中查無結果，可視為未出現 / 新進榜候選；Tokenizer-free TTS 與 voice cloning 如果持續留榜，可能會是下一波多模態開源主線。
- [revfactory/harness](https://github.com/revfactory/harness)：昨天 2,159，今天 2,030，weekly stars 小幅回落但已連三份保存報告留在 Top 5；「自動設計 domain-specific agent teams / skills」這條 agent orchestration 題材還沒有退潮。

## 4) 歷史比對
- 新進榜 / 進出變化：相較 2026-06-05，今天 Top 5 新成員是 [run-llama/liteparse](https://github.com/run-llama/liteparse)；[EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin) 則掉出 Top 5。[chopratejas/headroom](https://github.com/chopratejas/headroom) 從第 2 升到第 1，[microsoft/markitdown](https://github.com/microsoft/markitdown) 從第 3 升到第 2，[harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) 從第 1 退到第 3。依完整 repo 名 `rg -F` 檢索結果，[run-llama/liteparse](https://github.com/run-llama/liteparse) 在既有保存報告中查無結果，本次依規則視為「未出現 / 新進榜候選」。
- 連續上榜：[harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) 自 2026-05-29 起連 9 份保存報告留在 Top 5，但自 2026-05-31 起連 6 份保存報告排第 1 的紀錄今天中斷；[microsoft/markitdown](https://github.com/microsoft/markitdown) 自 2026-06-02 起連 5 份保存報告留在 Top 5；[chopratejas/headroom](https://github.com/chopratejas/headroom) 自 2026-06-03 起連 4 份保存報告留在 Top 5；[revfactory/harness](https://github.com/revfactory/harness) 則連 3 天留榜。
- 成長異常：[chopratejas/headroom](https://github.com/chopratejas/headroom) 從昨天的 9,421 增到今天 11,993，單日增加 2,572，是今天榜單裡最明顯的正向加速。[microsoft/markitdown](https://github.com/microsoft/markitdown) 從 17,165 回落到 16,376、[harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) 從 14,566 回落到 11,388，較像 GitHub weekly rolling window 的自然滑動；[revfactory/harness](https://github.com/revfactory/harness) 從 2,159 回到 2,030，仍算高位橫盤。[run-llama/liteparse](https://github.com/run-llama/liteparse) 因歷史樣本中查無完整 repo 名，暫時無法做連續增長判讀。
- 比對不足說明：目前本機只保留 2026-05-15 到 2026-06-05 的已保存報告，且缺少 2026-05-19；因此 streak、首次出現與異常成長判斷皆以這批樣本為準。今日榜單已成功用 `web_fetch` 抓取，歷史比對未因個別 repo 查無資料而中止；查無完整 repo 名者均依規則視為未出現 / 新進榜候選。

## 備註
- 今日 Top 5 依 GitHub Trending 頁面順序整理，不是單純照本週 stars 絕對值排序；因此 [microsoft/markitdown](https://github.com/microsoft/markitdown) 與 [run-llama/liteparse](https://github.com/run-llama/liteparse) 的 weekly stars 雖高於前面部分專案，仍按頁面順序列出。
