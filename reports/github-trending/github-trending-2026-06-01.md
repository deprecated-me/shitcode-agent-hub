# GitHub Trending 週榜觀察（2026-06-01）

來源：<https://github.com/trending?since=weekly>

## 1) 今日 Top 5
1. harry0703/MoneyPrinterTurbo — Python — 15,955 stars this week
2. Lum1104/Understand-Anything — TypeScript — 22,750 stars this week
3. anthropics/knowledge-work-plugins — Python — 4,944 stars this week
4. rohitg00/ai-engineering-from-scratch — Python — 10,586 stars this week
5. hardikpandya/stop-slop — N/A — 3,770 stars this week

## 2) 主題趨勢
- 「AI agent 開發工作流」仍是本週主線，但焦點正從 code understanding 擴到插件、教材與輸出品質控制。前五同時出現 `Understand-Anything`、`knowledge-work-plugins`、`ai-engineering-from-scratch`、`stop-slop`，代表市場在追的不只是「更懂 code」，還包括「更好地用 agent 工作」。
- Python 仍是最穩定的主流語言，前五佔三席；TypeScript 繼續支撐 agent tooling / graph 類產品。相較之下，今天新進前五的 `stop-slop` 沒標示語言，反而更像 prompt/skill 層產品直接吃到分發。
- 短影音生成熱度還在。`harry0703/MoneyPrinterTurbo` 連續第三天站在榜首，weekly stars 從昨天 13,948 再增到 15,955，代表 AI 內容生成不只是短暫回潮，而是本週後段最明顯的持續吸星題材。
- 榜外但仍在首頁前段的 repo 也透露同一方向：`Leonxlnx/taste-skill`、`colbymchenry/codegraph`、`affaan-m/ECC` 都圍繞 agent 品質、知識圖與 execution harness，說明 agent infra / workflow 敘事仍未退潮，只是今天被更多應用層與 skill 層專案分流。

## 3) 值得追蹤專案
- harry0703/MoneyPrinterTurbo：昨天 13,948，今天 15,955，單日再增 2,007，且連三天排第 1；這是目前最穩定的正向動能樣本。
- hardikpandya/stop-slop：今天直接打進 Top 5，用完整 repo 名在既有保存報告中查無結果，依規則可視為未出現 / 新進榜候選；「去除 AI 味」這種輸出品質控制 skill，可能是下一波高頻需求。
- Leonxlnx/taste-skill：昨天在既有樣本中首次出現，今天仍留在首頁前段且 weekly stars 升到 10,813；若明後天繼續往前排，代表「讓 AI 更有品味 / 更不 generic」可能會從邊緣題材變成主流工作流插件。
- anthropics/knowledge-work-plugins：雖然今天 weekly stars 較昨天回落到 4,944，但已連續多天停留前五，顯示知識工作 plugin 生態不是一次性流量。
- colbymchenry/codegraph：今天跌出 Top 5，但仍留在首頁第 8；從 2026-05-20 到 2026-05-31 的保存樣本看，它是這波 agent code graph 題材最長的一段主升浪，後續要觀察這次退位是 rolling window 滑動，還是真的被 skill/plugin 類題材接手。

## 4) 歷史比對
- 新進榜 / 進出變化：相較 2026-05-31，今天 Top 5 新成員是 `hardikpandya/stop-slop`，`colbymchenry/codegraph` 則掉出 Top 5；`anthropics/knowledge-work-plugins` 從第 4 升到第 3，`rohitg00/ai-engineering-from-scratch` 從第 3 退到第 4。依完整 repo 名 `rg -F` 檢索結果，`hardikpandya/stop-slop` 在既有保存報告中查無結果，本次依規則視為「未出現 / 新進榜候選」。
- 連續上榜：`rohitg00/ai-engineering-from-scratch` 自 2026-05-25 起連 8 天留在 Top 5；`Lum1104/Understand-Anything` 自 2026-05-26 起連 7 天留在前段；`anthropics/knowledge-work-plugins` 自 2026-05-28 起連 5 天留榜；`harry0703/MoneyPrinterTurbo` 自 2026-05-29 起連 4 天留榜。`colbymchenry/codegraph` 在 2026-05-20 到 2026-05-31 連 12 天留在 Top 5，但今天中斷。
- 成長異常：`harry0703/MoneyPrinterTurbo` 從昨天的 13,948 增到今天 15,955，單日增加 2,007，仍是前五裡唯一明顯正增長；`Lum1104/Understand-Anything`、`anthropics/knowledge-work-plugins`、`rohitg00/ai-engineering-from-scratch` 的 weekly stars 都較昨天回落，較像 GitHub weekly rolling window 的自然滑動。`hardikpandya/stop-slop` 因歷史樣本中查無完整 repo 名，暫時無法做連續增長判讀。
- 比對不足說明：目前本機只保留 2026-05-15 到 2026-05-31 的已保存報告，且缺少 2026-05-19；因此 streak、首次出現與異常成長判斷皆以這批樣本為準。今天榜單本身已成功抓取，歷史比對未因個別 repo 查無資料而中止；查無完整 repo 名者均依規則視為未出現 / 新進榜候選。

## 備註
- 今日 Top 5 依 GitHub Trending 頁面順序整理，不是單純照本週 stars 絕對值排序；因此 `Lum1104/Understand-Anything` 的 weekly stars 雖高於 `harry0703/MoneyPrinterTurbo`，仍按頁面順序列為第 2。
