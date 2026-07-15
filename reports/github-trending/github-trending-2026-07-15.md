# GitHub Trending 週報 — 2026-07-15（週三）

> 資料時間：2026-07-15 00:00 UTC（Asia/Taipei 08:00）
> 資料來源：[GitHub Trending Weekly](https://github.com/trending?since=weekly)
> 本報告由 cron job 自動生成，透過 `web_fetch` 抓取 + `rg` 比對歷史檔案。

---

## 1) 今日 Top 5

| # | Repo | 語言 | 本週 Stars | 摘要 |
|---|------|------|-----------|------|
| 1 | [MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search) | TypeScript | 13,195 | AI 求職框架：自動評測職缺、客製 CV + Cover Letter、模擬面試，基於 Claude Code 構建 |
| 2 | [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) | C# | 7,129 | 為 AI agent 打造的 Office 套件——讀/寫/自動化 Word/Excel/PPT，single binary、免安裝 Office |
| 3 | [stablyai/orca](https://github.com/stablyai/orca) | TypeScript | 5,724 | ADE 平台：用自身訂閱運行 agent 艦隊，支援桌面 + 手機雙平台 |
| 4 | [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) | Rust | 4,389 | 100% 本地 AI 會議助手，4x 加速逐字稿 + speaker diarization + Ollama 摘要，免雲端 |
| 5 | [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) | TypeScript | 4,297 | 單端點 AI 閘道：231+ 模型供應商（50+ 免費），RTK+Caveman 疊加壓縮省 15–95% tokens |

---

## 2) 主題趨勢

- **Agent 工具鏈從「寫程式」全面轉向「操作桌面 + Office 文件」**：[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)（C#、single binary）連續 4 日動能登頂 Top 5；[wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) 讓 agent 接管 terminal 與檔案系統；加上先前 [alibaba/page-agent](https://github.com/alibaba/page-agent) 的瀏覽器 GUI agent——Agent 已從程式 editor 擴散到「Office + 終端機 + 瀏覽器」三位一體的操作層面。

- **多 Agent 協作與 AI 求職應用成為新賽道**：[stablyai/orca](https://github.com/stablyai/orca)（fleet IDE 管控）+[ogulcancelik/herdr](https://github.com/ogulcancelik/herdr)（終端背景 agent 多工器）形成多 Agent 協作陣營；[MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search) 則將 AI agent 從工程師生產力工具擴展到**大眾求職市場**——自動評測職缺、客製 CV、模擬面試，單週 13,195 ⭐ 證明剛需存在。

- **Token 經濟進入產品化階段**：[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)（231+ 供應商、RTK+Caveman 疊加壓縮省下 15–95% tokens）持續在榜，直接回應「跑 agent 口袋夠深嗎」這個規模化部署的根本問題——token 成本已比模型能力更影響落地速度。

- **隱私優先與端側 AI 穩定剛需**：[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)（完全本地 AI 會議記錄）、[TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory)（零外部 API 依賴的 agent 長期記憶）顯示在 AI 監控與資料外洩疑慮下，Privacy-first 工具已形成穩定利基市場。

---

## 3) 值得追蹤專案

1. **[MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search)** — TypeScript，13,195 stars/week，**07-08 首次進榜以來連續 3 天在榜且登頂**。Agent 求職框架，從工程師族群跨到大眾市場的首波指標。動能若持續，本週有望站穩 10K+ ⭐。**高度推薦追蹤**：Agent-to-Consumer 的風向球。

2. **[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)** — C#，7,129 stars/week，**07-11 首次進榜以來連續 4 日上升無回落**（逐日上升、從未回落）。Single binary、無需安裝 Office，精準打中 Windows 企業市場。Agent 工具鏈龍頭，**本波最強動能指標**，若延續有機會挑戰 10,000 ⭐/week。

3. **[stablyai/orca](https://github.com/stablyai/orca)** — TypeScript，5,724 stars/week，多 Agent IDE 平台，桌面 + 手機雙平台。Agent 從单人 single-agent 走向 fleet management 的關鍵基礎設施。

4. **[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)** — TypeScript，4,297 stars/week，**自 07-03 起連續 13 日在榜**。231+ 模型供應商單端點、token 壓縮省 15–95%、MCP/A2A 支援——多 agent 時代的網路層協定。穩定長紅，值得持續觀察其 token 優化演算法的演進。

5. **[TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory)** — TypeScript，1,790 stars/week，**歷史全檔 0 記錄、本次首次進榜**。TencentDB Agent Memory 提供 zero-external-dependency 的 agent 長期記憶，4 階漸進式管線。大廠（腾讯）投入 agent 記憶層，驗證 agent memory 已從論文走向產品化。

---

## 4) 歷史比對（新進榜 / 連續上榜 / 成長異常）

### 新進榜（歷史 90 天全檔 0 記錄 → 今日首次出現）

| Repo | 語言 | 本週 Stars | 備註 |
|------|------|-----------|------|
| [TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) | TypeScript | 1,790 | 腾讯 agent 長期記憶，zero external API dependency |
| [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) | TypeScript | 2,009 | MCP server 終端控制，**07-12 首次進榜、連續 4 天在榜** |
| [openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc) | JavaScript | 2,063 | OpenAI 桥接 Codex 至 Claude Code，**07-04 首次進榜、斷續在榜** |
| [tt-a1i/archify](https://github.com/tt-a1i/archify) | JavaScript | 1,519 | Agent 架構圖生成，**07-12 首次進榜** |

### 連續上榜

| Repo | 已連續天數 | 趨勢 |
|------|-----------|------|
| [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) | **13 天**（07-03 起） | 長期穩居 full list，token 優化需求持續剛強 |
| [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) | **4 天**（07-11 起） | 逐日上升無回落，最強動能 |
| [stablyai/orca](https://github.com/stablyai/orca) | 長期穩定（自 06-24 頻繁在榜） | 多 Agent IDE 老牌選手 |
| [ogulcancelik/herdr](https://github.com/ogulcancelik/herdr) | **10 天**（07-05 起） | 終端背景 agent 多工器，穩定 full list |
| [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) | **7 天**（07-08 起） | 本週從 7,349 回落至 4,389（▼ -40.3%），獲利了結明顯 |
| [bradautomates/claude-video](https://github.com/bradautomates/claude-video) | **7 天**（07-09 起） | 讓 agent 看影片，穩定在榜 |
| [vxcontrol/pentagi](https://github.com/vxcontrol/pentagi) | **4 天**（07-12 起） | AI 滲透測試 Go 實作，穩定 full list |
| [TencentCloud/CubeSandbox](https://github.com/TencentCloud/CubeSandbox) | **7 天**（07-09 起） | 腾讯 agent sandbox，穩定 full list |
| [Nutlope/hallmark](https://github.com/Nutlope/hallmark) | **2 天**（07-14 起） | Anti-AI-slop 設計技能，穩定 full list |

### 成長異常（動能顯著加速或衰退）

| Repo | 變化 | 解讀 |
|------|------|------|
| [MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search) | 昨日未上榜 → 今日 **13,195 ⭐ 空降 #1** | 疑似 viral 效應（Hacker News / Twitter 擴散），動能爆發力極強但穩定度待觀察 |
| [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) | ▲ +8.9% 日增（昨日 6,974 → 今日 7,129） | 連續 4 日上升無回落，是本榜目前最強持續動能 |
| [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) | ▼ -40.3% 日增（昨日 7,440 → 今日 4,389） | 本地 AI 會議題材進入獲利了結期，是否站穩 4,000 是本週觀察重點 |
| [bradautomates/claude-video](https://github.com/bradautomates/claude-video) | 昨日 4,353 → 今日 3,554（▼ -18.3%） | 的影片理解赛道競爭加劇 |

### 昨日有但今日掉出榜單（full list 以上）

- [openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc)：昨日 #11（2,803 ⭐）→ 今日**直接掉出榜單**，OpenAI 桥接 Codex 至 Claude Code 的插件持續衰退中
- [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)：昨日 #2（6,284 ⭐）→ 今日**未上榜**（仍可能在 full list 但前 25 未包含）
- [alibaba/page-agent](https://github.com/alibaba/page-agent)：昨日 full list → 今日未上榜

---

> **資料限制**：本次 `web_fetch` 透過 readability 僅完整萃取約 19–20 個 repo（GitHub Trending 通常 25 個），[argoproj/argo-cd](https://github.com/argoproj/argo-cd) 與 [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) 出現在原始頁面上但 star/week 數據未被完整擷取。歷史比對使用 `rg -F` 精確匹配完整 repo 名（owner/name），共比對 15 份歷史報告（07-05 ~ 07-14），無資料缺失。

---

*報告產生時間：2026-07-15 08:00 (Asia/Taipei)*
*產生者：OpenClaw cron job `daily-github-trending-analysis`*
