# GitHub Trending 週榜觀察（2026-06-14）

來源：<https://github.com/trending?since=weekly>

## 1) 今日 Top 5
1. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) — Python — 12,602 stars this week
2. [apple/container](https://github.com/apple/container) — Swift — 9,173 stars this week
3. [phuryn/pm-skills](https://github.com/phuryn/pm-skills) — N/A — 5,408 stars this week
4. [chopratejas/headroom](https://github.com/chopratejas/headroom) — Python — 10,406 stars this week
5. [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) — Python — 2,799 stars this week

## 2) 主題趨勢
- 「agent skills / plugins / workflow 配件」繼續佔據首頁核心。[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)、[phuryn/pm-skills](https://github.com/phuryn/pm-skills)、[addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)、[Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) 都在補 agent 的可組裝能力，代表熱點仍在「把代理能力產品化、技能化」。
- 「本地執行環境」明顯升溫。[apple/container](https://github.com/apple/container) 連兩天進 Top 5 並從第 4 升到第 2，說明 Apple silicon 上的 Linux container / VM 開發體驗正在成為本週新支線。
- 「agent 安全與治理」開始浮上前排。[NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) 直接進 Top 5，搭配近期 skills 類專案爆量，安全掃描、惡意 pattern 偵測、供應鏈風險會是自然延伸題。
- Python 仍是首頁最強承載語言，但 Swift、Shell、TypeScript 也很醒目；這波熱度不是單一模型框架，而是從研究、壓縮、容器、UI 到安全的完整工具鏈擴張。

## 3) 值得追蹤專案
- [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector)：用完整 repo 名 `rg -F` 在既有保存報告中查無結果，今天直接進 Top 5；在 skills 類 repo 爆紅後，安全掃描工具出現得很合理，值得觀察是否會形成「skill registry + vetting」的新需求。
- [apple/container](https://github.com/apple/container)：昨天 7,781，今天 9,173，雖然增幅比前一天放緩，但排名從第 4 升到第 2；Apple silicon 本地容器工作流仍在加速被注意。
- [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)：從昨天 12,257 增到 12,602，連 6 份保存報告留在 Top 5；research-first agent workflow 已是本週最穩定主線。
- [phuryn/pm-skills](https://github.com/phuryn/pm-skills)：昨天 4,839，今天 5,408，連 2 天留在 Top 5；PM 向 skills marketplace 持續吃到「代理工作流配件化」的題材。
- [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)：今天頁面第 6，仍有 9,348 stars this week；雖未進 Top 5，但和 [phuryn/pm-skills](https://github.com/phuryn/pm-skills)、[Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) 一起強化 agent skills 這條主線。

## 4) 歷史比對
- 新進榜 / 進出變化：相較 2026-06-13，今天 Top 5 新成員是 [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector)；[openai/plugins](https://github.com/openai/plugins) 掉出 Top 5。[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) 守住第 1，[apple/container](https://github.com/apple/container) 從第 4 升到第 2，[phuryn/pm-skills](https://github.com/phuryn/pm-skills) 維持第 3，[chopratejas/headroom](https://github.com/chopratejas/headroom) 從第 2 退到第 4。
- 連續上榜：[chopratejas/headroom](https://github.com/chopratejas/headroom) 自 2026-06-03 起連 12 份保存報告留在 Top 5；[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) 連 6 天留榜；[apple/container](https://github.com/apple/container) 與 [phuryn/pm-skills](https://github.com/phuryn/pm-skills) 都連 2 天留榜。[NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) 用完整 repo 名 `rg -F` 查無歷史結果，依規則視為未出現 / 新進榜候選。
- 成長異常：[apple/container](https://github.com/apple/container) 從 7,781 增到 9,173，仍是今日 Top 5 裡較明顯的正向續強；[phuryn/pm-skills](https://github.com/phuryn/pm-skills) 從 4,839 增到 5,408，也維持上行。[chopratejas/headroom](https://github.com/chopratejas/headroom) 從 10,184 回升到 10,406，屬高位持平；[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) 從 12,257 到 12,602，仍穩定但增速放緩。[NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) 因本機歷史樣本缺少前日 weekly stars，暫時無法做嚴格單日增速比較。
- 比對不足說明：今日榜單先用 `web_fetch` 成功抓到主內容；因 readability 抽取對部分 repo 欄位不完整，後續用原始 HTML 解析補齊，未使用 browser。歷史比對僅以本機 `reports/github-trending/` 既有保存報告為準；若完整 repo 名 `rg -F` 查無結果，均依規則視為未出現 / 新進榜候選，而非錯誤。

## 備註
- 今日 Top 5 依 GitHub Trending 頁面順序整理，不是單純照本週 stars 絕對值排序；因此 [chopratejas/headroom](https://github.com/chopratejas/headroom) 的 weekly stars 雖高於 [apple/container](https://github.com/apple/container) 與 [phuryn/pm-skills](https://github.com/phuryn/pm-skills)，仍按頁面順序列為第 4。
