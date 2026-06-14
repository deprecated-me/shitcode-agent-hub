# GitHub Trending 週榜觀察（2026-06-13）

來源：<https://github.com/trending?since=weekly>

## 1) 今日 Top 5
1. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) — Python — 12,257 stars this week
2. [chopratejas/headroom](https://github.com/chopratejas/headroom) — Python — 10,184 stars this week
3. [phuryn/pm-skills](https://github.com/phuryn/pm-skills) — N/A — 4,839 stars this week
4. [apple/container](https://github.com/apple/container) — Swift — 7,781 stars this week
5. [openai/plugins](https://github.com/openai/plugins) — JavaScript — 1,435 stars this week

## 2) 主題趨勢
- 「agent 先研究、再執行」這條線仍然強，但現在更偏向 skill / marketplace / search aggregation 的組合。[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)、[phuryn/pm-skills](https://github.com/phuryn/pm-skills)、[Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) 分別對應跨站研究摘要、skills 市集、全網讀取搜尋，顯示熱門焦點已經從單一 agent infra 擴成完整外部資訊接入鏈。
- 「skills / plugins / workflow 配件」已經不是陪襯，而是首頁主體之一。[openai/plugins](https://github.com/openai/plugins)、[Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)、[phuryn/pm-skills](https://github.com/phuryn/pm-skills) 都在補代理擴充、風格控制或任務配件，代表開發者正在尋找比大型框架更快落地的輕量能力層。
- 榜單同時出現一條「本地執行環境 / 基礎設施」支線。[apple/container](https://github.com/apple/container) 與 [NVIDIA/cosmos](https://github.com/NVIDIA/cosmos) 都在頁面前段，說明除了 agent workflow 之外，本地容器執行與 Physical AI 工具鏈也開始吃到這波注意力。
- Python 仍是首頁主承載語言，但不再壟斷所有敘事。今天 Top 5 有兩席 Python，另外還有 Swift 與 JavaScript，而首頁前段也看得到 TypeScript 的 [lfnovo/open-notebook](https://github.com/lfnovo/open-notebook)，代表熱門專案正在從模型周邊工具延伸到 runtime 與產品化入口。

## 3) 值得追蹤專案
- [apple/container](https://github.com/apple/container)：昨天保存報告只記到頁面前段 4,081 stars this week，今天直接升到 Top 5 並來到 7,781，單日可比樣本增加 3,700；本地容器與 Apple silicon 開發環境這條線有明顯加速跡象。
- [phuryn/pm-skills](https://github.com/phuryn/pm-skills)：過去兩天已在趨勢段落出現，今天首次打進 Top 5；它把 100+ agent skills、commands、plugins 包成 PM 向技能市集，剛好踩中本週「workflow 配件化」的主旋律。
- [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)：雖然比昨天的 12,422 小回到 12,257，但仍穩坐第 1，且已連 5 份保存報告留在 Top 5；這條 research-first agent workflow 仍是本週最穩定的主線之一。
- [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach)：今天退到第 6，但仍有 5,364 stars this week，高於昨天 Top 5 時的 5,186；它雖暫時掉出前五，熱度本身沒有熄火，仍是「讓 agent 讀完整個網路」這條線的代表作。
- [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)：今天頁面前段有 8,651 stars this week，雖未進 Top 5，但和 [openai/plugins](https://github.com/openai/plugins)、[phuryn/pm-skills](https://github.com/phuryn/pm-skills) 一起把「少一點 slop、多一點可直接接進工作流的 skill layer」推成很清楚的副主題。

## 4) 歷史比對
- 新進榜 / 進出變化：相較 2026-06-12，今天 Top 5 新成員是 [phuryn/pm-skills](https://github.com/phuryn/pm-skills) 與 [apple/container](https://github.com/apple/container)；[lfnovo/open-notebook](https://github.com/lfnovo/open-notebook) 與 [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) 則掉出 Top 5。[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) 與 [chopratejas/headroom](https://github.com/chopratejas/headroom) 守住前 2 名，[openai/plugins](https://github.com/openai/plugins) 從第 4 退到第 5。
- 連續上榜：[chopratejas/headroom](https://github.com/chopratejas/headroom) 自 2026-06-03 起連 11 份保存報告留在 Top 5；[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) 連 5 天留榜；[openai/plugins](https://github.com/openai/plugins) 連 4 天留榜。[phuryn/pm-skills](https://github.com/phuryn/pm-skills) 用完整 repo 名 `rg -F` 可在 2026-06-11、2026-06-12 的保存報告中找到，但今天是首次進 Top 5；[apple/container](https://github.com/apple/container) 則是首次在本機保存報告裡進 Top 5。
- 成長異常：[apple/container](https://github.com/apple/container) 從昨天保存報告記錄的 4,081 增到今天 7,781，是目前可比樣本裡最明顯的正向跳升。[openai/plugins](https://github.com/openai/plugins) 從 1,424 微增到 1,435，屬高位持平；[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) 從 12,422 小回到 12,257、[chopratejas/headroom](https://github.com/chopratejas/headroom) 從 11,282 回到 10,184，較像 GitHub weekly rolling window 的自然滑動。[Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) 則從昨天的 5,186 增到今天第 6 的 5,364，屬於榜外續強。
- 比對不足說明：今日榜單先用 `web_fetch` 成功抓到主內容，但 [phuryn/pm-skills](https://github.com/phuryn/pm-skills) 的語言與星數欄位抽取不完整，後續用 browser 補齊。歷史比對僅以本機 `reports/github-trending/` 既有保存報告為準；其中 [phuryn/pm-skills](https://github.com/phuryn/pm-skills) 雖可用完整 repo 名 `rg -F` 查到前兩天曾被提及，但缺少前日精確 weekly stars，因此目前只能判讀為「首次進 Top 5」，無法做嚴格單日增速比較。

## 備註
- 今日 Top 5 依 GitHub Trending 頁面順序整理，不是單純照本週 stars 絕對值排序；因此 [apple/container](https://github.com/apple/container) 的 weekly stars 雖高於 [phuryn/pm-skills](https://github.com/phuryn/pm-skills)，仍按頁面順序列為第 4。
