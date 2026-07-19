# GitHub Weekly Trending — 2026-07-19（日）

> 資料區間：抓取時間 2026-07-19 08:00 CST（UTC+8），對應 GitHub `?since=weekly`。

---

## 1) 今日 Top 5（repo、語言、本週 stars）

| # | Repo | Language | 本週 ⭐ | 備註 |
|---|------|----------|---------|------|
| 1 | [OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut) | TypeScript | 13,319 | 開源 CapCut 替代方案，75.4K 總 ⭐，本週 ▲ +4.7%（昨日 12,718 → 今日 13,319），連續 4 日創高 |
| 2 | [Nutlope/hallmark](https://github.com/Nutlope/hallmark) | CSS | 8,834 | Anti-AI-slop 設計技能，12.8K 總 ⭐，本週 ▲ +9.4%（昨日 8,075 → 今日 8,834），連續 5 日在榜 |
| 3 | [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify) | Python | 8,611 | AI 知識圖譜：將任何代碼/文檔/媒體轉為可查詢 graph，90.9K 總 ⭐，歷史首次取得 stars/wk 數據即空降 Top 5 |
| 4 | [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) | Python | 5,635 | 「Vibe-Trading: Your Personal Trading Agent」，24.9K 總 ⭐，本週 ▲ +0.3%（昨日 5,616 → 今日 5,635），連續 4 日在榜 |
| 5 | [stablyai/orca](https://github.com/stablyai/orca) | TypeScript | 5,520 | ADE 平台，用自身訂閱運行 agent 艦隊，21.8K 總 ⭐，本週 ▲ +2.1%（昨日 5,409 → 今日 5,520），連續 25+ 日在榜 |

> **iOfficeAI/OfficeCLI 跌出 Top 5**：昨日 #5（4,611 ⭐）→ 今日 4,284 ⭐，連跌 3 日（▼ -7.1%），退居 #6 但仍連續 9 日在榜。

---

## 2) 主題趨勢

1. **AI Knowledge Graph 正式破圈——代碼庫成為 Agent 的第一输入**：[Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify)（8,611 ⭐/wk，90.9K 總 ⭐）從 full list 直接攻進 Top 3，[openai/codex](https://github.com/openai/codex)（Rust，2,268 ⭐/wk）與 [openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter)（Rust，2,344 ⭐/wk）同時回歸榜單——三方同時指向「用 graph 結構化理解代碼庫」成為 2026 下半年 Agent 競爭的新錨點。過去 Agent 靠 RAG + 遞歸搜索的粗糙模式正在被「知識圖譜化」取代。

2. **Anti-AI-slop 設計工具持續爆發，但分化開始**：[Nutlope/hallmark](https://github.com/Nutlope/hallmark)（8,834 ⭐/wk，▲ +9.4%）與 [ibelick/ui-skills](https://github.com/ibelick/ui-skills)（1,098 ⭐/wk，歷史首次取得 stars/wk 數據）分別代表「CSS 設計系統」與「設計工程師技能庫」兩條路線。市場不再滿足於「讓 AI」，而是要求「讓 AI 輸出符合人類設計品質標準化」。

3. **垂直 Agent 場域全面落地——交易 + 教育 + 影片三線並進**：[HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading)（交易 Agent，5,635 ⭐/wk）連續 4 日穩居 Top 5，[HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor)（個人化終身導師，27.6K 總 ⭐）也穩定在 full list。Agent 已從「工程師生產力工具」正式擴張到大眾垂直場域——金融交易、線上教育、影片剪輯（[OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut)）形成三足鼎立。

4. **底層語言工具鏈週期輪動——Rust + C++ 同時回歸**：[openai/codex](https://github.com/openai/codex)（Rust 99.4K 總 ⭐）與 [openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter)（Rust 66.7K 總 ⭐）同時回歸，[abseil/abseil-cpp](https://github.com/abseil/abseil-cpp)（C++，連續 3 日在榜）——在 TS/Python 統治趨勢多週後，底層語言工具鏈重新進入開發者視野，暗示 Agent 底層建置對效能與資源控制的再投資。

---

## 3) 值得追蹤專案

1. **[Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify)** — Python，8,611 ⭐/wk，90.9K 總 ⭐，**歷史首次取得 stars/wk 數據即空降 Top 3**。能將任何文件夾、SQL schema、R 腳本、Shell 腳本、論文、圖片、影片轉為可查詢的知識圖譜，涵蓋 App 代碼 + 資料庫 schema + infra 的統一 graph。過去 Agent 靠 RAG + 遞歸搜索的粗糙模式正在被「知識圖譜化」取代——graphify 是目前最成熟的實作。

2. **[openai/codex](https://github.com/openai/codex)** — Rust，2,268 ⭐/wk，99.4K 總 ⭐，**歷史首次出現在 trending 資料中**。輕量級 terminal 內運行的 coding agent。99.4K 總 ⭐ 的量級搭配本週突然爆發，說明 OpenAI 可能大幅更新產品或開放了新使用場景。Rust 實作 + 終端原生 = 與 [openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter) 的正面對決。

3. **[openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter)** — Rust，2,344 ⭐/wk，66.7K 總 ⭐，**歷史首次出現在 trending 資料中**。為開源模型（如 Kimi K3）打造的 coding agent。與 openai/codex 幾乎同時回歸、同樣 Rust 實作的「鏡像競爭」，代表 2026 下半年閉源 vs. open model 的 agent 戰爭正式升溫。

4. **[Nutlope/hallmark](https://github.com/Nutlope/hallmark)** — CSS，8,834 ⭐/wk，12.8K 總 ⭐，**本週增速▲ +9.4%，連續 5 日在榜**。Anti-AI-slop 設計技能，Claude Code / Cursor / Codex 通用。存量 12.8K 總 ⭐ 搭配爆發式週增速，說明主流開發者群開始大量採用「設計品質標準化」工具——當 AI 輸出泛濫成災，「反垃圾美感」本身成為剛需。

5. **[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)** — C#，4,284 ⭐/wk，19.3K 總 ⭐，連續 9 日在榜。動能降溫中（連跌 3 日 ▼ -7.1%），但仍是 Agent 工具鏈跨入辦公場景的標桿指標。Single binary + 免裝 Office 的精準架構，已證明 Agent × Office 自動化是真實剛需而非曇花一現。

---

## 4) 新進榜 / 連續上榜 / 成長異常

| Repo | 狀態 | 說明 |
|------|------|------|
| [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify) | 🆕 新進 Top 5 | 歷史報告僅 07-18 出現在 full list 無 stars/wk 數據，今日首次有 8,611 ⭐/wk 數據即空降 Top 3；90.9K 總 ⭐ 為全榜存量最高之一 |
| [openai/codex](https://github.com/openai/codex) | 🆕 首次進榜 | 歷史全檔 0 記錄（`rg -F` 精確匹配），99.4K 總 ⭐ 本週突然爆發 2,268 ⭐/wk，原因待查 |
| [openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter) | 🆕 首次進榜 | 歷史全檔 0 記錄（`rg -F` 精確匹配），66.7K 總 ⭐ 回歸 |
| [ibelick/ui-skills](https://github.com/ibelick/ui-skills) | 🆕 首次取得 stars/wk 數據 | 07-18 曾出現在 full list 但無數據，今日首次有 1,098 ⭐/wk |
| [abseil/abseil-cpp](https://github.com/abseil/abseil-cpp) | 連續 3 日在榜 | 07-14 首次 → 消失 → 07-17 回歸後至今，底層 C++ 工具鏈回歸指標 |
| [Nutlope/hallmark](https://github.com/Nutlope/hallmark) | 連續 5 日在榜 | 07-14 首次進榜以來從未離開，動能最強的新秀 |
| [stablyai/orca](https://github.com/stablyai/orca) | 連續 25+ 日在榜 | 06-24 起頻繁在榜，本輪最穩定長跑選手 |

### Top 5 逐日對比（vs 07-18）

| Repo | 07-18 | 07-19 | 變化 |
|------|-------|-------|------|
| [OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut) | 12,718 | 13,319 | ▲ +4.7%，動能持續創高 |
| [Nutlope/hallmark](https://github.com/Nutlope/hallmark) | 8,075 | 8,834 | ▲ +9.4%，增速不減 |
| [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify) | —（full list 無數據） | 8,611 | 🆕 空降 Top 3 |
| [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) | 5,616 | 5,635 | ▲ +0.3%，持平 |
| [stablyai/orca](https://github.com/stablyai/orca) | 5,409 | 5,520 | ▲ +2.1%，穩定增長 |
| [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) | 4,611 | 4,284 | ▼ -7.1%，連跌 3 日退出 Top 5 |

---

## 資料限制

- `web_fetch` 透過 readability 萃取約 15 個 repo（GitHub Trending 通常 25 個），[Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) 與 [mattpocock/skills](https://github.com/mattpocock/skills) 出現在頁面但 star/本週數據未完整擷取。
- 歷史比對使用 `rg -F` 精確匹配完整 repo 名（owner/name），共比對 19 份歷史報告（05-23 ~ 07-18），無資料缺失。
- [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify) 與 [ibelick/ui-skills](https://github.com/ibelick/ui-skills) 在 07-18 報告中出現在 full list 但無 stars/wk 數據，本次為首次取得完整 stars/wk 數據。
- [openai/codex](https://github.com/openai/codex) 與 [openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter) 均為歷史全檔 0 記錄的首次進榜專案。
