# GitHub Trending 週榜觀察（2026-06-12）

來源：<https://github.com/trending?since=weekly>

## 1) 今日 Top 5
1. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) — Python — 12,422 stars this week
2. [chopratejas/headroom](https://github.com/chopratejas/headroom) — Python — 11,282 stars this week
3. [lfnovo/open-notebook](https://github.com/lfnovo/open-notebook) — TypeScript — 4,796 stars this week
4. [openai/plugins](https://github.com/openai/plugins) — JavaScript — 1,424 stars this week
5. [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) — Python — 5,186 stars this week

## 2) 主題趨勢
- 「agent 先研究、再執行」仍是本週首頁主線。[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)、[Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach)、[lfnovo/open-notebook](https://github.com/lfnovo/open-notebook) 分別對應跨社群研究、全網讀取搜尋與 Notebook LM 類知識工作台，熱門點已經從單一 agent infra 擴成完整資訊攝取鏈。
- 「skills / plugins / workflow 配件」沒有退場，反而更像次主線。[openai/plugins](https://github.com/openai/plugins)、[Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)、[phuryn/pm-skills](https://github.com/phuryn/pm-skills) 都在補代理擴充、風格控制或任務配件，說明開發者還在找可快速掛進現有流程的輕量能力層。
- Python 仍是週榜主承載語言，但產品化入口持續抬頭。今日 Top 5 有 3 席是 Python，不過 [lfnovo/open-notebook](https://github.com/lfnovo/open-notebook) 與 [CopilotKit/CopilotKit](https://github.com/CopilotKit/CopilotKit) 這類 TypeScript 介面專案仍維持高位，表示「把 AI 做成可直接操作產品」的需求沒有降溫。
- 榜內也出現較偏基礎設施與實體世界的旁支訊號。[apple/container](https://github.com/apple/container) 與 [NVIDIA/cosmos](https://github.com/NVIDIA/cosmos) 同時在頁面前段，代表除了 agent workflow 之外，開發者也在關注本地容器執行環境與 Physical AI 工具鏈。

## 3) 值得追蹤專案
- [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)：昨天 11,732，今天 12,422，單日增加 690，且已連 4 天留在 Top 5；「research-first agent workflow」已從新進榜候選變成穩定主線。
- [lfnovo/open-notebook](https://github.com/lfnovo/open-notebook)：昨天 4,648，今天 4,796，且已連 2 天留在 Top 5；它從 2026-06-08 保存報告的 2,993 一路放大到現在，開源 Notebook LM / knowledge workspace 類產品還在升溫。
- [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach)：昨天 5,021，今天 5,186，已連 4 天留在 Top 5；「低成本讓 agent 讀完整個網路」這條敘事雖增速放緩，但持續性很強。
- [openai/plugins](https://github.com/openai/plugins)：昨天 1,371，今天 1,424，已連 3 天留在 Top 5；這不像一次性舊 repo 回魂，更像 plugin interface 題材被新一輪 agent 工具鏈重新帶起。
- [apple/container](https://github.com/apple/container)：今天頁面前段有 4,081 stars this week，用完整 repo 名 `rg -F` 在既有保存報告中查無結果，依規則視為未出現 / 新進榜候選；若它接下來幾天仍留在前段，代表本地容器與 Apple silicon 開發環境會成為 AI 開發者的新副主題。

## 4) 歷史比對
- 新進榜 / 進出變化：相較 2026-06-11，今天 Top 5 名單完全相同，沒有新進榜或掉榜專案；排序也維持不變，代表週榜前段已經從前幾天的快速換血，進入短暫穩定期。
- 連續上榜：[chopratejas/headroom](https://github.com/chopratejas/headroom) 自 2026-06-03 起連 10 份保存報告留在 Top 5；[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) 與 [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) 都連 4 天留在 Top 5；[openai/plugins](https://github.com/openai/plugins) 連 3 天留榜；[lfnovo/open-notebook](https://github.com/lfnovo/open-notebook) 連 2 天留榜，且用完整 repo 名 `rg -F` 可在 2026-06-08、2026-06-10 的保存報告中找到更早出現紀錄。
- 成長異常：[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) 從 11,732 增到 12,422，仍是今日 Top 5 裡最明顯的正向增長；[Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) 與 [lfnovo/open-notebook](https://github.com/lfnovo/open-notebook) 分別從 5,021 增到 5,186、4,648 增到 4,796，屬穩定續強。[chopratejas/headroom](https://github.com/chopratejas/headroom) 從 13,062 回到 11,282，較像 GitHub weekly rolling window 的自然滑動，而不是熱度立即反轉。
- 比對不足說明：今日榜單先用 `web_fetch` 成功抓到主內容，未需要退回 browser。歷史比對僅以本機 `reports/github-trending/` 既有保存報告為準；若某些 repo 用完整 repo 名 `rg -F` 查無結果，均依規則視為未出現 / 新進榜候選，而非錯誤，因此像 [apple/container](https://github.com/apple/container) 目前只能做候選判讀，無法做嚴格連續增長計算。

## 備註
- 今日 Top 5 依 GitHub Trending 頁面順序整理，不是單純照本週 stars 絕對值排序；因此 [openai/plugins](https://github.com/openai/plugins) 的 weekly stars 雖低於榜內其他專案，仍按頁面順序列為第 4。
