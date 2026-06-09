# GitHub Trending 週榜觀察（2026-05-27）

來源：<https://github.com/trending?since=weekly>

## 1) 今日 Top 5
1. colbymchenry/codegraph — TypeScript — 21,211 stars this week
2. Lum1104/Understand-Anything — TypeScript — 19,191 stars this week
3. rohitg00/ai-engineering-from-scratch — Python — 11,840 stars this week
4. tinyhumansai/openhuman — Rust — 8,542 stars this week
5. Imbad0202/academic-research-skills — Python — 8,422 stars this week

## 2) 主題趨勢
- 「code knowledge graph / code understanding layer」已經不是單點題材，而是本週首頁最強主線。`colbymchenry/codegraph` 與 `Lum1104/Understand-Anything` 同時包下前二，且都直接面向 Claude Code、Codex、Cursor 這類 agent coding workflow。
- 教學型與 workflow 型專案持續吃流量，而且排序還在往前。`rohitg00/ai-engineering-from-scratch` 升到第 3，`Imbad0202/academic-research-skills` 雖然本週 stars 回落，仍留在 Top 5，表示市場不只追工具，也在追「怎麼學、怎麼做」。
- 語言分布仍是 TypeScript、Python、Rust 三角。TypeScript 吃 agent tooling / graph，Python 吃教學與 research workflow，Rust 維持 personal AI / local-first 敘事。
- 週榜前段越來越偏 agent-native 生產力層；純模型展示或單一能力型 repo 仍在榜內，但頁面前排已被「讓 AI 開發更好用」的題材占滿。

## 3) 值得追蹤專案
- colbymchenry/codegraph：從 2026-05-20 的 4,650 拉到今天 21,211，七天增加 16,561，仍是樣本內最穩定且最陡的成長曲線。
- Lum1104/Understand-Anything：昨天以 14,750 首次進入已保存樣本，今天直接升到第 2，一天增加 4,441；這是目前前段榜單裡最值得注意的加速點。
- rohitg00/ai-engineering-from-scratch：連三天留在 Top 5，且今天升到第 3；AI engineering 教材型專案看起來不是短期噪音。
- tinyhumansai/openhuman：weekly stars 從高點回落，但自 2026-05-20 起持續在前段，personal AI / local-first 路線還沒有退場。
- Imbad0202/academic-research-skills：雖然從 2026-05-24 的 11,691 回落到今天 8,422，仍自 2026-05-17 起維持可見度，顯示 research workflow 仍有穩定需求。

## 4) 歷史比對（對照已保存報告：2026-05-15、2026-05-16、2026-05-17、2026-05-18、2026-05-20、2026-05-21、2026-05-22、2026-05-23、2026-05-24、2026-05-25、2026-05-26）
- 新進榜 / 進出變化：相較 2026-05-26，今天 Top 5 成員完全相同，沒有新的 Top 5 repo；變化是 `Lum1104/Understand-Anything` 從第 3 升到第 2、`rohitg00/ai-engineering-from-scratch` 從第 5 升到第 3，`tinyhumansai/openhuman`、`Imbad0202/academic-research-skills` 各下滑兩名。
- 連續上榜：`colbymchenry/codegraph` 與 `tinyhumansai/openhuman` 自 2026-05-20 起持續站在前段；`Imbad0202/academic-research-skills` 自 2026-05-17 起持續可見；`rohitg00/ai-engineering-from-scratch` 連三天留在 Top 5；`Lum1104/Understand-Anything` 連兩天留在 Top 5。
- 成長異常：`Lum1104/Understand-Anything` 從昨天的 14,750 拉到今天 19,191，單日增加 4,441，是今日最明顯的加速；`colbymchenry/codegraph` 也從昨天的 20,208 增到 21,211，並把 2026-05-20 以來的累積增幅推到 16,561。相對地，`tinyhumansai/openhuman` 與 `Imbad0202/academic-research-skills` 的 weekly stars 明顯下滑，較像 GitHub weekly rolling window 的自然滑動。
- 比對不足說明：目前本機只保留 2026-05-15 到 2026-05-26 的已保存報告，且缺少 2026-05-19；因此本次 streak 與「首次出現」判斷以這批樣本為準，不外推到更早日期。

## 備註
- 今日 Top 5 依 GitHub Trending 頁面順序整理，不是單純照本週 stars 絕對值排序。
- 歷史比對優先以完整 repo 名做 `rg -F` 檢索；查無更早樣本或缺漏日期時，僅在報告中如實標示比對範圍，不把它當成任務失敗。
