# GitHub 本週熱門專案 — 2026-07-07（週二）

## 1) 今日 Top 5（repo、語言、本週 stars）

| # | Repo | 語言 | 本週 Stars | 簡介 |
|---|------|------|-----------|------|
| 1 | [usestrix/strix](https://github.com/usestrix/strix) | Python | 10,759 | 開源 AI 滲透測試工具，自動發現並修復應用程式漏洞 |
| 2 | [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) | JavaScript | 7,780 | Claude Code token 節省 65%，用穴居人語法寫 prompt |
| 3 | [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) | C | 6,309 | Codebase knowledge graph 索引，158 語言、sub-ms 查詢、99% token 減少 |
| 4 | [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) | Rust | 5,769 | 100% 本地 AI 會議記錄助手，4x 加速 Parakeet/Whisper 逐字稿 + Ollama 摘要 |
| 5 | [hasaneyldrm/exercises-dataset](https://github.com/hasaneyldrm/exercises-dataset) | HTML | 5,665 | 433 筆健身動作資料集，含名稱、類別、目標肌群、器材、教學圖/影片 |

> 本週Top 5 中，AI Agent 相關佔 3 席（strix 滲透測試、codebase-memory-mcp 知識層、caveman token 優化）。[hasaneyldrm/exercises-dataset](https://github.com/hasaneyldrm/exercises-dataset) 是唯一非 AI 核心的項目，以結構化健身資料集殺入前五，反映開源資料集的長尾需求。

## 2) 主題趨勢

- **AI Agent 生態系全面爆發**：從應用場域（[usestrix/strix](https://github.com/usestrix/strix) 滲透測試、[xbtlin/ai-berkshire](https://github.com/xbtlin/ai-berkshire) 投資研究、[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) 會議記錄），到基礎建設（[DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) 持久記憶體、[ogulcancelik/herdr](https://github.com/ogulcancelik/herdr) agent 多工、[stablyai/orca](https://github.com/stablyai/orca) fleet IDE），排行榜上過半專案围绕 AI Agent。Agent 已從概念驗證過渡到大規模工具鏈整合。

- **Token 成本優化與多模型路由成為剛需**：[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)（單一端點驅動 231+ 供應商，RTK+Caveman 疊加壓縮省 15–95% tokens）搭配 [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)（穴居人 prompt 法省 65% tokens），回應了 Agent 部署中的核心成本痛點。[ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) 讓 coding agent 直接操縱瀏覽器，也降低了 UI 自動化成本。

- **隱私優先與端側 AI 韌性需求穩定成長**：[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)（完全本地 AI 會議記錄，07-06 首次進榜即飆 5,769 stars）搭配 [altic-dev/FluidVoice](https://github.com/altic-dev/FluidVoice)（macOS 本地 StT）與 [Starmel/OpenSuperWhisper](https://github.com/Starmel/OpenSuperWhisper)，反映 AI 監控與資料外洩疑慮下，privacy-first 工具持續吸引特定族群。

- **跨 Agent 互操作成為新戰場**：[openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc)（4,329 stars/week）讓 Codex 在 Claude Code 裡搭檔工作，打破過去 AI coding agent 孤島；[msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) 則提供打包好的多角色 agent 全家桶。

## 3) 值得追蹤專案

1. **[JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)** — JavaScript，7,780 stars/week，歷史檔案 0 記錄首次進榜。穴居人 prompt 法（"why use many token when few token do trick"）省 65% tokens，簡單粗暴但极其有效。動能極強，可能成為下一個 codebase-memory-mcp 級爆發。

2. **[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)** — Rust，5,769 stars/week，07-06 首次進榜後本週再次確認力道。隱私優先 + 本地 AI 會議記錄的明確定位，在 Zoom/Notion AI 壟斷市場中走差異化路線。Rust 實作提供效能護城河。

3. **[DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)** — C，6,309 stars/week，自 06-18 起連續超過 3 週在榜。Knowledge graph 索引 codebase 是 Agent 基礎建設的關鍵層。本週略降（7,945 → 6,309，▼ -20.6%），但仍穩居 Top 5，基本面健康。

4. **[ogulcancelik/herdr](https://github.com/ogulcancelik/herdr)** — Rust，agent multiplexer 在 terminal 背景運行多 agent 協作。07-03 首次進榜至今連續 5 天稳定在 full list，累積 12,848 總 stars。在 Agent 數量暴增的環境中，「agent 背景化、工程師不切換視窗」的設計哲學是關鍵差異化。

5. **[alibaba/page-agent](https://github.com/alibaba/page-agent)** — TypeScript，3,989 stars/week，自 06-28 起連續在榜。阿里開源 in-page GUI agent，對 Web agent 標準化具備風向意義——大廠的參與會加速生態成熟。

## 4) 歷史比對

### 新進榜 / 今日首次出現在榜單

- **[JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)** — 歷史檔案 0 記錄，首次進榜即空降 #2，7,780 stars/week，為本榜最大黑馬。
- **[hasaneyldrm/exercises-dataset](https://github.com/hasaneyldrm/exercises-dataset)** — 歷史檔案 0 記錄，首次進榜，結構化健身資料集。
- **[altic-dev/FluidVoice](https://github.com/altic-dev/FluidVoice)** — 歷史檔案 0 記錄，首次進榜，macOS 本地 StT。
- **[huggingface/speech-to-speech](https://github.com/huggingface/speech-to-speech)** — 歷史檔案 0 記錄，首次進榜，開源本地語音 agent。
- **[msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)** — 07-04 首次進榜。

### 連續上榜專案

- **[usestrix/strix](https://github.com/usestrix/strix)** — 自 07-04 起連續 4 日在榜，加速器趨勢：7,567 → 9,362 → 10,338 → 10,759。AI 滲透測試領域需求量級正進入爆發期。
- **[alibaba/page-agent](https://github.com/alibaba/page-agent)** — 自 06-28 起連續 10 天在榜上（含 full list），最長壽項目。
- **[xbtlin/ai-berkshire](https://github.com/xbtlin/ai-berkshire)** — 自 07-02 起連續 6 天在榜。
- **[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)** — 自 07-03 起連續 5 天在榜。
- **[DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)** — 自 06-18 起連續超过 3 週在榜（本週略降但仍在 Top 5）。

### 成長異常

- **[JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)**：首次進榜即 7,780 stars/week，排名 #2，動能遠超同期新進專案。若明日在榜，将是本月最速成長項目。
- **[usestrix/strix](https://github.com/usestrix/strix)**：連續 4 日加速成長（07-03: 7,567 → 07-04: 7,567 → 07-05: 9,362 → 07-06: 10,338 → 今日: 10,759），是本週唯一突破 10,000 stars/week 門檻的專案。
- **[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)**：07-06 首次進榜後本週再次確認（昨日 5,769 → 今日仍 5,769），在隱私工具市場中力道足夠。

### 落出榜單 / 變動

- 昨日 Top 5 中之 [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) 與 [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) 本週仍入榜但排名更動：codebase-memory-mcp 從 #1 降至 #3；OpenMontage 已出 Top 5（但仍在 full list）。

---

**資料來源**：[GitHub Trending (weekly)](https://github.com/trending?since=weekly)，抓取時間 2026-07-07 08:00 CST
**歷史比對範圍**：`reports/github-trending/` 全檔（44 份，2026-05-23 至今），以 `rg -F <repo>` 精確比對。
