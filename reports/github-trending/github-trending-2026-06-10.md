# GitHub Trending 週榜觀察（2026-06-10）

來源：<https://github.com/trending?since=weekly>

## 1) 今日 Top 5
1. [chopratejas/headroom](https://github.com/chopratejas/headroom) — Python — 15,060 stars this week
2. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) — Python — 9,307 stars this week
3. [microsoft/markitdown](https://github.com/microsoft/markitdown) — Python — 8,903 stars this week
4. [openai/plugins](https://github.com/openai/plugins) — JavaScript — 1,144 stars this week
5. [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) — Python — 4,361 stars this week

## 2) 主題趨勢
- 週榜前段進一步從「agent 基建」轉向「research / search 接入」。[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) 與 [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) 都在補 AI agent 的外部資訊攝取能力，一個做跨社群研究摘要、一個做多平台讀取與搜尋，顯示熱門點已不只在模型能力，而是怎麼把網路資訊接進工作流。
- Python 依然是本週首頁最強承載語言，今日 Top 5 直接佔 4 席。[chopratejas/headroom](https://github.com/chopratejas/headroom)、[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)、[microsoft/markitdown](https://github.com/microsoft/markitdown)、[Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) 分別對應 context 壓縮、研究彙整、文件轉 Markdown、搜尋橋接，都是能直接接進 AI pipeline 的實用層。
- 「舊 plugin / workflow 介面」題材也重新浮上前段。[openai/plugins](https://github.com/openai/plugins) 雖然 weekly stars 絕對值不高，但今天能排進第 4，代表開發者仍在回看代理外掛與工具接面這條老題材，或至少把它當成 agent 生態演化的參考座標。
- 互動層今天退到首頁中段而非消失。昨天在 Top 5 的 [Open-LLM-VTuber/Open-LLM-VTuber](https://github.com/Open-LLM-VTuber/Open-LLM-VTuber) 今天掉出前五，但像 [lfnovo/open-notebook](https://github.com/lfnovo/open-notebook) 這類產品化入口仍留在榜內，代表熱度暫時回到 research tooling 與工作流接入。

## 3) 值得追蹤專案
- [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)：昨天 6,616，今天 9,307，單日增加 2,691，且從第 3 升到第 2；如果這個增速能再撐 1-2 天，research-first agent workflow 很可能會從副主題變成首頁主線。
- [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach)：昨天 3,006，今天 4,361，單日增加 1,355；它把 Twitter、Reddit、YouTube、GitHub、Bilibili、XiaoHongShu 等來源拉進同一條 CLI 讀取鏈，這種「低成本讓 agent 看完整個網路」的敘事升溫很快。
- [chopratejas/headroom](https://github.com/chopratejas/headroom)：昨天 14,266，今天 15,060，單日增加 794，且自 2026-06-03 起連 8 份保存報告留在 Top 5；「先壓縮 tool outputs / logs / chunks 再送模型」已經從單點工具長成穩定主線。
- [openai/plugins](https://github.com/openai/plugins)：用完整 repo 名 `rg -F` 在既有保存報告中查無結果，依規則視為未出現 / 新進榜候選；雖然它不是新 repo，但今天突然擠進第 4，值得觀察這是短期懷舊回流，還是 plugin interface 題材重新被 agent 生態帶起。
- [lfnovo/open-notebook](https://github.com/lfnovo/open-notebook)：今天仍留在榜內，且 2026-06-08 的保存報告記到它有 2,993 stars this week；如果它和 research 類 repo 一起連續留榜，代表「搜尋 / 摘要 / 知識工作台」會開始收斂成更完整的產品化組合。

## 4) 歷史比對
- 新進榜 / 進出變化：相較 2026-06-09，今天 Top 5 新成員是 [openai/plugins](https://github.com/openai/plugins)；[Open-LLM-VTuber/Open-LLM-VTuber](https://github.com/Open-LLM-VTuber/Open-LLM-VTuber) 則掉出 Top 5。[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) 從第 3 升到第 2，[microsoft/markitdown](https://github.com/microsoft/markitdown) 從第 2 退到第 3；[chopratejas/headroom](https://github.com/chopratejas/headroom) 與 [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) 分別守住第 1 與第 5。
- 連續上榜：[microsoft/markitdown](https://github.com/microsoft/markitdown) 自 2026-06-02 起連 9 份保存報告留在 Top 5；[chopratejas/headroom](https://github.com/chopratejas/headroom) 自 2026-06-03 起連 8 份保存報告留在 Top 5；[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) 與 [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) 都連 2 天留在 Top 5。[openai/plugins](https://github.com/openai/plugins) 用完整 repo 名 `rg -F` 查無歷史結果，依規則視為未出現 / 新進榜候選。
- 成長異常：[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) 從 6,616 增到 9,307，單日增加 2,691，是今日 Top 5 裡最明顯的正向加速；[Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) 從 3,006 增到 4,361，也有 1,355 的明顯升幅；[chopratejas/headroom](https://github.com/chopratejas/headroom) 從 14,266 升到 15,060，維持高位續強。[microsoft/markitdown](https://github.com/microsoft/markitdown) 從 11,177 回到 8,903，較像 GitHub weekly rolling window 的自然滑動。對 [openai/plugins](https://github.com/openai/plugins) 而言，本機歷史樣本缺少前日精確 weekly stars，因此暫時無法做嚴格的單日異常增長判讀。
- 比對不足說明：今日榜單先用 `web_fetch` 成功抓到主內容，但因部分條目的語言與 weekly stars 擷取不完整，後續改用 browser 補齊結構化欄位。歷史比對僅以本機 `reports/github-trending/` 既有保存報告為準；若某些 repo 用完整 repo 名 `rg -F` 查無結果，均依規則視為未出現 / 新進榜候選，而非錯誤。

## 備註
- 今日 Top 5 依 GitHub Trending 頁面順序整理，不是單純照本週 stars 絕對值排序；因此 [openai/plugins](https://github.com/openai/plugins) 的 weekly stars 雖低於榜內其他專案，仍按頁面順序列為第 4。
