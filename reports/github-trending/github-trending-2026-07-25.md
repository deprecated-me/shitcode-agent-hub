# GitHub Weekly Trending — 2026-07-25（週六）

> 資料來源：[GitHub Trending Weekly](https://github.com/trending?since=weekly)，抓取時間 2026-07-25 20:36 CST。
> `web_fetch` 透過 readability 萃取約 19 個 repo（GitHub Trending 通常 25 個），[mattpocock/skills](https://github.com/mattpocock/skills) 出現在頁面但 star/本週數據未完整擷取。
> 歷史比對使用 `rg -F` 精確匹配完整 repo 名，比對 60+ 份歷史報告（05-23 ~ 07-24）。

---

## 1) 今日 Top 5

| # | Repo | 語言 | 本週 ⭐ | 總 ⭐ | 敘述 |
|---|------|------|---------|--------|------|
| 1 | [bojieli/ai-agent-book](https://github.com/bojieli/ai-agent-book) | Python | 19,519 | 21.4K | 《深入理解 AI Agent：设计原理与工程实践》開源主倉庫，全書正文 + 編譯版 PDF + 按章配套代碼 |
| 2 | [koala73/worldmonitor](https://github.com/koala73/worldmonitor) | TypeScript | 10,936 | 73.8K | 即時全球情報儀表板：AI 驅動新聞聚合、地緣政治監控、基礎設施追蹤 |
| 3 | [tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph) | Python | 6,565 | 26.3K | Local-first code intelligence graph for MCP / CLI，知識圖譜化理解 codebase |
| 4 | [1jehuang/jcode](https://github.com/1jehuang/jcode) | Rust | 2,773 | 11.3K | "The most intelligent agent harness for code"——Rust 切入 agent 運行時賽道 |
| 5 | [agegr/pi-web](https://github.com/agegr/pi-web) | TypeScript | 1,316 | 2.7K | Web UI for the pi coding agent |

---

## 2) 主題趨勢

1. **AI Agent 教材與知識圖譜化雙重爆發**：[bojieli/ai-agent-book](https://github.com/bojieli/ai-agent-book)（19,519 ⭐/wk，歷史首次進榜即空降 #1）與 [tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph)（連續 5 日在榜，07-20 → 今日穩定攀升）領跑——Agent 從「工具躍進」進入「系統化教育 + 結構化理解」階段。

2. **多模型路由與 CLI 工具鏈持續發燒**：[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)（9,965 ⭐/wk，▲+42.6%）、[stablyai/orca](https://github.com/stablyai/orca)（7,245 ⭐/wk，▲+26.4%）、[MoonshotAI/kimi-code](https://github.com/MoonshotAI/kimi-code)（1,589 ⭐/wk）與 [MoonshotAI/kimi-cli](https://github.com/MoonshotAI/kimi-cli)（1,570 ⭐/wk）構成「多模型閘道 + 並行 agent 管理 + CLI 標準化」三位一體——Agent 底層設施全面成熟化。

3. **邊緣 AI / 隱私感知題材回歸**：[jamiepine/voicebox](https://github.com/jamiepine/voicebox)（4,493 ⭐/wk，時隔 23 天重返）、[ruvnet/RuView](https://github.com/ruvnet/RuView)（4,821 ⭐/wk，時隔 ~2 週重返）、[agegr/pi-web](https://github.com/agegr/pi-web)（1,316 ⭐/wk，首次進榜）同時出現——邊緣感知 + 本地 AI + Agent UI 三線匯流。

4. **反 AI-slop 設計運動動能降溫**：[Nutlope/hallmark](https://github.com/Nutlope/hallmark)（4,978 ⭐/wk，從 #1 8,471 降至 #10，▼-41.2%）與 [OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut)（前日 #2 7,394，今日完全退出榜單）同時退潮——設計標準化題材從爆發期進入沈澱期。

---

## 3) 值得追蹤專案

- **[bojieli/ai-agent-book](https://github.com/bojieli/ai-agent-book)** — Python，19,519 ⭐/wk，21.4K 總 ⭐。**歷史全檔 0 記錄，首次進榜即空降 #1**。李博傑著作《深入理解 AI Agent》開源主倉庫，全書正文 + 編譯版 PDF + 按章配套代碼。19,519 ⭐/wk 是近 2 週榜單最高週星數，反映開發者對「系統化 Agent 教材」的強烈需求。

- **[stablyai/orca](https://github.com/stablyai/orca)** — TypeScript，7,245 ⭐/wk，28.7K 總 ⭐。**相隔 1 天重返 full list 即飆出 7,245 高標**（07-22 5,733 → 今日 7,245 ▲+26.4%）。Orca 是 ADE（Agent Development Environment）平台，支援用自有訂閱管理多 agent 艦隊——Agent 走向實際產品化的標桿，動能重返加速。

- **[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)** — TypeScript，9,965 ⭐/wk，29.5K 總 ⭐。**相隔 1 天重返後即創近期高點**（07-23 6,989 → 今日 9,965 ▲+42.6%）。一端點對接 290+ 供應商（90+ 免費），RTK+Caveman 壓縮省 15-95% tokens，MCP/A2A 全協議支援——多模型路由基礎設施的領頭羊。

- **[ruvnet/RuView](https://github.com/ruvnet/RuView)** — Rust，4,821 ⭐/wk，86.2K 總 ⭐。**時隔 ~2 週重返**（上次出現在 07-14 報告）。WiFi 訊號即時空間感測 + 生命體徵監測 + 存在偵測，**零像素純 RF 感測**的設計哲學在 edge AI 赛道具獨特定位。老牌長青專案再次回榜反映 edge sensing 需求穩定存在。

- **[jamiepine/voicebox](https://github.com/jamiepine/voicebox)** — TypeScript，4,493 ⭐/wk，46.6K 總 ⭐。**時隔 23 天重返**（上次出現在 07-02）。開源 AI 語音工作室，支援語音克隆、口述與創建。Agent 時代「語音介面」重新成為焦點，voicebox 作為老牌專案重返榜單，反映語音互動需求回溫。

---

## 4) 歷史榜單比對

### 🆕 新進榜 repo（歷史全檔 0 記錄）

- **[bojieli/ai-agent-book](https://github.com/bojieli/ai-agent-book)**：Python，19,519 ⭐/wk，21.4K 總 ⭐。首次進榜即空降 #1，創近 2 週單週星數最高紀錄。
- **[agegr/pi-web](https://github.com/agegr/pi-web)**：TypeScript，1,316 ⭐/wk，2.7K 總 ⭐。Web UI for the pi coding agent，與 [earendil-works/pi](https://github.com/earendil-works/pi) 構成「Agent 引擎 + Web 前端」雙編排。
- **[Pumpkin-MC/Pumpkin](https://github.com/Pumpkin-MC/Pumpkin)**：Rust，1,279 ⭐/wk，9.5K 總 ⭐。開源 Minecraft 伺服器，首次進榜。
- **[every-app/open-seo](https://github.com/every-app/open-seo)**：TypeScript，3,309 ⭐/wk，7.8K 總 ⭐。Semrush/Ahrefs 開源替代方案，首次進榜。
- **[hyprwm/Hyprland](https://github.com/hyprwm/Hyprland)**：C++，724 ⭐/wk，37.4K 總 ⭐。獨立動態平鋪 Wayland compositor，首次進榜。
- **[ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)**：Python，1,997 ⭐/wk，70.3K 總 ⭐。Claude Skills 精選資源庫，首次進榜。

### 🔁 重返榜單

- **[ruvnet/RuView](https://github.com/ruvnet/RuView)**：Rust，4,821 ⭐/wk，86.2K 總 ⭐。**時隔 ~2 週重返**（上次出現在 07-14 報告）。
- **[jamiepine/voicebox](https://github.com/jamiepine/voicebox)**：TypeScript，4,493 ⭐/wk，46.6K 總 ⭐。**時隔 23 天重返**（上次出現在 07-02 報告，自 06-27 起連續 6 天在榜後消失）。
- **[rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch)**：Python，4,399 ⭐/wk，43.3K 總 ⭐。**時隔 ~2 個月重返**（上次出現在 05-31 報告，自 05-25 起連 7 天留榜）。

### 📈 成長異常

- **[koala73/worldmonitor](https://github.com/koala73/worldmonitor)**：07-23 5,812 → 今日 10,936 ▲+88.2%，單日翻倍成長，動能暴發。
- **[schollz/croc](https://github.com/schollz/croc)**：07-23 1,665 → 今日 2,647 ▲+58.9%，老牌檔案傳輸工具加速爆發。
- **[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)**：07-23 6,989 → 今日 9,965 ▲+42.6%。
- **[stablyai/orca](https://github.com/stablyai/orca)**：07-22 5,733 → 今日 7,245 ▲+26.4%。
- **[earendil-works/pi](https://github.com/earendil-works/pi)**：07-23 4,060 → 今日 4,880 ▲+20.2%。
- **[tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph)**：07-23 5,639 → 今日 6,565 ▲+16.4%，連續 5 日穩定攀升。

### ⬇️ 動能降溫

- **[Nutlope/hallmark](https://github.com/Nutlope/hallmark)**：07-23 8,471 → 今日 4,978 ▼-41.2%，從 #1 跌至 #10。
- **[OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut)**：07-23 #2 7,394 → **今日完全退出榜單**，連 9+ 日在榜後中斷。
- **[ibelick/ui-skills](https://github.com/ibelick/ui-skills)**：07-23 2,206 → 今日 1,691 ▼-23.3%。

### 🔁 連續上榜（長期跑者）

- **[tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph)**：連續 5 日在榜（07-20 → 今日），累積 ▲+494%（從 07-20 1,103 起算）。
- **[Nutlope/hallmark](https://github.com/Nutlope/hallmark)**：連續 10+ 日在榜（07-15 起），但動能明顯降溫。
- **[1jehuang/jcode](https://github.com/1jehuang/jcode)**：連續 3 日在榜（07-22 → 今日），07-22 1,769 → 今日 2,773 ▲+56.7%。
- **[earendil-works/pi](https://github.com/earendil-works/pi)**：連續 2 日在榜（07-23 → 今日），穩定攀升。
- **[MoonshotAI/kimi-code](https://github.com/MoonshotAI/kimi-code)**：連續 2 日在榜（07-23 → 今日），穩定成長。
- **[MoonshotAI/kimi-cli](https://github.com/MoonshotAI/kimi-cli)**：連續 2 日在榜（07-23 → 今日），穩定成長。

---

*報告由 OpenClaw cron 自動生成，歷史比對範圍 05-23 ~ 07-24。*
