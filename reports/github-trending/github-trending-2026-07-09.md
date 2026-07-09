# GitHub 本週熱門專案 — 2026-07-09（週四）

## 1) 今日 Top 5（repo、語言、本週 stars）

| # | Repo | 語言 | 本週 Stars | 簡介 |
|---|------|------|-----------|------|
| 1 | [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) | Rust | 8,366 | 100% 本地 AI 會議記錄助手，4× 加速 Parakeet/Whisper 逐字稿 + Ollama 摘要 |
| 2 | [usestrix/strix](https://github.com/usestrix/strix) | Python | 10,274 | 開源 AI 滲透測試工具，自動發現並修復應用程式漏洞 |
| 3 | [facebook/astryx](https://github.com/facebook/astryx) | TypeScript | 4,943 | Facebook 開源 fully-customizable、agent-ready 設計系統 |
| 4 | [openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc) | JavaScript | 4,890 | 讓 Codex 在 Claude Code 內搭檔工作——跨 agent 互操作正式產品化 |
| 5 | [alibaba/page-agent](https://github.com/alibaba/page-agent) | TypeScript | 4,295 | JavaScript in-page GUI agent，用自然語言操控網頁介面 |

> 與昨日（07-08）相比，Top 5 再度大換血：[facebook/astryx](https://github.com/facebook/astryx) 首次進榜即空降 #3；[openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc) 與 [alibaba/page-agent](https://github.com/alibaba/page-agent) 重新攻回 Top 5。昨日 #3 [hasaneyldrm/exercises-dataset](https://github.com/hasaneyldrm/exercises-dataset) 本週下跌至 full list（本日 3,028 ⭐，▼ -38.8%），[ogulcancelik/herdr](https://github.com/ogulcancelik/herdr) 與 [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) 被擠出 Top 5 但仍在 full list 內。

## 2) 主題趨勢

- **AI Agent 應用場域持續擴張，大廠正式進場**：[facebook/astryx](https://github.com/facebook/astryx)（agent-ready 設計系統）代表 Meta 開始將「Agent 友善」納入基礎建設思維；[openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc) 讓 Codex 與 Claude Code 互通，將「跨 agent 協作」從概念推向產品；[stablyai/orca](https://github.com/stablyai/orca)（fleet IDE）持續在 full list——Agent 已從單體工具走向多 agent 協作體系。

- **本地端 AI 的剛需已不可逆**：[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) 連續 3 日在榜且動能走強（昨日 7,349 → 今日 8,366，▲ +13.8%），[JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)（穴居人 token 優化法）持續在 full list，[huggingface/speech-to-speech](https://github.com/huggingface/speech-to-speech) 開源本地語音 agent 進榜——privacy-first 不再是利基刁鑽需求，而是主流用戶的明確偏好。

- **Token 成本戰爭白熱化**：[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)（231+ 供應商單端點，RTK+Caveman 疊加壓縮省 15–95% tokens）搭配 [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)（省 65% tokens），直接回應「跑 agent 口袋夠深嗎」這個根本問題——在 Agent 部署規模化時，token 成本比模型能力更影響落地速度。

- **Agent 工具鏈從 Web 走向終端、從雲端走向地端**：[ogulcancelik/herdr](https://github.com/ogulcancelik/herdr)（終端機背景 agent 多工器）、[altic-dev/FluidVoice](https://github.com/altic-dev/FluidVoice)（macOS 本地 StT）、[dotnet/skills](https://github.com/dotnet/skills)（官方 .NET agent 技能庫）顯示 Agent 生態正從「Web-only、雲端 API」分化出「終端原生」與「語言原生」的分線演化，與業界 .NET/Java/Python 多語言 agent 接軌的趨勢吻合。

## 3) 值得追蹤專案

1. **[facebook/astryx](https://github.com/facebook/astryx)** — TypeScript，4,943 stars/week，**歷史檔案 0 記錄，首次進榜即空降 #3**。Meta 開源、fully-customizable 且「agent ready」的設計系統，首度將 Agent 友善（agent-friendly component model）納入頂層設計——大廠的參與加速 Web agent 標準化風向。

2. **[immich-app/immich](https://github.com/immich-app/immich)** — TypeScript，2,099 stars/week，**歷史檔案 0 記錄，首次進榜**。自託管照片／影片管理方案，**總 stars 已達 106,924**，為本榜整體「最資深」的常見專案——首次打入 weekly trending 代表 self-hosted 生態圈再度進入大眾視野。

3. **[TencentCloud/CubeSandbox](https://github.com/TencentCloud/CubeSandbox)** — Rust，2,106 stars/week，**歷史檔案 0 記錄，首次進榜**。腾讯出品的 agent sandbox：instant、concurrent、secure、lightweight。大廠相繼投入 agent 安全隔離層（sandbox），繼 [openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc) 跨平台互操作之後，「安全隔離」成為另一個基礎設施戰場。

4. **[JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)** — JavaScript，8,080 stars/week，自 07-07 起連續 3 天在榜。穴居人 prompt 法簡單卻極有效，總 stars 已達 86,807——token 優化類專案中最具影響力的開源代表。持續在榜顯示熱度並非曇花一現。

5. **[dotnet/skills](https://github.com/dotnet/skills)** — C#，840 stars/week，**歷史檔案 0 記錄，首次進榜**。Microsoft 官方維護的 .NET agent 技能庫，降低 .NET 開發者接軌 AI coding agent 的門檻，補齊了過去 agent 生態系「重 Python/TS、輕 C#」的一塊拼圖。

## 4) 歷史比對

### 新進榜 / 今日首次出現在歷史報告

- **[facebook/astryx](https://github.com/facebook/astryx)** — 0 歷史記錄，首次進榜。Meta 開源 agent-ready 設計系統，空降 #3，大廠參與的風向指標。
- **[immich-app/immich](https://github.com/immich-app/immich)** — 0 歷史記錄，首次進榜（但總 stars 106,924，為本榜「最資深」專案）。self-hosted 管理方案首次打入 weekly trending。
- **[TencentCloud/CubeSandbox](https://github.com/TencentCloud/CubeSandbox)** — 0 歷史記錄，首次進榜。腾讯 agent 安全 sandbox。
- **[alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills)** — 0 歷史記錄，首次進榜。345 個 Claude Code skills & plugins 大合集，涵蓋 30+ agents、330+ skills、engineering/marketing/product/compliance 等多領域。
- **[bradautomates/claude-video](https://github.com/bradautomates/claude-video)** — 0 歷史記錄，首次進榜。讓 Claude 看影片——自動下載、抽幀、轉逐字稿，再交給 Claude。
- **[dotnet/skills](https://github.com/dotnet/skills)** — 0 歷史記錄，首次進榜。Microsoft .NET 官方 agent 技能庫。

### 連續上榜專案

- **[usestrix/strix](https://github.com/usestrix/strix)** — 自 07-04 起連續 6 日在榜，維持 #1–#2 水位，仍是唯一破萬門檻的專案（10,274）。
- **[ogulcancelik/herdr](https://github.com/ogulcancelik/herdr)** — 自 07-03 起連續 7 日在榜，穩定 full list。
- **[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)** — 自 07-03 起連續 7 日在榜，穩定 full list。
- **[alibaba/page-agent](https://github.com/alibaba/page-agent)** — 自 06-28 起連續 13 日在榜（含 full list），**本榜最長壽專案**。
- **[JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)** — 自 07-07 起連續 3 日在榜，動能極強（8,080 ⭐）。
- **[asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)** — 自 06-17 起多次進出榜單，總 stars 54,150。**本次回歸後若可維持，將挑戰連續在榜紀錄**。

### 掉出 Top 5（full list 仍在榜）

- **[hasaneyldrm/exercises-dataset](https://github.com/hasaneyldrm/exercises-dataset)** — 昨日 #3（4,950）→ 今日 full list（3,028），▼ -38.8%。結構化健身資料集的爆發屬短週期中快速升降型，未來是否穩固需再觀察。
- **[ogulcancelik/herdr](https://github.com/ogulcancelik/herdr)** — 昨日 #4 → 今日 #6，絕對 stars 略升（4,557 → 4,754 ▲ +4.3%），純粹被新進榜者擠下。
- **[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)** — 昨日 #5 → 今日 #7（4,797 → 4,424，▼ -7.8%），多模型路由市場面臨新玩家競爭。

### 成長異常

- **[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)**：本日最強增幅，從昨日 7,349 → 今日 8,366（▲ +13.8%），自 07-06 首次進榜以來連續 3 天攀升（2,972 → 5,769 → 7,349 → 8,366）——隱私優先 + 本地 AI 會議記錄的定位持續爆發。
- **[asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)**：本日 6,182 stars/week 回歸 full list，較 07-08 未在榜單內明顯回升，是否重回連續在榜態勢需再觀察。
- **[immich-app/immich](https://github.com/immich-app/immich)**：total stars 106,924 的老牌專案首次打入 weekly trending，過去從未出現在歷史報告——self-hosted 需求是否有週期性爆發值得追蹤。

---

**資料來源**：[GitHub Trending (weekly)](https://github.com/trending?since=weekly)，抓取時間 2026-07-09 08:00 CST
**歷史比對範圍**：`reports/github-trending/` 全檔（46 份，2026-06-09 至今），以 `rg -F <repo>` 精確比對。
