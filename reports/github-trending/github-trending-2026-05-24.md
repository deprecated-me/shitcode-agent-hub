# GitHub Trending 週榜觀察（2026-05-24）

來源：<https://github.com/trending?since=weekly>

## 1) 今日 Top 5
1. colbymchenry/codegraph — TypeScript — 15,909 stars this week
2. tinyhumansai/openhuman — Rust — 16,288 stars this week
3. Imbad0202/academic-research-skills — Python — 11,691 stars this week
4. ruvnet/RuView — Rust — 6,741 stars this week
5. rohitg00/agentmemory — TypeScript — 6,734 stars this week

## 2) 主題趨勢
- Agent 開發基建仍是本週主軸，而且熱點更集中在「降低 agent 開發摩擦」：code knowledge graph、persistent memory、research workflow 連續卡在前段。
- Rust、TypeScript、Python 繼續主導前排。Rust 吃 personal AI 與 sensing，TypeScript 吃 agent tooling，Python 吃 research workflow 與 browser / video 這類能力層。
- Methods / skills 類題材沒有退潮。榜內同時看得到 `humanlayer/12-factor-agents`、`K-Dense-AI/scientific-agent-skills`、`obra/superpowers`，表示市場仍在追可複用工作法，不只追單一工具。
- Edge / multimodal 題材維持次主線。`ruvnet/RuView`、`supertone-inc/supertonic`、`HKUDS/ViMax` 都還在榜內，說明注意力沒有完全回到純文字 agent。

## 3) 值得追蹤專案
- colbymchenry/codegraph：從 2026-05-20 的 4,650 拉到今天 15,909，本週 stars 四天增加 11,259；這已不是單純上榜，而是 agent coding infra 裡最陡的一段加速。
- tinyhumansai/openhuman：雖然今天頁面順位退到第 2，但 16,288 weekly stars 仍是全頁最高檔之一，personal AI / local-first 敘事沒有熄火。
- Imbad0202/academic-research-skills：研究工作流連三天站穩 Top 3，代表「把 research 流程代理化」已從長尾技能題轉成主流 productivity 題材。
- CloakHQ/CloakBrowser：今天雖不在 Top 5，但仍有 6,991 weekly stars，而且自 2026-05-15 起在已保存樣本持續高能見度；browser stealth 仍是獨立賽道。
- HKUDS/ViMax：今天榜內有 2,790 weekly stars，且在目前已保存報告中查不到完整 repo 名，可視為新進榜候選；如果 agentic video generation 接下來持續留榜，代表多模態 agent 敘事正在擴張。

## 4) 歷史比對（對照已保存報告：2026-05-15、2026-05-16、2026-05-17、2026-05-18、2026-05-20、2026-05-21、2026-05-22、2026-05-23）
- 新進榜 / 進出變化：相較 2026-05-23，今天 Top 5 成員完全相同，沒有新的 Top 5 repo；變化是 `colbymchenry/codegraph` 重新回到頁面第 1，`tinyhumansai/openhuman` 退到第 2。若擴到值得追蹤名單，`HKUDS/ViMax` 在已保存報告中查不到完整 repo 名，可視為「未出現 / 新進榜候選」。
- 連續上榜：`rohitg00/agentmemory` 自 2026-05-15 起每天都出現在已保存樣本；`Imbad0202/academic-research-skills` 自 2026-05-17 起持續可見；`colbymchenry/codegraph` 與 `tinyhumansai/openhuman` 自 2026-05-20 起連續站在前段。
- 成長異常：`colbymchenry/codegraph` 從 2026-05-20 的 4,650 拉到今天 15,909，四天增幅 11,259，是目前樣本最陡成長；`Imbad0202/academic-research-skills` 也從 2026-05-21 的 8,737 增到今天 11,691。相對地，`tinyhumansai/openhuman`、`ruvnet/RuView`、`rohitg00/agentmemory` 的 weekly stars 低於前幾天峰值，較像 GitHub weekly rolling window 的自然滑動。
- 敘事切換：昨天還在觀察的 `supertone-inc/supertonic` 今天留在榜內後段，前五重新被 agent coding infra + research workflow 吃滿；但 `RuView` 持續守在前排，表示 edge sensing 還沒退場。

## 備註
- 今日 Top 5 依 GitHub Trending 頁面順序整理，不是單純照本週 stars 絕對值排序。
- 歷史比對優先以完整 repo 名做 `rg -F` 檢索；對 `HKUDS/ViMax` 這類查無完整 repo 名的結果，本次依規則視為未出現 / 新進榜候選，而非錯誤。
