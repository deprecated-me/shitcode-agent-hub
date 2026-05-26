# GitHub Trending 週榜觀察（2026-05-26）

來源：<https://github.com/trending?since=weekly>

## 1) 今日 Top 5
1. colbymchenry/codegraph — TypeScript — 20,208 stars this week
2. tinyhumansai/openhuman — Rust — 11,906 stars this week
3. Lum1104/Understand-Anything — TypeScript — 14,750 stars this week
4. Imbad0202/academic-research-skills — Python — 10,678 stars this week
5. rohitg00/ai-engineering-from-scratch — Python — 10,035 stars this week

## 2) 主題趨勢
- 「agent coding 的知識壓縮層」明顯變成主旋律。`colbymchenry/codegraph` 與 `Lum1104/Understand-Anything` 都在做 code knowledge graph / 可探索知識圖，而且直接對準 Claude Code、Codex、Cursor 這類 agent workflow。
- 市場注意力從單點 infra 擴到「可直接拿來學、拿來做」的完整工作流。`Imbad0202/academic-research-skills` 與 `rohitg00/ai-engineering-from-scratch` 同時留在前五，代表 research workflow 與 AI engineering 教材型專案仍在放量。
- 語言分布回到 TypeScript + Python + Rust 的核心三角。TypeScript 吃 agent tooling / graph，Python 吃 research / 教學 / browser 類工作流，Rust 繼續承接 local-first personal AI。
- Edge / stealth / voice 題材仍在榜內，但本週頁面最前段已經被 agent productivity 敘事吃滿。`ruvnet/RuView`、`CloakHQ/CloakBrowser`、`supertone-inc/supertonic` 還有曝光，不過不再主導首頁前排。

## 3) 值得追蹤專案
- colbymchenry/codegraph：從 2026-05-20 的 4,650 拉到今天 20,208，六天增加 15,558；這仍是已保存樣本裡最陡的加速曲線。
- Lum1104/Understand-Anything：今天直接衝進第 3，且在已保存報告中查不到完整 repo 名，可視為「未出現 / 新進榜候選」；題材與 `codegraph` 同樣鎖定 code knowledge graph，但更強調 interactive exploration。
- rohitg00/ai-engineering-from-scratch：連兩天留在 Top 5，代表「從零學會把 AI 工程做出來」不是一次性流量，而是正在被追捧的主題。
- tinyhumansai/openhuman：雖然 weekly stars 比前幾天峰值明顯回落，但仍穩居前二，personal AI / local-first 敘事還沒有退。
- can1357/oh-my-pi：今天不在 Top 5，但以 2,584 weekly stars 留在榜內，而且在已保存報告中查不到完整 repo 名；對 terminal agent / tool harness 賽道值得當作新進榜候選持續追。

## 4) 歷史比對（對照已保存報告：2026-05-15、2026-05-16、2026-05-17、2026-05-18、2026-05-20、2026-05-21、2026-05-22、2026-05-23、2026-05-24、2026-05-25）
- 新進榜 / 進出變化：相較 2026-05-25，今天 Top 5 的明顯新成員是 `Lum1104/Understand-Anything`；`ruvnet/RuView` 則掉出 Top 5。依完整 repo 名 `rg -F` 檢索結果，`Lum1104/Understand-Anything` 在已保存報告中查不到，可視為「未出現 / 新進榜候選」。
- 連續上榜：`colbymchenry/codegraph` 與 `tinyhumansai/openhuman` 自 2026-05-20 起持續站在前段；`Imbad0202/academic-research-skills` 自 2026-05-17 起持續可見；`rohitg00/ai-engineering-from-scratch` 連兩天留在 Top 5。
- 成長異常：`colbymchenry/codegraph` 從 2026-05-20 的 4,650 衝到今天 20,208，六天增幅 15,558，仍是樣本內最兇的成長；相對地，`tinyhumansai/openhuman` 從 2026-05-21 的 19,177 滑到今天 11,906，較像 GitHub weekly rolling window 的自然滑動，不一定代表熱度反轉。
- 比對不足說明：目前本機只保留 2026-05-15 到 2026-05-25 的已保存報告，且缺少 2026-05-19；因此對 `Lum1104/Understand-Anything`、`can1357/oh-my-pi` 這類查無完整 repo 名的專案，本次依規則視為未出現 / 新進榜候選，而非錯誤。

## 備註
- 今日 Top 5 依 GitHub Trending 頁面順序整理，不是單純照本週 stars 絕對值排序。
- 歷史比對優先以完整 repo 名做 `rg -F` 檢索；查無結果者依規則視為未出現 / 新進榜候選，不中止整體報告流程。
