# GitHub 本週熱門專案 — 2026-07-08（週三）

## 1) 今日 Top 5（repo、語言、本週 stars）

| # | Repo | 語言 | 本週 Stars | 簡介 |
|---|------|------|-----------|------|
| 1 | [usestrix/strix](https://github.com/usestrix/strix) | Python | 10,741 | 開源 AI 滲透測試工具，自動發現並修復應用程式漏洞 |
| 2 | [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) | Rust | 7,349 | 100% 本地 AI 會議記錄助手，4x 加速 Parakeet/Whisper 逐字稿 + Ollama 摘要 |
| 3 | [hasaneyldrm/exercises-dataset](https://github.com/hasaneyldrm/exercises-dataset) | HTML | 4,950 | 433 筆健身動作資料集，含目標肌群、器材、教學圖/影片 |
| 4 | [ogulcancelik/herdr](https://github.com/ogulcancelik/herdr) | Rust | 4,557 | Agent multiplexer —— 在 terminal 背景同時跑多個 agent |
| 5 | [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) | TypeScript | 4,797 | 單端點 AI 閘道：231+ 模型供應商、RTK+Caveman 疊加壓縮省 15–95% tokens |

> 本週 Top 5 中，AI Agent 相關佔 4 席（strix 滲透測試、meetily 本地 AI 會議記錄、herdr agent 多工、OmniRoute 多模型路由）。[hasaneyldrm/exercises-dataset](https://github.com/hasaneyldrm/exercises-dataset) 是唯一非 AI 核心專案，以結構化健身資料集殺入前五，反映開源資料集的長尾需求。與昨日相比，Top 5 大洗牌——[JuliuBrussee/caveman](https://github.com/JuliusBrussee/caveman)與[DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)同時跌出前段。

## 2) 主題趨勢

- **AI Agent 生態系全面爆發，應用場域全面滲透**：從[usestrix/strix](https://github.com/usestrix/strix)（滲透測試）、[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)（本地 AI 會議記錄）、[xbtlin/ai-berkshire](https://github.com/xbtlin/ai-berkshire)（AI 價值投資研究），到[ogulcancelik/herdr](https://github.com/ogulcancelik/herdr)（agent 多工）、[stablyai/orca](https://github.com/stablyai/orca)（fleet IDE 管控），排行榜上過半專案圍繞 AI Agent。在不同專業領域內，Agent 已從概念驗證過渡到大規模工具鏈整合。

- **Token 成本優化與多模型路由成為剛需**：[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)（單一端點驅動 231+ 供應商）的 RTK+Caveman 疊加壓縮（省 15–95% tokens）持續在榜，搭配[JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)（穴居人 prompt 法省 65% tokens），回應了 Agent 部署的核心成本痛點。[ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) 讓 coding agent 直接操縱瀏覽器，也降低了 UI 自動化成本。

- **隱私優先與端側 AI 韌性需求穩定成長**：[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)（完全本地 AI 會議記錄，本週從 #4→#2，+27.4% 增長）搭配[altic-dev/FluidVoice](https://github.com/altic-dev/FluidVoice)（macOS 本地 StT）與[huggingface/speech-to-speech](https://github.com/huggingface/speech-to-speech)（開源本地語音 agent），在 AI 監控與資料外洩疑慮下，privacy-first 工具持續吸引特定族群。

- **跨 Agent 互操作成為新戰場**：[openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc)（4,725 stars/week）讓 Codex 在 Claude Code 裡搭檔工作；[MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search)（5,363 stars/week，**首次出現在歷史報告中**）則將 AI agent 用于求職流程——評測職缺、客製 CV、撰寫 Cover Letter、模擬面試。Agent 從「工程師的生产力工具」正式擴散到一般用戶的日常流程。

## 3) 值得追蹤專案

1. **[MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search)** — TypeScript，5,363 stars/week，**歷史檔案 0 記錄，首次進榜**。基於 Claude Code 的 AI 求職框架：填 profile → 自動評測職缺 → 客製 CV + Cover Letter → 模擬面試。Agent 應用從工程師族群正式跨越到大眾市場。

2. **[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)** — Rust，7,349 stars/week，自 07-06 進榜以來本週排名翻倍（#4 → #2），增長 +27.4%。隱私優先 + 完全本地 AI 會議記錄的明確定位，在 Zoom/Notion AI 壟斷市場中走差異化路線。

3. **[JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)** — JavaScript，8,066 stars/week，雖然自昨日 #2 跌出 Top 5（本日 full list），動能極強。穴居人 prompt 法（「why use many token when few token do trick」）簡單粗暴但极其有效，歷史累積總 stars 已達 86,260。若榜單震盪回穩，將重返前段。

4. **[DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)** — C，5,457 stars/week，自 06-18 起連續超過 3 週在榜，本日從 Top 5 跌出（昨日 #3 → full list），但基本面仍在。Knowledge graph 索引 codebase 作為 Agent 基礎建設關鍵層，158 語言、sub-ms 查詢，可持續觀察企穩訊號。

5. **[alibaba/page-agent](https://github.com/alibaba/page-agent)** — TypeScript，4,163 stars/week，自 06-28 起連續在榜超過 2 週。阿里開源的 in-page GUI agent，對 Web agent 標準化具備風向意義——大廠的參與會加速生態成熟。

## 4) 歷史比對

### 新進榜 / 今日首次出現在歷史報告

- **[MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search)** — 歷史檔案 0 記錄，首次進榜，5,363 stars/week。Agent 求職框架，擴散到大眾市場的首個指標性專案。

### 連續上榜專案

- **[usestrix/strix](https://github.com/usestrix/strix)** — 自 07-04 起連續 5 日在榜。本週略降（10,759 → 10,741，▼ -0.2%），仍唯一破萬門檻專案。
- **[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)** — 自 07-03 起連續 6 天在榜。
- **[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)** — 自 07-06 起連續 3 天在榜，且排名與動能持續攀升。
- **[alibaba/page-agent](https://github.com/alibaba/page-agent)** — 自 06-28 起連續 11 天在榜（含 full list），最長壽項目。
- **[DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)** — 自 06-18 起連續超過 3 週在榜，今日略跌出 Top 5 但仍在 full list。

### 掉出 Top 5（full list 仍在榜）

- **[JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)** — 昨日 #2（7,780）→ 今日掉出 Top 5，但 full list 記錄 8,066 stars/week（▲ +3.7%），排名震盪而非衰退。
- **[DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)** — 昨日 #3（6,309）→ 今日 full list 記錄 5,457 stars/week（▼ -13.5%），若能企穩則屬正常波動。

### 成長異常

- **[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)**：本日最強增幅，從昨日 #4（5,769）→ 今日 #2（7,349，▲ +27.4%），為本週最高成長率。隱私工具市場需求持續爆發。
- **[MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search)**：首次進榜即 5,363 stars/week，面向大眾求職市場，潛力值得觀察。
- **[ogulcancelik/herdr](https://github.com/ogulcancelik/herdr)**：持續在 full list，累積動能中，本日進入 top 5（#4），自 07-03 起已穩定 6 天。

---

**資料來源**：[GitHub Trending (weekly)](https://github.com/trending?since=weekly)，抓取時間 2026-07-08 08:00 CST
**歷史比對範圍**：`reports/github-trending/` 全檔（45 份，2026-05-23 至今），以 `rg -F <repo>` 精確比對。
