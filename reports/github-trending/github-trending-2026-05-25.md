# GitHub Trending 週榜觀察（2026-05-25）

來源：<https://github.com/trending?since=weekly>

## 1) 今日 Top 5
1. colbymchenry/codegraph — TypeScript — 18,136 stars this week
2. tinyhumansai/openhuman — Rust — 15,194 stars this week
3. Imbad0202/academic-research-skills — Python — 11,401 stars this week
4. rohitg00/ai-engineering-from-scratch — Python — 6,944 stars this week
5. ruvnet/RuView — Rust — 6,461 stars this week

## 2) 主題趨勢
- Agent 開發基建依然是榜單主線，而且比前幾天更集中在「讓 AI coding/agent workflow 可直接落地」：code knowledge graph、persistent memory、research workflow、從零搭建 AI engineering 教材同時衝高。
- Python、TypeScript、Rust 三語言繼續吃掉前排。Python 吃 research / browser / 教學型 workflow，TypeScript 吃 agent tooling，Rust 吃 local-first personal AI 與 sensing。
- 「skills / methodology / education」類題材持續升溫，不只 `Imbad0202/academic-research-skills`，榜內也能看到 `K-Dense-AI/scientific-agent-skills`、`obra/superpowers`、`datawhalechina/easy-vibe`，表示市場不只追工具，還在追可複用方法與學習路徑。
- Edge / multimodal 題材還在榜內，但聲量已被 agent productivity 敘事壓過。`ruvnet/RuView`、`supertone-inc/supertonic` 仍有能見度，不過頁面前段明顯回到 coding agent 與 workflow。

## 3) 值得追蹤專案
- colbymchenry/codegraph：從 2026-05-20 的 4,650 拉到今天 18,136，五天增加 13,486；這是目前已保存樣本裡最陡的加速曲線。
- rohitg00/ai-engineering-from-scratch：今天直接打進 Top 5，但在既有保存報告中查不到完整 repo 名，可視為新進榜候選；「教你把 AI 工程從零做起來」這類教材型專案開始吃到主流流量。
- tinyhumansai/openhuman：weekly stars 從前幾天高點回落到 15,194，但仍穩居前二，personal AI / local-first 敘事還沒退。
- ruvnet/RuView：雖然 weekly stars 比 2026-05-20 的 8,076 低，但 5/18 就已在保存樣本出現，且這幾天能反覆回到前排，代表 edge sensing 不是一次性噪音。
- CloakHQ/CloakBrowser：今天不在 Top 5，但在已保存報告裡自 2026-05-15 起持續高能見度，browser stealth 仍是值得獨立追蹤的支線。

## 4) 歷史比對（對照已保存報告：2026-05-15、2026-05-16、2026-05-17、2026-05-18、2026-05-20、2026-05-21、2026-05-22、2026-05-23、2026-05-24）
- 新進榜 / 進出變化：相較 2026-05-24，今天 Top 5 的明顯新成員是 `rohitg00/ai-engineering-from-scratch`；`rohitg00/agentmemory` 則掉出 Top 5。依完整 repo 名 `rg -F` 檢索結果，`rohitg00/ai-engineering-from-scratch` 在已保存報告中查不到，可視為「未出現 / 新進榜候選」。
- 連續上榜：`colbymchenry/codegraph` 與 `tinyhumansai/openhuman` 自 2026-05-20 起持續站在前段；`Imbad0202/academic-research-skills` 自 2026-05-17 起持續可見；`ruvnet/RuView` 至少自 2026-05-18 起就在已保存樣本中反覆出現。
- 成長異常：`colbymchenry/codegraph` 從 2026-05-20 的 4,650 衝到今天 18,136，五天增幅 13,486，仍是樣本內最兇的成長；相對地，`tinyhumansai/openhuman`、`ruvnet/RuView` 的 weekly stars 低於前幾天峰值，較像 GitHub weekly rolling window 的自然滑動。
- 敘事切換：昨天 Top 5 還有 `rohitg00/agentmemory`，今天換成 `rohitg00/ai-engineering-from-scratch`，表示市場注意力從「agent infra 的單點能力層」進一步擴到「完整 AI engineering 學習與落地流程」。

## 備註
- 今日 Top 5 依 GitHub Trending 頁面順序整理，不是單純照本週 stars 絕對值排序。
- 歷史比對優先以完整 repo 名做 `rg -F` 檢索；對 `rohitg00/ai-engineering-from-scratch` 這類查無完整 repo 名的結果，本次依規則視為未出現 / 新進榜候選，而非錯誤。
