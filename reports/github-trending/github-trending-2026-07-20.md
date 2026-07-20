# GitHub Weekly Trending — 2026-07-20（一）

> 資料區間：抓取時間 2026-07-20 08:00 CST（UTC+8），對應 GitHub `?since=weekly`。

---

## 1) 今日 Top 5（repo、語言、本週 stars）

| # | Repo | Language | 本週 ⭐ | 備註 |
|---|------|----------|---------|------|
| 1 | [OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut) | TypeScript | 12,743 | 開源 CapCut 替代方案，75.9K 總 ⭐，本週 ▼ -4.3%（昨日 13,319 → 今日 12,743），**連漲 5 日後首跌**，但仍在 75.9K 總 ⭐ 量級穩坐 #1 |
| 2 | [Nutlope/hallmark](https://github.com/Nutlope/hallmark) | CSS | 9,193 | Anti-AI-slop 設計技能，13.4K 總 ⭐，本週 ▲ +4.1%（昨日 8,834 → 今日 9,193），**連續 6 日在榜**，存量雖小但動能穩定 |
| 3 | [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) | Python | 5,228 | 「Vibe-Trading: Your Personal Trading Agent」，25.3K 總 ⭐，本週 ▼ -7.2%（昨日 5,635 → 今日 5,228），**連續 5 日在榜**，但動能明顯降溫 |
| 4 | [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) | C# | 4,269 | 為 AI agent 打造的 Office 套件，19.6K 總 ⭐，本週 ▼ -0.3%（昨日 4,284 → 今日 4,269），**連跌 3 日後觸底企稳**，連續 10 日在榜 |
| 5 | [earendil-works/pi](https://github.com/earendil-works/pi) | TypeScript | 2,854 | AI agent toolkit：統一 LLM API、agent loop、TUI、coding agent CLI，72.8K 總 ⭐，**歷史首次進榜即空降 #5**，動能暴發 |

> **Top 5 變動**：[Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify)（昨日 #3，8,611 ⭐）與 [stablyai/orca](https://github.com/stablyai/orca)（昨日 #5，5,520 ⭐）退出 Top 5；[earendil-works/pi](https://github.com/earendil-works/pi) 空降 #5。[HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor)（2,375 ⭐/wk）穩定在 full list，[openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter)（2,498 ⭐/wk）超越 DeepTutor 但未進入 Top 5。

---

## 2) 主題趨勢

1. **Anti-AI-slop 設計運動持續分化，領跑者與追趕者同時爆發**：[Nutlope/hallmark](https://github.com/Nutlope/hallmark)（9,193 ⭐/wk，▲ +4.1%，連續 6 日）與 [ibelick/ui-skills](https://github.com/ibelick/ui-skills)（1,669 ⭐/wk，**▲ +52.0% 日增為全榜最高**）分別代表「CSS 設計系統」與「設計工程師技能庫」兩條路線。「反垃圾美感」從個人工具進化為標準化設計系統——當 AI 輸出泛濫成災，設計師與工程師開始用 agent 對抗 agent。

2. **Rust + TypeScript 同時大量投入 Agent 底層工具鏈——從概念走向實際部署**：[earendil-works/pi](https://github.com/earendil-works/pi)（72.8K 總 ⭐，歷史首次進榜即空降 #5）作為統一 LLM API + agent loop + TUI 的 toolkit；[openai/codex](https://github.com/openai/codex)（2,361 ⭐/wk，▲ +4.1%）與 [openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter)（2,498 ⭐/wk，▲ +6.6%）持續攀升。三方同時指向開發者對「輕量化、高效能 agent 運行時」的需求已進入實際部署階段。

3. **Agent 垂直場域動能分化——影片 + 設計 ↑ vs. 交易 ↓**：[OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut) 雖本週首跌（▼ -4.3%），但仍在 75.9K 總 ⭐ 穩坐 #1，且 [Nutlope/hallmark](https://github.com/Nutlope/hallmark) 與 [ibelick/ui-skills](https://github.com/ibelick/ui-skills) 共推「設計品質標準化」持續創高。但 [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading)（▼ -7.2%）卻出現明顯回檔——Agent 在金融交易領域的「新鮮感」可能進入冷靜期，需观察能否守住 5,000 關卡。

4. **OfficeCLI 觸底企稳，Agent 辦公场景仍在但需新刺激**：[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) 連跌 3 日後今日幾乎持平（▼ -0.3%），連續 10 日在榜。Agent × Office 的結合已站穩利基，但增速放緩說明需要新一輪功能刺激才能重返成長軌道。

---

## 3) 值得追蹤專案

1. **[earendil-works/pi](https://github.com/earendil-works/pi)** — TypeScript，2,854 ⭐/wk，72.8K 總 ⭐，**歷史首次進榜即空降 #5**。AI agent toolkit：統一 LLM API、agent loop、TUI、coding agent CLI。由 badlogic / mitsuhiko 等人開發，底層架構極度精煉。歷史全檔（約 57 份報告）0 記錄即空降 Top 5，動能異常暴發——可能與 mitsuhiko 的社群影響力或產品重大更新有關。

2. **[ibelick/ui-skills](https://github.com/ibelick/ui-skills)** — TypeScript，1,669 ⭐/wk（▲ +52.0%），5.4K 總 ⭐，**連續 2 日在榜，日增為全榜最高**。設計工程師專用技能庫——如果 hallmarks 是「反垃圾美感」的 CSS 系統，ui-skills 就是「設計工程師」的 agent 技能組合。從 07-18 首次在 full list 出現（無數據）→ 07-19 取得 1,098 ⭐/wk → 今日 1,669 ⭐/wk +52% 日增，爆發模式與 hallmark 07-14 進榜時高度相似。

3. **[openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter)** — Rust，2,498 ⭐/wk（▲ +6.6%），66.8K 總 ⭐，**連續 2 日在榜，動能超越 openai/codex**。為開源模型（如 Kimi K3）打造的 coding agent，與 [openai/codex](https://github.com/openai/codex) 的「鏡像競爭」中今日首次實現 stars/wk 反超（2,498 vs 2,361）。閉源 vs. open model 的 agent 戰爭正在全面升溫。

4. **[Nutlope/hallmark](https://github.com/Nutlope/hallmark)** — CSS，9,193 ⭐/wk（▲ +4.1%），13.4K 總 ⭐，**連續 6 日在榜**。存量虽小但動能穩定，反映「反 AI 垃圾美感」需求仍在爬升期。能穩定維持高週增速而不見頹勢的项目少見——與 OpenCut 並列為本週趨勢的「壓艙石」。

5. **[HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor)** — Python，2,375 ⭐/wk，27.9K 總 ⭐，穩定在 full list。個人化終身導師——當 [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) 交易 Agent 出現回檔時，教育 Agent 反而穩定在榜，說明「學習」比「交易」具有更持續的 agent 剛需，值得長期觀察。

---

## 4) 新進榜 / 連續上榜 / 成長異常

### 新進榜（歷史全檔 0 記錄）

| Repo | 位置 | 說明 |
|------|------|------|
| [earendil-works/pi](https://github.com/earendil-works/pi) | 🆕 空降 #5 | 歷史全檔 0 記錄（`rg -F` 精確匹配），72.8K 總 ⭐ 直接空降 Top 5，動能暴發 |
| [tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph) | 🆕 首次進榜 | Python，1,103 ⭐/wk，21.1K 總 ⭐。Local-first code intelligence graph for MCP and CLI——過去 Agent 靠 RAG + 遞歸搜索的粗糙模式正在被「知識圖譜化」取代的另一個信號 |
| [anthropics/cwc-workshops](https://github.com/anthropics/cwc-workshops) | 🆕 首次進榜 | TypeScript，317 ⭐/wk，1.8K 總 ⭐。Anthropic 官方 CWC（Claude Workshops）培訓資料—存量雖小但代表官方教育資源開始受到社群關注 |

### 退出榜單（昨日 Top 5 → 今日未上榜）

| Repo | 昨日位置 | 說明 |
|------|--------|------|
| [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify) | 昨日 #3（8,611 ⭐） | 07-18 出現在 full list（無數據）→ 07-19 空降 Top 3 → 今日退出，曇花一現 |
| [stablyai/orca](https://github.com/stablyai/orca) | 昨日 #5（5,520 ⭐） | 連續 25+ 日在榜後終於退出，06-24 起頻繁在榜的長跑選手落幕 |

### 連續上榜

| Repo | 連續天數 | 狀態 |
|------|---------|------|
| [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) | 10 天 | 連跌 3 日後企稳，動能觸底 |
| [Nutlope/hallmark](https://github.com/Nutlope/hallmark) | 6 天 | 動能穩定，▲ +4.1% 日增 |
| [ibelick/ui-skills](https://github.com/ibelick/ui-skills) | 2 天 | 爆發中，▲ +52.0% 日增 |
| [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) | 5 天 | 動能降溫，▼ -7.2% 日增 |
| [openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter) | 2 天 | 動能加速，▲ +6.6% 日增 |
| [openai/codex](https://github.com/openai/codex) | 2 天 | 穩定，▲ +4.1% 日增 |

### Top 5 逐日對比（vs 07-19）

| Repo | 07-19 | 07-20 | 變化 |
|------|-------|-------|------|
| [OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut) | 13,319 | 12,743 | ▼ -4.3%，連漲 5 日後首跌 |
| [Nutlope/hallmark](https://github.com/Nutlope/hallmark) | 8,834 | 9,193 | ▲ +4.1%，增速放緩但持續創高 |
| [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) | 5,635 | 5,228 | ▼ -7.2%，最大跌幅 |
| [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) | 4,284 | 4,269 | ▼ -0.3%，觸底企稳 |
| [earendil-works/pi](https://github.com/earendil-works/pi) | — | 2,854 | 🆕 空降 |

---

## 資料限制

- `web_fetch` 透過 readability 萃取約 14 個 repo（GitHub Trending 通常 25 個），[Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) 與 [mattpocock/skills](https://github.com/mattpocock/skills) 出現在頁面但 star/本週數據未完整擷取。
- 歷史比對使用 `rg -F` 精確匹配完整 repo 名（owner/name），共比對約 57 份歷史報告（05-23 ~ 07-19），無資料缺失。
- [earendil-works/pi](https://github.com/earendil-works/pi)、[tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph)、[anthropics/cwc-workshops](https://github.com/anthropics/cwc-workshops) 均為歷史全檔 0 記錄的首次進榜專案。
- [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify) 與 [stablyai/orca](https://github.com/stablyai/orca) 退出榜單——前者僅在 07-19 出現一天即消失，後者連續 25+ 日後終於謝幕。
- [openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter) 今日 stars/wk 首次超越 [openai/codex](https://github.com/openai/codex)（2,498 vs 2,361），為歷史首次。
