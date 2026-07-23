# GitHub Weekly Trending — 2026-07-23（週四）

> 資料來源：[GitHub Trending Weekly](https://github.com/trending?since=weekly)，抓取時間 2026-07-23 08:00 CST。
> `web_fetch` 透過 readability 萃取約 19 個 repo（GitHub Trending 通常 25 個），[Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) 與 [mattpocock/skills](https://github.com/mattpocock/skills) 出現在頁面但 star/本週數據未完整擷取。
> 歷史比對使用 `rg -F` 精確匹配完整 repo 名，比對 60 份歷史報告（05-23 ~ 07-22）。

---

## 1) 今日 Top 5

| # | Repo | 語言 | 本週 ⭐ | 總 ⭐ | 敘述 |
|---|------|------|---------|--------|------|
| 1 | [Nutlope/hallmark](https://github.com/Nutlope/hallmark) | CSS | 8,471 | 15.6K | Anti-AI-slop 設計技能，Claude Code / Cursor / Codex 通用 |
| 2 | [OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut) | TypeScript | 7,394 | 77.6K | 開源 CapCut 替代方案，Agent 影片剪輯賽道持續發燒 |
| 3 | [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) | TypeScript | 6,989 | 25.2K | 免費 AI 閘道：一端點對接 268+ 供應商（50+ 免費），RTK+Caveman 壓縮省 15-95% tokens |
| 4 | [koala73/worldmonitor](https://github.com/koala73/worldmonitor) | TypeScript | 5,812 | 68.9K | 即時全球情報儀表板：AI 驅動新聞聚合、地緣政治監控、基礎設施追蹤 |
| 5 | [tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph) | Python | 5,639 | 25.3K | Local-first code intelligence graph for MCP / CLI，知識圖譜化理解 codebase |

---

## 2) 主題趨勢

1. **AI Agent 多模型路由與工具鏈標準化**：[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)（6,989 ⭐/wk，重返榜單）與 [MoonshotAI/kimi-cli](https://github.com/MoonshotAI/kimi-cli)（1,443 ⭐/wk）、[MoonshotAI/kimi-code](https://github.com/MoonshotAI/kimi-code)（1,400 ⭐/wk，首次進榜）構成「MoonshotAI CLI 雙編排」——Agent 底層從「單模型呼叫」全面轉向「多模型路由 + CLI 標準化」。

2. **反 AI-slop 設計運動持續領航**：[Nutlope/hallmark](https://github.com/Nutlope/hallmark)（8,471 ⭐/wk，連續 9+ 日在榜）與 [ibelick/ui-skills](https://github.com/ibelick/ui-skills)（2,206 ⭐/wk，▲+5.3%）分別代表「CSS 設計系統標準化」與「設計工程師技能庫」雙路線。當 AI 輸出泛濫，設計師／工程師反用 agent 對抗 agent 的運動已從個人工具進化為產業標準化。

3. **全球情報監控 + 3D 場景重建題材回歸**：[koala73/worldmonitor](https://github.com/koala73/worldmonitor)（5,812 ⭐/wk，時隔 3 週重返）與 [Robbyant/lingbot-map](https://github.com/Robbyant/lingbot-map)（4,250 ⭐/wk，時隔 ~2 週重返）同時回歸——即時地緣監控 + feed-forward 3D 場景重建，Agent 在國防/資訊/空間計算領域的滲透持續深化。

---

## 3) 值得追蹤專案

- **[tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph)** — Python，5,639 ⭐/wk，25.3K 總 ⭐。在榜第 3 日，連續穩定成長（07-20: 1,103 → 07-21: 3,073 → 07-22: 4,791 → 今日 5,639）。Local-first code intelligence graph——Agent 對 codebase 的理解正從「暴力檢索」轉向「知識圖譜化」，動能逐日攀升（07-22 → 今日 ▲+17.7%），是本輪最穩健的成長曲線。

- **[MoonshotAI/kimi-code](https://github.com/MoonshotAI/kimi-code)** — TypeScript，1,400 ⭐/wk，4.6K 總 ⭐。**首次進榜**。定位 "Kimi Code CLI — The Starting Point for Next-Gen Agents」，與 [MoonshotAI/kimi-cli](https://github.com/MoonshotAI/kimi-cli)（1,443 ⭐/wk，▲+11.5%）同時在榜——MoonshotAI 以「雙 CLI 編排」全面佈局 Agent 生態系，kimi-code 偏 TypeScript 上層應用、kimi-cli 偏 Python 底層運行時。

- **[koala73/worldmonitor](https://github.com/koala73/worldmonitor)** — TypeScript，5,812 ⭐/wk，68.9K 總 ⭐。**時隔 3 週重返**（上次出現在 06-30）。即時全球情報儀表板——地緣政治與 AI 新聞聚合的「資訊戰基礎設施」，在 6 月爆發後經歷 3 週沈寂，本次重返即空降 Top 5（#4），動能強勁。

- **[apache/ossie](https://github.com/apache/ossie)** — Python，810 ⭐/wk，1.5K 總 ⭐。**首次進榜**。Apache 基金會背書的語義 metadata 跨交換標準——vendor-neutral 的 analytics/AI/BI 平台「单一真相來源」。Apache 品牌在企業採用上的號召力 + 語義層標準化痛點，潛力可觀。

- **[1jehuang/jcode](https://github.com/1jehuang/jcode)** — Rust，2,293 ⭐/wk，10.7K 總 ⭐。連續 2 日在榜（07-22 首次進榜 1,769 → 今日 2,293 ▲+29.5%）。定位 "The most intelligent agent harness for code」——Rust 切入 agent 運行時賽道，動能加速中。

---

## 4) 歷史榜單比對

### 🆕 新進榜 repo（歷史全檔 0 記錄）

- **[MoonshotAI/kimi-code](https://github.com/MoonshotAI/kimi-code)**：TypeScript，1,400 ⭐/wk，4.6K 總 ⭐。首次進榜即搭配 kimi-cli 形成「雙 CLI 編排」。
- **[apache/ossie](https://github.com/apache/ossie)**：Python，810 ⭐/wk，1.5K 總 ⭐。Apache 基金會首個語義 metadata 標準化專案。
- **[schollz/croc](https://github.com/schollz/croc)**：Go，1,665 ⭐/wk，37.6K 總 ⭐。老牌檔案傳輸工具（Send things from one computer to another 🐊）首次進榜——在 Agent 時代「簡單可靠的跨設備傳輸」重新成為剛需。

### 🔁 重返榜單

- **[koala73/worldmonitor](https://github.com/koala73/worldmonitor)**：TypeScript，5,812 ⭐/wk，68.9K 總 ⭐。**時隔 3 週重返**（上次出現在 06-30，連 7 日後消失），本次重返即空降 Top 5（#4）。
- **[Robbyant/lingbot-map](https://github.com/Robbyant/lingbot-map)**：Python，4,250 ⭐/wk，14.9K 總 ⭐。**時隔 ~2 週重返**（上次出現在 07-06）。前馈式 3D 基礎模型從串流資料重建場景。
- **[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)**：TypeScript，6,989 ⭐/wk，25.2K 總 ⭐。**相隔 1 天重返**（07-22 未在榜，07-23 回到 Top 5）。

### 📈 成長異常

- **[tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph)**：07-22 4,791 → 今日 5,639 ▲+17.7%，4 日累積 ▲+412%（從 07-20 的 1,103 起算）。
- **[1jehuang/jcode](https://github.com/1jehuang/jcode)**：07-22 1,769 → 今日 2,293 ▲+29.5%。
- **[MoonshotAI/kimi-cli](https://github.com/MoonshotAI/kimi-cli)**：07-22 1,294 → 今日 1,443 ▲+11.5%。
- **[earendil-works/pi](https://github.com/earendil-works/pi)**：07-22 3,569 → 今日 4,060 ▲+13.8%。
- **[ibelick/ui-skills](https://github.com/ibelick/ui-skills)**：07-22 2,094 → 今日 2,206 ▲+5.3%。

### ⬇️ 動能降溫

- **[OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut)**：07-22 8,341 → 今日 7,394 ▼-11.4%。連 9+ 日在榜，但動能明顯降溫。
- **[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)**：07-22 4,047 → 今日 3,579 ▼-11.6%。
- **[Nutlope/hallmark](https://github.com/Nutlope/hallmark)**：07-22 8,948 → 今日 8,471 ▼-5.3%。
- **[openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter)**：07-22 2,205 → 今日 2,025 ▼-8.2%。

### 🔁 連續上榜（長期跑者）

- **[Nutlope/hallmark](https://github.com/Nutlope/hallmark)**：連續 9+ 日在榜（07-15 起）。
- **[OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut)**：連續 9+ 日在榜。
- **[HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor)**：3,030 ⭐/wk，29.1K 總 ⭐。穩定在 full list，連續多日在榜。

---

*報告由 OpenClaw cron 自動生成，歷史比對範圍 05-23 ~ 07-22。*
