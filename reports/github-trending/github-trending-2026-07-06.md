# GitHub Trending Weekly — 2026-07-06（一）

**資料來源**：[GitHub Trending Weekly](https://github.com/trending?since=weekly)

---

## 1) 今日 Top 5

| # | 專案 | 語言 | 本週 Stars |
|---|------|------|-----------|
| 1 | [usestrix/strix](https://github.com/usestrix/strix) | Python | 10,338 |
| 2 | [xbtlin/ai-berkshire](https://github.com/xbtlin/ai-berkshire) | Python | 5,038 |
| 3 | [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) | TypeScript | 4,411 |
| 4 | [simplex-chat/simplex-chat](https://github.com/simplex-chat/simplex-chat) | Haskell | 3,572 |
| 5 | [Robbyant/lingbot-map](https://github.com/Robbyant/lingbot-map) | Python | 1,875 |

**觀察**：本日榜單震盪劇烈——昨日 Top 5 中有兩本週落入榜外（calesthio/OpenMontage、DeusData/codebase-memory-mcp）。[usestrix/strix](https://github.com/usestrix/strix)（AI 滲透測試）登基第一，自 07-04 起連續四日顯示加速成長。[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) 一口氣衝上第三，[Robbyant/lingbot-map](https://github.com/Robbyant/lingbot-map) 擠進第五，榜單洗牌顯著。

---

## 2) 主題趨勢

- **AI Agent 滲透測試需求井噴**：[usestrix/strix](https://github.com/usestrix/strix) 穩居寶座，本週獨拿 10,338 stars，是唯一週破萬的專案。AI 時代弱點掃描從傳統工具轉向「Agentic AppSec」——agent 自動發現 + 自動修復，strix 將這流程做成一條龍。同時資安領域老牌 [cognee](https://github.com/topoteretes/cognee)（AI agent 記憶平台，2,699 stars）持續榜單，反映 Agent 衍生需求是全方位。
- **多模型閘道與 Agent 編排作戰化**：[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)（單一端點驅動 231+ 供應商，4,411 stars）搭配 [stablyai/orca](https://github.com/stablyai/orca)（agent fleet 管理 IDE，3,783 stars），證明多模型混用與 agent 編排已成剛需而非噱頭。OmniRoute 的 RTK+Caveman 疊加壓縮（省 15–95% tokens）具體回應了 agent 開發的成本痛點。
- **隱私工具與端側 AI 韌性需求**：[simplex-chat/simplex-chat](https://github.com/simplex-chat/simplex-chat)（100% 匿名通訊，3,572 stars）繼昨日本週再次榜單，另新增 [meetily](https://github.com/Zackriya-Solutions/meetily)（完全本地 AI 會議記錄，2,972 stars）進榜。在 AI 監控、資料外洩疑慮下，privacy-first 工具每次進榜代表真實市場區隔需求。
- **OpenAI 發動跨 Agent 互操作**：[openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc)（3,405 stars）讓 Codex 在 Claude Code 裡搭檔工作，正面打破過去 AI coding agent 孤島。此一「跨平台 agent 橋接」的轉變，比單一 Agent 成就更值得長期關注。

---

## 3) 值得追蹤專案

- [ogulcancelik/herdr](https://github.com/ogulcancelik/herdr) — Rust，3,937 stars/week。Agent multiplexer 直接在 terminal 背景運行多 agent 協作，Rust 實作追求極致效能。在 Agent 數量暴增的環境中，「agent 背景化、工程師不切換視窗」的設計哲學是關鍵差異化。
- [browser-use/video-use](https://github.com/browser-use/video-use) — Python，4,288 stars/week。coding agent 直接編輯影片，browser-use 生態系從網頁自動化橫向入侵影音後製。與 OpenMontage 一前一後，Agentic 影片生產管線日趨完整。
- [stablyai/orca](https://github.com/stablyai/orca) — TypeScript，3,783 stars/week。定位為「fleet 級 ADE」，讓工程師在本機端同時跑多個 coding agent。Desktop + Mobile 雙平台支援，是 agent 工具從 Web 走向終端的指標性產品。
- [alibaba/page-agent](https://github.com/alibaba/page-agent) — TypeScript，3,151 stars/week。JavaScript 原生的 in-page GUI agent，用自然語言操控網頁介面。阿里開源對於 Web agent 標準化具備風向意義——大廠的參與會加速生態成熟。
- [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) — Rust，2,972 stars/week。**本日首次出現在歷史報告中唯一一個從未出現的新 repo**。隱私優先 + 100% 本地 AI 會議記錄 + 4x 加速 Parakeet/Whisper 逐字稿 + Ollama 摘要。在隱私軟體與端側 AI 的交叉市場中走出鮮明定位。

---

## 4) 進榜 / 連續 / 成長比對

**歷史資料來源**：[github-trending-2026-07-05](github-trending-2026-07-05.md)、[github-trending-2026-07-04](github-trending-2026-07-04.md)、[github-trending-2026-07-03](github-trending-2026-07-03.md)

### 升級入榜（本次首次進入 Top 5）

| Repo | 07-05 排名 | 07-06 排名 | 07-05 本週 Stars | 07-06 本週 Stars | 趨勢 |
|------|-----------|-----------|-----------------|-----------------|------|
| [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) | Top 5 外 | #3 | 4,133 | 4,411 | ▲ +6.7%，連續兩日回榜單後終於攻入 TOP 5 |
| [Robbyant/lingbot-map](https://github.com/Robbyant/lingbot-map) | Top 5 外 | #5 | 1,875 | 1,875 | 持平，僅 07-03 歷史曾上榜，屬於間歇性 |

### 掉出 Top 5（仍在 full list 中但排名下降）

| Repo | 07-05 排名 | 07-05 本週 Stars | 07-06 本週 Stars | 趨勢 |
|------|-----------|-----------------|-----------------|------|
| [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) | #1 | 9,517 | 7,945 | ▼ -16.5%，降至 #6 |
| [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) | #3 | 8,447 | 7,353 | ▼ -13.0%，降至 #11 |

> 備註：DeusData 與 OpenMontage 從 06-18 以來長期佔據前段班，本週雙雙跌出 Top 5。若本週頹勢持續，下週將轉為觀察訊號。

### Tier 2 _repo 動向（full list 內非 Top 1-5）

| Repo | 07-05 | 07-06 | 趨勢 | 狀態 |
|------|-------|-------|------|------|
| [simplex-chat/simplex-chat](https://github.com/simplex-chat/simplex-chat) | #5, 4,630 | #4, 3,572 | ▼ -22.8% | 連續數日，但成長萎縮 |
| [browser-use/video-use](https://github.com/browser-use/video-use) | -, 4,174 | -, 4,288 | ▲ +2.7% | 穩定 |
| [stablyai/orca](https://github.com/stablyai/orca) | -, 3,790 | -, 3,783 | ▼ -0.2% | 持平 |
| [JCodesMore/ai-website-cloner-template](https://github.com/JCodesMore/ai-website-cloner-template) | -, 3,730 | -, 3,246 | ▼ -13.0% | 小幅下滑 |
| [topoteretes/cognee](https://github.com/topoteretes/cognee) | -, 3,388 | -, 2,699 | ▼ -20.3% | 下跌 |
| [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis) | -, 3,842 | -, 3,806 | ▼ -0.9% | 持平 |

### 歷史從未出現的 repo

> 以下 repo 在本報告的歷史檔案（05-23 至今共 43 份）中從未出現過——本日首次進榜：

- [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) — Rust，2,972 stars/week：隱私優先 + 本地端 AI 會議記錄助手，Parakeet/Whisper 4x 加速逐字稿 + Ollama 摘要。新進榜即進 full list Top 8，力道足夠。
- [apache/maven](https://github.com/apache/maven) — Java，173 stars/week：知名 Java build tool 間歇性進榜，本週回升。低 star count 但顯示仍有社群關注。

### 成長異常

- ⚠️ [usestrix/strix](https://github.com/usestrix/strix)：連續 4 日成長——07-03 7,567 → 07-04 7,567 → 07-05 9,362 → 07-06 10,338。本日本週 stars 正式突破 10,000 門檻，AI 滲透測試領域需求量級可能正進入爆發期。07-05 相對 07-04 ▲ +23.7%，本日相對 07-05 ▲ +10.4%，為所有亮點項目中動能最強者。
- ⚠️ [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)：本日 Top 5 新成員，相對 07-05 ▲ +6.7%，AI 多模型路由市場需求持續上揚。
