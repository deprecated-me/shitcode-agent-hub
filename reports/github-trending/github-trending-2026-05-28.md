# GitHub Trending 週榜觀察（2026-05-28）

來源：<https://github.com/trending?since=weekly>

## 1) 今日 Top 5
1. colbymchenry/codegraph — TypeScript — 21,424 stars this week
2. Lum1104/Understand-Anything — TypeScript — 23,401 stars this week
3. rohitg00/ai-engineering-from-scratch — Python — 12,787 stars this week
4. ruvnet/RuView — Rust — 5,434 stars this week
5. anthropics/knowledge-work-plugins — Python — 4,718 stars this week

## 2) 主題趨勢
- 「code knowledge graph / code understanding」仍是本週最強主線。`colbymchenry/codegraph` 與 `Lum1104/Understand-Anything` 連三天包下前二，而且都直接對準 Claude Code、Codex、Cursor 這類 agent coding workflow。
- 教學型與工作流型專案持續在前段吃流量。`rohitg00/ai-engineering-from-scratch` 穩住第 3，表示市場不只追新工具，也在追「怎麼學、怎麼落地」。
- Python 與 TypeScript 持續吃掉大部分 agent / workflow 敘事，但 Rust 題材沒有消失。`ruvnet/RuView` 回到 Top 5，代表 edge sensing / ambient intelligence 這條線還有續航。
- 榜單前排開始從「單一 skill / methodology」擴到「可直接放進知識工作流程的插件與自動化」。`anthropics/knowledge-work-plugins` 今天首次進入已保存樣本的 Top 5，說明 knowledge worker tooling 開始往前排擠。

## 3) 值得追蹤專案
- colbymchenry/codegraph：從 2026-05-20 的 4,650 拉到今天 21,424，八天增加 16,774；雖然今日單日增幅只比昨天多 213，但整段曲線仍是目前樣本裡最穩定的主升段。
- Lum1104/Understand-Anything：昨天 19,191，今天到 23,401，單日再增 4,210；這是今日前段榜單裡最明顯的加速點，而且已連三天站在前二。
- rohitg00/ai-engineering-from-scratch：自 2026-05-25 進入已保存樣本後，從 6,944 漲到今天 12,787，三天增加 5,843；AI engineering 教材型 repo 看起來不是短期噪音。
- anthropics/knowledge-work-plugins：完整 repo 名在既有保存報告中查不到，可依規則視為「未出現 / 新進榜候選」；題材直接貼近知識工作者插件生態，值得觀察是否會延續到週榜尾聲。
- ruvnet/RuView：雖然 weekly stars 低於 2026-05-20 到 2026-05-25 的高點，但它至少自 2026-05-18 起就在已保存樣本中反覆出現，今天又回到 Top 5，代表 edge AI 並沒有完全退出首頁視野。

## 4) 歷史比對（對照已保存報告：2026-05-15、2026-05-16、2026-05-17、2026-05-18、2026-05-20、2026-05-21、2026-05-22、2026-05-23、2026-05-24、2026-05-25、2026-05-26、2026-05-27）
- 新進榜 / 進出變化：相較 2026-05-27，今天 Top 5 新成員是 `ruvnet/RuView` 與 `anthropics/knowledge-work-plugins`；`tinyhumansai/openhuman`、`Imbad0202/academic-research-skills` 則掉出 Top 5。依完整 repo 名 `rg -F` 檢索結果，`anthropics/knowledge-work-plugins` 在既有保存報告中查無結果，依規則視為「未出現 / 新進榜候選」。
- 連續上榜：`colbymchenry/codegraph` 自 2026-05-20 起持續站在前段；`Lum1104/Understand-Anything` 連三天留在 Top 2；`rohitg00/ai-engineering-from-scratch` 連四天留在 Top 5；`ruvnet/RuView` 至少自 2026-05-18 起就在已保存樣本中反覆出現，今天重新回到前五。
- 成長異常：`Lum1104/Understand-Anything` 從昨天的 19,191 拉到今天 23,401，單日增加 4,210，是今日最明顯的加速；`colbymchenry/codegraph` 雖然單日只增加 213，但從 2026-05-20 到今天的累積增幅已達 16,774，仍是樣本內最完整的主升段。相對地，`ruvnet/RuView` 與今天掉出 Top 5 的 `tinyhumansai/openhuman`、`Imbad0202/academic-research-skills` 都更像 weekly rolling window 下的自然滑動。
- 比對不足說明：目前本機只保留 2026-05-15 到 2026-05-27 的已保存報告，且缺少 2026-05-19；因此本次 streak、首次出現與新進榜判斷皆以這批樣本為準，不外推到更早日期。

## 備註
- 今日 Top 5 依 GitHub Trending 頁面順序整理，不是單純照本週 stars 絕對值排序。
- 歷史比對優先以完整 repo 名做 `rg -F` 檢索；查無結果者依規則視為未出現 / 新進榜候選，不中止整體報告流程。
