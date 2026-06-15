# GitHub Trending 週榜觀察（2026-06-15）

來源：<https://github.com/trending?since=weekly>

## 1) 今日 Top 5
1. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) — Python — 12,053 stars this week
2. [apple/container](https://github.com/apple/container) — Swift — 10,021 stars this week
3. [phuryn/pm-skills](https://github.com/phuryn/pm-skills) — N/A — 5,713 stars this week
4. [chopratejas/headroom](https://github.com/chopratejas/headroom) — Python — 10,653 stars this week
5. [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) — Python — 3,669 stars this week

## 2) 主題趨勢
- 「agent skills / plugin / marketplace」仍是本週最明顯主線。[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)、[phuryn/pm-skills](https://github.com/phuryn/pm-skills)、[addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)、[Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) 都在解決 agent 能力如何被打包、分發、套用與品質控管。
- 「本地 / 端側執行環境」持續升溫。[apple/container](https://github.com/apple/container) 連 3 天留在 Top 5，weekly stars 從昨天 9,173 增到 10,021，代表 Apple silicon 上的輕量 VM / Linux container 工作流仍在吸引開發者注意。
- 「agent 安全與治理」跟著 skills 熱潮放大。[NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) 連 2 天進 Top 5，從 2,799 增到 3,669；當 skills / plugins 開始變成可安裝供應鏈，掃描惡意 pattern 與風險會自然變成配套需求。
- Python 仍是首頁主力語言，但 Swift、Shell、TypeScript、Rust、JavaScript 同時出現，顯示熱門焦點不是單一框架，而是圍繞 AI agent 的研究、壓縮、安全、桌面工具與本地執行環境。

## 3) 值得追蹤專案
- [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector)：昨天首次在本機報告中進 Top 5，今天 weekly stars 從 2,799 增到 3,669，安全掃描題材開始接上 skills / plugin 熱潮。
- [apple/container](https://github.com/apple/container)：從 2026-06-13 的 7,781 到今天 10,021，連 3 天 Top 5 且仍上行；若 Apple silicon 開發工作流持續擴散，這可能不只是短期話題。
- [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)：今天頁面第 6，Shell，10,445 stars this week；雖未進 Top 5，但與 [phuryn/pm-skills](https://github.com/phuryn/pm-skills) 一起強化「可重用 agent skill」這條主線。
- [chopratejas/headroom](https://github.com/chopratejas/headroom)：自 2026-06-03 起連續留在 Top 5，今天從 10,406 增到 10,653；context / tool output 壓縮仍是 agent 工程化的高需求基礎件。
- [safishamsi/graphify](https://github.com/safishamsi/graphify)：今天頁面第 15，Python，5,478 stars this week；用 code、schema、infra 建知識圖譜，切中「讓 agent 理解既有系統」的中長期需求，本機歷史報告未查到完整 repo 名，視為未出現 / 新進榜候選。

## 4) 歷史比對
- 新進榜 / 進出變化：相較 2026-06-14，今日 Top 5 成員與排序完全相同，沒有新進 Top 5，也沒有掉出 Top 5 的 repo。[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) 續守第 1，[apple/container](https://github.com/apple/container) 第 2，[phuryn/pm-skills](https://github.com/phuryn/pm-skills) 第 3，[chopratejas/headroom](https://github.com/chopratejas/headroom) 第 4，[NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) 第 5。
- 連續上榜：[chopratejas/headroom](https://github.com/chopratejas/headroom) 自 2026-06-03 起連 13 份保存報告留在 Top 5；[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) 連 7 天留榜；[apple/container](https://github.com/apple/container) 與 [phuryn/pm-skills](https://github.com/phuryn/pm-skills) 都連 3 天留榜；[NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) 連 2 天留榜。
- 成長異常：[NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) 從 2,799 增到 3,669，單日增加 870，是今日 Top 5 裡最明顯正向增長；[apple/container](https://github.com/apple/container) 從 9,173 增到 10,021，單日增加 848，也延續強勢。[phuryn/pm-skills](https://github.com/phuryn/pm-skills) 從 5,408 增到 5,713、[chopratejas/headroom](https://github.com/chopratejas/headroom) 從 10,406 增到 10,653，屬穩定續強；[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) 從 12,602 回落到 12,053，較像 GitHub weekly rolling window 的自然滑動。
- 比對不足說明：今日榜單先用 `web_fetch` 成功抓到主內容；因 readability 對部分 repo 欄位不完整，後續用原始 HTML 解析補齊，未使用 browser。歷史比對僅以本機 `reports/github-trending/` 既有保存報告為準；完整 repo 名 `rg -F` 查無結果時，依規則視為未出現 / 新進榜候選，而非錯誤。

## 備註
- 今日 Top 5 依 GitHub Trending 頁面順序整理，不是單純照本週 stars 絕對值排序；因此 [phuryn/pm-skills](https://github.com/phuryn/pm-skills) 的 weekly stars 低於 [chopratejas/headroom](https://github.com/chopratejas/headroom)，仍按頁面順序列為第 3。
