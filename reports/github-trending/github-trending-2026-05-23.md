# GitHub Trending 週榜觀察（2026-05-23）

來源：<https://github.com/trending?since=weekly>

## 1) 今日 Top 5
1. colbymchenry/codegraph — TypeScript — 10,749 stars this week
2. tinyhumansai/openhuman — Rust — 17,399 stars this week
3. Imbad0202/academic-research-skills — Python — 10,737 stars this week
4. ruvnet/RuView — Rust — 7,636 stars this week
5. rohitg00/agentmemory — TypeScript — 7,000 stars this week

## 2) 主題趨勢
- Agent infra 仍是主旋律，而且更集中在「直接提升開發效率」的能力：code knowledge graph、persistent memory、research workflow 同時卡在前五。
- Rust、TypeScript、Python 繼續主導週榜前段。Rust 吃 local-first / sensing，TypeScript 吃 agent tooling，Python 則繼續承接 workflow 與研究流程。
- Skills / methodology 相關題材沒有退潮。除了 Top 5 的 `Imbad0202/academic-research-skills`，榜內還有 `obra/superpowers`、`humanlayer/12-factor-agents`、`mattpocock/skills` 這類方法論專案，代表市場不只在追工具，也在追可複用工作法。
- 端側與實體世界題材還在場上。`ruvnet/RuView` 回到 Top 5，`supertone-inc/supertonic` 雖然今天掉出前五，但 WiFi sensing 與 on-device TTS 這類 edge 能力仍維持高曝光。

## 3) 值得追蹤專案
- colbymchenry/codegraph：從 2026-05-20 的 4,650 漲到今天 10,749，本週 stars 三天增加 6,099，而且今天回到頁面第 1，屬於這波 agent coding 基建裡最值得盯的加速樣本。
- tinyhumansai/openhuman：雖然今天不是頁面第 1，但仍維持 17,399 weekly stars，絕對熱度仍是全頁最強之一，personal AI / local-first 敘事還沒退。
- Imbad0202/academic-research-skills：連兩天卡在前段，研究工作流已經不只是小眾 skills 題材，而是開始進入主流 agent 生產力工具視野。
- ruvnet/RuView：今天重回 Top 5，證明注意力沒有完全被純軟體 agent 吃掉；WiFi sensing / spatial intelligence 這條 edge AI 支線仍有續航。
- obra/superpowers：雖然不在 Top 5，但今天榜內仍有 10,688 stars this week，說明「skills framework + 方法論」依然有穩定吸星能力。

## 4) 歷史比對（對照已保存報告：2026-05-15、2026-05-16、2026-05-17、2026-05-18、2026-05-20、2026-05-21、2026-05-22）
- 新進榜 / 進出變化：相較 2026-05-22 的 Top 5，今天是 `ruvnet/RuView` 回補前五、`supertone-inc/supertonic` 掉出前五；若看目前已保存樣本，今天 Top 5 沒有完全首次出現的 repo。
- 連續上榜：`rohitg00/agentmemory` 自 2026-05-15 起每天都出現在已保存樣本；`Imbad0202/academic-research-skills` 自 2026-05-17 起持續可見；`colbymchenry/codegraph` 與 `tinyhumansai/openhuman` 則自 2026-05-20 起連續站在前段。
- 成長異常：`colbymchenry/codegraph` 從 2026-05-20 的 4,650 拉到今天 10,749，三天增幅 6,099，成長斜率仍是目前樣本最陡；相對地，`tinyhumansai/openhuman`、`rohitg00/agentmemory`、`ruvnet/RuView` 的 weekly stars 較前兩天回落，比較像 GitHub weekly rolling window 的自然滑動。
- 敘事切換：昨天進前五的 `supertone-inc/supertonic` 今天退到榜內後段，今天前五重新偏向 agent coding infra + research workflow，表示 edge / creator tooling 雖然還有能見度，但本週主敘事仍由開發工作流工具主導。

## 備註
- 今日 Top 5 依 GitHub Trending 頁面順序整理，不是單純照本週 stars 絕對值排序。
- 歷史比對優先以完整 repo 名做 `rg -F` 檢索；對未查到完整 repo 名的情況，依規則視為「未出現 / 新進榜候選」，不視為錯誤。
