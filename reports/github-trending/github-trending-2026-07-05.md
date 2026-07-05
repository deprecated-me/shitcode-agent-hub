# GitHub Trending Weekly — 2026-07-05（日）

**資料來源**：[GitHub Trending Weekly](https://github.com/trending?since=weekly)

---

## 1) 今日 Top 5

| # | 專案 | 語言 | 本週 Stars |
|---|------|------|-----------|
| 1 | [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) | C | 9,517 |
| 2 | [usestrix/strix](https://github.com/usestrix/strix) | Python | 9,362 |
| 3 | [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) | Python | 8,447 |
| 4 | [xbtlin/ai-berkshire](https://github.com/xbtlin/ai-berkshire) | Python | 5,984 |
| 5 | [simplex-chat/simplex-chat](https://github.com/simplex-chat/simplex-chat) | Haskell | 4,630 |

**觀察**：Top 5 與昨日完全一致（相同 5 個 repo），但本週 Stars 普遍下移。值得注意的是 [usestrix/strix](https://github.com/usestrix/strix) 逆勢成長 ▲+23.7%（7,567 → 9,362），正式超越 [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) 升至第二名。

---

## 2) 主題趨勢

- **AI Agent 生態系持續主導**：Top 5 全為 AI Agent 相關（滲透測試 Agent、程式碼記憶 MCP、影片製作 Agent、投資研究 Agent），整個 trending 清單超過 60% 是 Agent 應用或基礎設施。Agent 已從概念驗證轉向大規模工具鏈整合，涵蓋影片、投資、資安、網站複製等垂直場域。
- **AI 內容創作工具鏈細分化**：[calesthio/OpenMontage](https://github.com/calesthio/OpenMontage)（Agentic 影片製作）領軍，搭配新進榜的 [browser-use/video-use](https://github.com/browser-use/video-use)（coding agent 影片編輯，4,174 stars）與先前的 [ai-website-cloner-template](https://github.com/JCodesMore/ai-website-cloner-template)（AI 網站複製，3,730 stars），形成程式碼、影片、網站三位一體的 AI 自動化產線。
- **AI 閘道與多模型路由需求爆發**：[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)（4,133 stars）單一端點支援 231+ 供應商，[stablyai/orca](https://github.com/stablyai/orca)（3,790 stars）提供本地 Agent 開發環境。開發者對多模型並用、成本優化的需求持續攀升。
- **隱私與去中心化韌性需求**：[simplex-chat/simplex-chat](https://github.com/simplex-chat/simplex-chat) 四度上榜，[Starmel/OpenSuperWhisper](https://github.com/Starmel/OpenSuperWhisper)（macOS 本地語音轉文字，499 stars）首次進榜，反映 AI 資料濫用疑慮下，本地端 / 隱私強化工具穩定吸引特定族群。
- **OpenAI 跨足 Agent 互操作**：[openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc)（1,974 stars）讓 Codex 與 Claude Code 互通，打破過去各模型 Agent 的孤島狀態，促進跨平台協作。

---

## 3) 值得追蹤專案

- [browser-use/video-use](https://github.com/browser-use/video-use) — Python，4,174 stars/week。**首次進榜**：讓coding agent 直接編輯影片，補足 OpenMontage pipeline 中「後製剪辑」的細分工具，browser-use 生態系橫向擴展能力值得觀察。
- [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) — TypeScript，4,133 stars/week。免費 AI 閘道，231+ 供應商（50+ 免費）、RTK+Caveman 疊加壓縮節省 15–95% tokens。多模型路由與成本優化痛點明確，持續成長動能強。
- [ogulcancelik/herdr](https://github.com/ogulcancelik/herdr) — Rust，3,506 stars/week。Agent multiplexer 進終端機background協作。Rust 實作提供效能優勢，在 Agent 編排市場中走輕量化路線。
- [interviewstreet/hiring-agent](https://github.com/interviewstreet/hiring-agent) — Python，1,647 stars/week。**首次進榜**：AI agent 評估與評分履歷。人力資源 × AI Agent 的新垂直應用，市場需求明確但競爭者眾，需注意後續黏著度。
- [allenai/olmocr](https://github.com/allenai/olmocr) — Python，1,229 stars/week。**首次進榜**：PDF linearization 工具包，為 LLM 訓練資料預處理。學術研究驅動的開源工具，顯示 AI 基礎設施的開發正向上游（資料層）延伸。

---

## 4) 進榜 / 連續 / 成長比對

**歷史資料來源**：[github-trending-2026-07-04](github-trending-2026-07-04.md)、[github-trending-2026-07-03](github-trending-2026-07-03.md)、[github-trending-2026-07-02](github-trending-2026-07-02.md)

### 連續在榜

| Repo | 07-02 | 07-03 | 07-04 | 07-05 | 趨勢 |
|------|-------|-------|-------|-------|------|
| [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) | 9,697 | 9,873 | 10,186 | 9,517 | ▼ -6.7%，自 06-18 連續超過 2 週 |
| [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) | 12,624 | 10,199 | 9,213 | 8,447 | ▼ -8.3%，自 06-22 連續 13 天 |
| [usestrix/strix](https://github.com/usestrix/strix) | — | 7,567 | 7,567 | 9,362 | ▲ +23.7%，**成長異常** |
| [xbtlin/ai-berkshire](https://github.com/xbtlin/ai-berkshire) | 6,758 | 6,989 | 6,230 | 5,984 | ▼ -3.9%，持平 |
| [simplex-chat/simplex-chat](https://github.com/simplex-chat/simplex-chat) | — | 6,376 | 5,971 | 4,630 | ▼ -22.5%，間歇性需求 |
| [stablyai/orca](https://github.com/stablyai/orca) | 频繁 | 频繁 | 3,790 | 3,790 | 持平 |
| [alibaba/page-agent](https://github.com/alibaba/page-agent) | 1,451 | 1,451 | 2,484 | 2,484 | 持平 |
| [JCodesMore/ai-website-cloner-template](https://github.com/JCodesMore/ai-website-cloner-template) | 频繁 | 频繁 | 3,730 | 3,730 | 持平 |
| [logto-io/logto](https://github.com/logto-io/logto) | — | — | 1,488 | 1,488 | 持平 |
| [topoteretes/cognee](https://github.com/topoteretes/cognee) | — | 4,001 | 3,388 | 3,388 | 持平 |
| [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis) | 频繁 | — | 3,842 | 3,842 | 持平 |

### 新進榜（首次出現在 trending 清單）

- [browser-use/video-use](https://github.com/browser-use/video-use) — 4,174 stars，browser-use 生態從網頁擴展至影片後製
- [Starmel/OpenSuperWhisper](https://github.com/Starmel/OpenSuperWhisper) — 499 stars，macOS 本地語音轉文字，低門檻但顯示隱私工具穩定需求
- [interviewstreet/hiring-agent](https://github.com/interviewstreet/hiring-agent) — 1,647 stars，AI 人資評估 agent
- [allenai/olmocr](https://github.com/allenai/olmocr) — 1,229 stars，LLM 訓練資料預處理工具

### 掉出榜單（前日在榜、今日未見）

- [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) — 07-04 仍在，今日不見
- [google-labs-code/design.md](https://github.com/google-labs-code/design.md) — 07-02 Top 5，持續下滑後跌出
- [jamiepine/voicebox](https://github.com/jamiepine/voicebox) — 07-04 列在追蹤專案，今日不見
- [mauriceboe/TREK](https://github.com/mauriceboe/TREK) — 07-03 曾單日進榜，回到休眠
- [mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) — 07-02 曾上榜
- [kunchenguid/no-mistakes](https://github.com/kunchenguid/no-mistakes) — 07-02 曾上榜

### 成長異常

> ⚠️ [usestrix/strix](https://github.com/usestrix/strix)：昨日 7,567 → 今日 9,362（**▲ +23.7%**），為近 4 日所有 Top 5 專案中唯一一家呈現「加速成長」趨勢者，AI 滲透測試領域需求正在爆發。
