# GitHub Weekly Trending — 2026-07-22（週三）

> 資料來源：[GitHub Trending Weekly](https://github.com/trending?since=weekly)，抓取時間 2026-07-22 08:00 CST。
> `web_fetch` 透過 readability 萃取約 18 個 repo（GitHub Trending 通常 25 個），[Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) 與 [mattpocock/skills](https://github.com/mattpocock/skills) 出現在頁面但 star/本週數據未完整擷取。
> 歷史比對使用 `rg -F` 精確匹配完整 repo 名，比對 29 份歷史報告（05-23 ~ 07-21）。

---

## 1) 今日 Top 5

| # | Repo | 語言 | 本週 ⭐ | 總 ⭐ | 敘述 |
|---|------|------|---------|--------|------|
| 1 | [Nutlope/hallmark](https://github.com/Nutlope/hallmark) | CSS | 8,948 | 14.9K | Anti-AI-slop 設計技能，Claude Code / Cursor / Codex 通用 |
| 2 | [OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut) | TypeScript | 8,341 | 76.9K | 開源 CapCut 替代方案，Agent 影片剪輯賽道持續發燒 |
| 3 | [stablyai/orca](https://github.com/stablyai/orca) | TypeScript | 5,733 | 24.9K | ADE 並行 agent 管理平台，用自有訂閱運行多 agent 艦隊 |
| 4 | [tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph) | Python | 4,791 | 24.5K | Local-first code intelligence graph for MCP / CLI，知識圖譜化理解 codebase |
| 5 | [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) | C# | 4,047 | 20.6K | AI agent 專用 Office 套件——讀/寫/自動化 Word/Excel/PPT，single binary 免裝 Office |

---

## 2) 主題趨勢

1. **「知識圖譜化理解 codebase」成為 Agent 競爭錨點**：[tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph)（4,791 ⭐/wk，連續 3 日爆衝：1,103 → 3,073 → 4,791）領跑，[openai/codex](https://github.com/openai/codex)（Rust, 2,205 ⭐/wk）與 [openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter)（Rust, 2,205 ⭐/wk）緊隨——三方共同指向「用 graph 結構化理解代碼庫」取代 RAG + 遞歸搜索的粗糙模式。

2. **Agent × 設計／反 AI-slop 運動全面爆發**：[Nutlope/hallmark](https://github.com/Nutlope/hallmark)（8,948 ⭐/wk，連續 9 日在榜）與 [ibelick/ui-skills](https://github.com/ibelick/ui-skills)（2,094 ⭐/wk，▲+25.5%）分別代表「CSS 設計系統」與「設計工程師技能庫」雙路線。「反垃圾美感」從個人工具進化為標準化設計系統——當 AI 輸出泛濫，設計師／工程師反用 agent 對抗 agent。

3. **Agent 工具鏈從「寫程式」全面轉向「操作桌面 + Office + 終端機」**：[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)（4,047 ⭐/wk，連續 9+ 日）讓 agent 直接操作 Word/Excel/PPT，[earendil-works/pi](https://github.com/earendil-works/pi)（3,569 ⭐/wk，統一 LLM API + agent loop + TUI）提供底層運行時，[stablyai/orca](https://github.com/stablyai/orca)（5,733 ⭐/wk，連續 25+ 日長跑）管理多 agent 艦隊——Agent 正式從程式 editor 滲透到大眾辦公場景。

---

## 3) 值得追蹤專案

- **[tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph)** — Python，4,791 ⭐/wk，24.5K 總 ⭐。在榜第 3 日，連續爆衝（1,103 → 3,073 → 4,791，累積 ▲+334%）。Local-first code intelligence graph for MCP / CLI——Agent 對 codebase 的理解正從「暴力檢索」轉向「知識圖譜化」，本 repo 是該浪潮旗艦。動能極猛，需觀察能否在高基數下維持。

- **[Nutlope/hallmark](https://github.com/Nutlope/hallmark)** — CSS，8,948 ⭐/wk，14.9K 總 ⭐。連續 9 日在榜（07-14 首次進榜從未離開）。Anti-AI-slop 設計技能，Claude Code / Cursor / Codex 通用。存量 14.9K 總 ⭐ 搭配爆發式週增速，說明主流開發者群開始大量採用「設計品質標準化」工具。

- **[stablyai/orca](https://github.com/stablyai/orca)** — TypeScript，5,733 ⭐/wk，24.9K 總 ⭐。連續 25+ 日在榜（06-24 起頻繁出現），07-20 退出 Top 5 但仍在 full list。ADE 平台 + 自有訂閱——讓開發者帶著自己的 API key 管理多 agent 艦隊，是 Agent 走向實際產品化的標桿。

- **[1jehuang/jcode](https://github.com/1jehuang/jcode)** — Rust，1,769 ⭐/wk，10.3K 總 ⭐。**歷史全檔 0 記錄，首次進榜**。定位「最智慧的 agent harness for code」——以 Rust 實作切入 agent 運行時賽道，與 [openai/codex](https://github.com/openai/codex) 和 [openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter) 形成三方競逐。新面孔值得觀察後續動能。

- **[Dicklesworthstone/destructive_command_guard](https://github.com/Dicklesworthstone/destructive_command_guard)** — Rust，1,167 ⭐/wk，5.3K 總 ⭐。07-21 首次進榜後第 2 日。專門阻擋 Agent 執行危險 git/shell 指令——Agent 安全性從「研究課題」正式落地為「實際工程需求」。對於任何 production 級 agent 團隊，這是剛需工具。

---

## 4) 歷史榜單比對

### 🆕 新進榜 repo（歷史全檔 0 記錄）

- **[1jehuang/jcode](https://github.com/1jehuang/jcode)**：Rust，1,769 ⭐/wk，10.3K 總 ⭐。定位 "The most intelligent agent harness for code"，首次進榜即突破千字週星。

### 🔁 連續上榜 / 動能不減

- **[Nutlope/hallmark](https://github.com/Nutlope/hallmark)**：連續 9 日在榜（07-14 起）。07-19 8,834 → 今日 8,948 ▲+1.3%。動能最強新秀。
- **[OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut)**：連續 9+ 日在榜，穩居 TypeScript 影片剪輯霸主。07-20 曾跌 ▼-4.3%（連漲 5 日後首跌），今日 8,341 ⭐/wk，仍在 76.9K 總 ⭐ 量級穩坐前列。
- **[HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor)**：穩定在 full list，2,908 ⭐/wk，28.8K 總 ⭐。個人化終身導師——一邊 [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) 交易 Agent 連日重挫，一邊 DeepTutor 教育 Agent 逆勢走強，「學習」比「交易」更具持續剛需。
- **[HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading)**：3,679 ⭐/wk，26.1K 總 ⭐。動能持續降溫，從 07-19 的 5,635 下滑至今日 3,679 ▼-34.7%，進入第三週衰退週期。

### 📈 成長異常

- **[tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph)**：07-20 1,103 → 07-21 3,073 → 今日 4,791，3 日累積 ▲+334%，為本輪增速最猛。
- **[ibelick/ui-skills](https://github.com/ibelick/ui-skills)**：07-19 首次紀錄 1,098 → 07-20 1,669 → 今日 2,094，3 日累積 ▲+90.7%，增速次高。
- **[MoonshotAI/kimi-cli](https://github.com/MoonshotAI/kimi-cli)**：07-21 首次進榜 974 → 今日 1,294 ▲+32.8%，維持正向動能。

### ⬇️ 動能降溫

- **[HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading)**：連 3 日下滑，07-19 5,635 → 今日 3,679 ▼-34.7%。Agent 在交易場域的「新鮮感」進入長期調整。
- **[Dicklesworthstone/destructive_command_guard](https://github.com/Dicklesworthstone/destructive_command_guard)**：07-21 首次 1,410 → 今日 1,167 ▼-17.2%。
- **[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)**：動能持續降溫中，從 07-15 高點 7,129 降至今日 4,047 ▼-43.2%，但仍連續 9+ 日在榜。

### ⬇️ 退出 Top 5（仍在 full list）

- **[earendil-works/pi](https://github.com/earendil-works/pi)**：07-20 空降 #5（2,854 ⭐），今日 3,569 ⭐ 但排名退出 Top 5。
- **[stablyai/orca](https://github.com/stablyai/orca)**：07-20 退出 Top 5 但仍在 full list，本週 5,733 ⭐。

---

*報告由 OpenClaw cron 自動生成，歷史比對範圍 05-23 ~ 07-21。*
