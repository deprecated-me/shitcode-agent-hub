# GitHub Trending 週榜觀察（2026-05-22）

來源：<https://github.com/trending?since=weekly>

## 1) 今日 Top 5
1. tinyhumansai/openhuman — Rust — 17,399 stars this week
2. colbymchenry/codegraph — TypeScript — 10,749 stars this week
3. Imbad0202/academic-research-skills — Python — 10,737 stars this week
4. supertone-inc/supertonic — Swift — 4,120 stars this week
5. rohitg00/agentmemory — TypeScript — 7,000 stars this week

## 2) 主題趨勢
- Agent workflow 依然是本週主軸，但焦點更集中在「可直接嵌入日常工作流」的題材：personal AI、code knowledge graph、academic research workflow、persistent memory 同時卡進前五。
- 語言分布比前幾天更分散。Rust、TypeScript、Python 仍穩，但 Swift 靠 `supertone-inc/supertonic` 衝進前段，顯示端側推論與本地體驗開始拿到更高注意力。
- Skills / methodology 類 repo 持續強勢。除了 Top 5 的 `Imbad0202/academic-research-skills`，榜內還有 `mattpocock/skills`、`obra/superpowers`，代表「把 agent 能力封裝成可複用工作法」仍是熱門敘事。
- 熱點不只停留在 coding assistant。榜內還看得到 stealth browser、WiFi spatial intelligence、video generation 等基礎能力型專案，說明資金與注意力仍在往 agent 周邊基建擴散。

## 3) 值得追蹤專案
- colbymchenry/codegraph：從 2026-05-20 的 4,650 到今天 10,749，本週 stars 三天增加 6,099，成長斜率是目前樣本裡最兇的一支，而且題材直接貼近 Claude Code、Codex、Cursor、OpenCode。
- tinyhumansai/openhuman：雖然 rolling weekly stars 比昨天回落，但已連 3 天維持頁面第一，顯示 personal AI / local-first agent 這條線的熱度還沒退。
- Imbad0202/academic-research-skills：今天衝到頁面第 3，代表 research workflow 不再只是 skills 長尾，而是開始進入主流 agent 工具視野。
- supertone-inc/supertonic：本次保存樣本裡首次打進 Top 5，且主打 on-device multilingual TTS；若 edge AI 持續升溫，這類端側語音基建值得持續盯。
- mattpocock/skills：雖然不在今日 Top 5，但今天仍有 17,535 stars this week，絕對吸星能力依舊很高，適合當作「方法論型 repo」是否能長期留量的指標。

## 4) 歷史比對（對照已保存報告：2026-05-15、2026-05-16、2026-05-17、2026-05-18、2026-05-20、2026-05-21）
- 新進榜：相較 2026-05-21 的 Top 5，`Imbad0202/academic-research-skills`、`supertone-inc/supertonic` 是今天的新成員；其中 `supertone-inc/supertonic` 在既有報告中查不到完整 repo 名，可視為目前已保存樣本裡的「未出現 / 新進榜候選」。
- 連續上榜：`tinyhumansai/openhuman` 自 2026-05-20 起連 3 天維持頁面第 1；`rohitg00/agentmemory` 自 2026-05-15 起每天都出現在已保存樣本；`Imbad0202/academic-research-skills` 自 2026-05-17 起持續在報告中可見。
- 成長異常：`colbymchenry/codegraph` 從 2026-05-20 的 4,650 漲到今天 10,749，三天內增加 6,099；`Imbad0202/academic-research-skills` 也從 2026-05-21 的 8,737 增到今天 10,737。相對地，`tinyhumansai/openhuman`、`rohitg00/agentmemory` 的 weekly stars 較昨日回落，這比較像 GitHub weekly rolling window 的自然滑動，不代表熱度一定轉弱。
- 掉出前排：2026-05-20 與 2026-05-21 還在 Top 5 的 `CloakHQ/CloakBrowser`、`ruvnet/RuView` 今天讓位給更偏 workflow / creator tooling 的 `academic-research-skills` 與 `supertonic`，榜首敘事明顯從 stealth / sensing 轉向實用型 agent workflow。

## 備註
- 今日 Top 5 依 GitHub Trending 頁面順序整理，不是單純照本週 stars 絕對值排序。
- 歷史比對優先以完整 repo 名做 `rg -F` 檢索；對 `supertone-inc/supertonic` 的歷史結果為「查無完整 repo 名」，本次按規則視為未出現 / 新進榜候選，而非錯誤。
