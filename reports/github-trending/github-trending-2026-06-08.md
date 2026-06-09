# GitHub Trending 週榜觀察（2026-06-08）

來源：<https://github.com/trending?since=weekly>

## 1) 今日 Top 5
1. [chopratejas/headroom](https://github.com/chopratejas/headroom) — Python — 14,272 stars this week
2. [microsoft/markitdown](https://github.com/microsoft/markitdown) — Python — 13,359 stars this week
3. [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) — Python — 7,992 stars this week
4. [supermemoryai/supermemory](https://github.com/supermemoryai/supermemory) — TypeScript — 2,924 stars this week
5. [affaan-m/ECC](https://github.com/affaan-m/ECC) — JavaScript — 10,207 stars this week

## 2) 主題趨勢
- 「AI 工作流基建」仍是首頁主旋律，而且更集中在可直接接進 agent pipeline 的實用層。[chopratejas/headroom](https://github.com/chopratejas/headroom)、[microsoft/markitdown](https://github.com/microsoft/markitdown)、[supermemoryai/supermemory](https://github.com/supermemoryai/supermemory)、[affaan-m/ECC](https://github.com/affaan-m/ECC) 分別卡在 context 壓縮、文件轉 Markdown、memory API、agent harness，焦點明顯是工程效率，不是新模型本身。
- Python 仍然是本週首頁最強承載語言。Top 5 裡三席是 Python，而且榜內中段還有 [Open-LLM-VTuber/Open-LLM-VTuber](https://github.com/Open-LLM-VTuber/Open-LLM-VTuber)、[Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach)、[NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) 等專案，覆蓋內容生成、語音互動、搜尋整合與 agent 框架。
- Agent engineering 題材沒有退潮，只是從 orchestration 轉向更完整的 execution system。昨天還在 Top 5 的 [revfactory/harness](https://github.com/revfactory/harness) 今天退到榜外，但 [affaan-m/ECC](https://github.com/affaan-m/ECC)、[EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin)、[can1357/oh-my-pi](https://github.com/can1357/oh-my-pi) 仍把 plugin、tool harness、memory、security 這條線維持在首頁。
- 產品化互動層也有穩定存在感。[Open-LLM-VTuber/Open-LLM-VTuber](https://github.com/Open-LLM-VTuber/Open-LLM-VTuber)、[nesquena/hermes-webui](https://github.com/nesquena/hermes-webui)、[lfnovo/open-notebook](https://github.com/lfnovo/open-notebook) 分別對應語音互動、agent WebUI、Notebook LM 類知識介面，代表開發者不只在堆 infra，也在補「能被一般人直接使用」的前端入口。

## 3) 值得追蹤專案
- [chopratejas/headroom](https://github.com/chopratejas/headroom)：昨天 13,308，今天 14,272，單日增加 964，且自 2026-06-03 起連 6 份保存報告留在 Top 5；這條「先壓縮 tool outputs / logs / chunks 再送模型」的降本路線，已從新秀變成首頁常駐主線。
- [affaan-m/ECC](https://github.com/affaan-m/ECC)：今天以 10,207 打進 Top 5；它在 2026-06-04 的保存報告就曾被記到有 10,008 stars this week，之後雖未進 Top 5 但持續出現在趨勢段落，表示 agent harness / memory / security 的系統化工程題材不是單日噪音。
- [Open-LLM-VTuber/Open-LLM-VTuber](https://github.com/Open-LLM-VTuber/Open-LLM-VTuber)：今天榜內有 2,388 stars this week，較昨天保存報告提到的 2,273 再往上走；它把本地 LLM、語音打斷與 Live2D 串成完整互動體驗，是少數產品感比較完整的互動層專案。
- [lfnovo/open-notebook](https://github.com/lfnovo/open-notebook)：今天榜內有 2,993 stars this week，用完整 repo 名 `rg -F` 在既有保存報告中查無結果，依規則視為未出現 / 新進榜候選；如果接下來幾天仍留榜，表示開源 Notebook LM 類知識工作台會成為更明確的副主題。
- [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)：昨天保存報告提到 11,355，今天來到 11,427，雖未進 Top 5 但仍是首頁高位；如果它能和 [nesquena/hermes-webui](https://github.com/nesquena/hermes-webui) 一起持續留榜，代表 agent framework + 可用前端這條組合正在擴散。

## 4) 歷史比對
- 新進榜 / 進出變化：相較 2026-06-07，今天 Top 5 新成員是 [affaan-m/ECC](https://github.com/affaan-m/ECC)；[revfactory/harness](https://github.com/revfactory/harness) 則掉出 Top 5。[supermemoryai/supermemory](https://github.com/supermemoryai/supermemory) 從第 5 升到第 4；前 3 名仍是 [chopratejas/headroom](https://github.com/chopratejas/headroom)、[microsoft/markitdown](https://github.com/microsoft/markitdown)、[harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)。
- 連續上榜：[harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) 自 2026-05-29 起連 11 份保存報告留在 Top 5；[microsoft/markitdown](https://github.com/microsoft/markitdown) 自 2026-06-02 起連 7 份保存報告留在 Top 5；[chopratejas/headroom](https://github.com/chopratejas/headroom) 自 2026-06-03 起連 6 份保存報告留在 Top 5；[supermemoryai/supermemory](https://github.com/supermemoryai/supermemory) 則連 2 天留榜。[affaan-m/ECC](https://github.com/affaan-m/ECC) 在既有保存報告中不是首次出現，但今天是首次進 Top 5。
- 成長異常：[chopratejas/headroom](https://github.com/chopratejas/headroom) 從昨天的 13,308 增到今天 14,272，單日增加 964，仍是今天 Top 5 裡最明顯的正向加速。[microsoft/markitdown](https://github.com/microsoft/markitdown) 從 15,015 回到 13,359、[harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) 從 9,174 回到 7,992，較像 GitHub weekly rolling window 的自然滑動；[supermemoryai/supermemory](https://github.com/supermemoryai/supermemory) 從 2,992 微回落到 2,924，仍算高位橫盤。[affaan-m/ECC](https://github.com/affaan-m/ECC) 因本機歷史樣本只有 2026-06-04 留下明確 weekly stars（10,008），中間幾天缺少逐日精確數字，暫時無法做嚴格的單日異常增長判讀。
- 比對不足說明：目前本機只保留 2026-05-15 到 2026-06-07 的已保存報告，且缺少 2026-05-19；因此 streak、首次出現與成長異常判斷皆以這批樣本為準。今日榜單已成功用 `web_fetch` 抓取；若某些 repo 用完整 repo 名 `rg -F` 查無結果，均依規則視為未出現 / 新進榜候選，而非錯誤。
