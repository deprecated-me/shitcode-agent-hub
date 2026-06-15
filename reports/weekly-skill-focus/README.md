# weekly-skill-focus

本週焦點週報（HTML）。每週五早上九點，由排程 agent 將 `reports/github-trending/` 近 30 天日報彙整為「本週焦點」，
與 30 天歷史比對、做多維分類後，用 `/frontend-design:frontend-design` 產出方便瀏覽的單檔 HTML。

## 檔名

`weekly-skill-focus-YYYY-MM-DD.html` — 日期為產出當日（通常為週五）。

## 內容結構

1. **本週焦點 takeaways** — 跨本週 7 份日報彙整出的 3–5 條重點。
2. **榜單動態四象限** — 新進榜 / 連續霸榜 / 爆發成長 / 退潮掉榜。
3. **主題多維分類** — Agent Skill 生態系、安全與品質、Context 效率、研究搜尋、本地基建、互動層等。
4. **30 天主題演變** — 熱度焦點隨時間的遷移時間軸。
5. **30 天最持久專案** — 連續留在 Top 5 的天數排行。
6. **值得追蹤** — 熱度未必在 Top 5、但敘事續強的專案。

## 來源與比對基準

- 資料來源：`reports/github-trending/`（GitHub Trending 週榜日報，僅保留最近 30 天）。
- 比對基準：產出當日往前的近 30 天全部日報。

## 自動化

每週五 09:00 由雲端排程 routine 自動執行並 commit/push 到 `openclaw` 分支。本機手動執行時會額外開瀏覽器預覽。
