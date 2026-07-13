# GitHub 本週熱門專案 — 2026-07-13（週一）

## 1) 今日 Top 5（repo、語言、本週 stars）

| # | Repo | 語言 | 本週 Stars | 簡介 |
|---|------|------|-----------|------|
| 1 | [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) | Rust | 7,440 | 100% 本地 AI 會議記錄助手，4× 加速 Parakeet/Whisper 逐字稿 + Ollama 摘要，零雲端 |
| 2 | [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) | JavaScript | 7,155 | 定期更新Anthropic / OpenAI / Google / xAI / Cursor / Copilot / VS Code / Perplexity 等系統提示萃取庫 |
| 3 | [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) | C# | 6,978 | 第一個為 AI agent 打造的 Office 套件——讀/寫/自動化 Word/Excel/PPT，免安裝 Office |
| 4 | [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) | TypeScript | 4,506 | 一端點對接 231+ 家 AI 供應商（50+ 免費），RTK+Caveman 疊層壓縮省 15-95% tokens |
| 5 | [stablyai/orca](https://github.com/stablyai/orca) | TypeScript | 4,481 | ADE for working with a fleet of parallel agents；桌面 + 手機皆可使用 |

> **Top 5 大幅洗牌**：昨日 Top 5 僅 [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) 和 [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI）衛冕成功，其餘 3 名全換。[asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) 強升 5,715 → 7,155▲ +25.3%，空降 #2；[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) 自 07-03 以來**連續 11 日在榜**；[stablyai/orca](https://github.com/stablyai/orca) 自 06-24 起多次進出，今日总算重返 Top 5。

## 2) 主題趨勢

- **隱私優先 × 本地 AI 的紅利持續放大但動能放緩**：[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)（Rust、100% 本地）**連續 7 日在榜**，但昨日創高 8,579 後今日回落至 7,440（▼ -13.3%），顯示本波本地 AI 會議記錄題材進入震盪整理期。[Ruvnet/RuView](https://github.com/ruvnet/RuView)（Rust、3,763 ⭐、用 WiFi 訊號做空間感知）今日仍在 full list，Rust + 隱私優先旗幟鮮明但未再進 top 5。

- **AI 滲透測試 + 系統提示萃取形成「資安透明度」新賽道**：[asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) 自 06-16 起斷續在榜、今日創歷史新高 7,155（▲ +25.3%週增），搭配 [usestrix/strix](https://github.com/usestrix/strix)（4,143 ⭐）、[vxcontrol/pentagi](https://github.com/vxcontrol/pentagi)（1,989 ⭐）、[TencentCloud/CubeSandbox](https://github.com/TencentCloud/CubeSandbox)（2,490 ⭐）和 [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)——資安透明度從「揭露系統提示」進一步擴大到「自主滲透測試」與「DevTools 安全隔离」，**資安已從專題專案升級為橫貫整個榜單的基礎需求**。

- **Agent Office 自動化在 Windows 生態站穩腳步**：[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) 進榜第 3 日即衝上 6,978（▲ +6.6%，連續 3 日上升），C# + single binary + 免裝 Office 的架構精準打中 Windows 企業用戶刚需。這是 Agent 從工程師市場正式跨入一般辦公室的里程碑。

- **Token 優化與 Multi-agent 協作進入實用化阶段**：[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)（RTK+Caveman 壓縮省 15-95% tokens、4,506 ⭐）與 [stablyai/orca](https://github.com/stablyai/orca)（fleet of parallel agents、4,481 ⭐）首次同時進入 Top 5，代表 Agent 生態從「單 agent 能力競賽」邁向「多 agent + 成本優化」的實用化階段。

## 3) 值得追蹤專案

1. **[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)** — Rust，7,440 stars/week，自 07-07 起連續 7 日在榜，**本週期最穩定上升專案之一**（07-07 5,769 → 今日 7,440，▲ +28.9%）。定位極明確：100% 本地 + 隱私優先 + AI 會議記錄。雖今日回落，但仍在創新高後的正常震盪區間。持續關注是否能站穩 7,000 關卡。（Agent 從工程師族群跨越到大眾市場的風向指標）

2. **[asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)** — JavaScript，7,155 stars/week（▲ +25.3% 週增），自 06-16 起多次進出榜單，今日創歷史新高。定期更新 Anthropic / OpenAI / Google / xAI / Cursor / Copilot 等系統提示，**已成為了解大廠 AI 運作邏輯的標準參考點**。增長模式呈「階梯式」而非穩定線性，顯示每逢新提示被挖掘就會產生一波流量。

3. **[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)** — C#，6,978 stars/week，**首次進榜仅 3 日即站穩 Top 3**，連續 3 日上升（07-11 首次 → 07-12 6,549 → 今日 6,978，▲ +6.6%）。第一個「為 AI agent 而生」的 Office 套件——single binary、無需安裝 Office。Agent 正式跨入一般辦公場景，動能極強，短線有望挑戰 meetily 的 #1 地位。

4. **[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)** — TypeScript，4,506 stars/week，自 07-03 起**連續 11 日在榜**，是本週期穩健度最高的專案之一。一端點對接 231+ 家 AI 供應商（50+ 免費），搭配 RTK+Caveman 疊層壓縮省 15-95% tokens，MCP/A2A 兼容 + 桌面/PWA 雙平台支援。 Agent 互操作層的實質基礎建設，正在定義「多 agent 時代的網路层」。

5. **[bradautomates/claude-video](https://github.com/bradautomates/claude-video)** — Python，4,353 stars/week，自 07-09 首次進榜。讓 Claude 能「看」任何影片——下載、抽幀、轉文字稿後交給 Agent 處理。**補上多模態 agent 最後一塊拼圖——視覺理解管線**。Agent 能「讀程式碼、操作 terminal」之後，下一步就是「看影片、看螢幕、理解視覺世界」，claude-video 正在定義這條赛道。

## 4) 歷史比對

### 新進榜 / 今日首次出現在歷史報告

- **[pbakaus/impeccable](https://github.com/pbakaus/impeccable)** — JavaScript，2,272 ⭐，**歷史全檔 0 記錄、首次進榜**。一個「讓你的 AI 輸出更好看的設計語言」——為 AI agent 的視覺輸出提供設計系統標準化規範。51 份歷史報告中從未出現，今日空降即為 #15，值得追蹤是否站穩。

### 今日新進入 Top 5（此前未進入過歷史 Top 5）

- **[asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)** — 06-16 起斷續在榜（full list），**首次進入 Top 5**（#2，7,155 ⭐，▲ +25.3%）。此前最高排名為 07-12 的 full list，但從未進入過報告 Top 5 表格。
- **[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)** — 07-03 起**連續 11 日在榜**（full list），**首次進入 Top 5**（#4，4,506 ⭐）。在 full list 穩定存在多週後首次攻頂。
- **[stablyai/orca](https://github.com/stablyai/orca)** — 06-24 起多次進出榜單，**首次進入 Top 5**（#5，4,481 ⭐）。老牌多 agent IDE 在長期蓄力後重返光榮。

### 回歸榜單（此前曾出現但未在 07-12 Top 22）

- **[pbakaus/impeccable](https://github.com/pbakaus/impeccable)** — **歷史全檔 0 記錄、首次進榜**。不是「回歸」而是「全新」。

### 連續上榜專案

- **[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)** — 自 07-03 起**連續 11 日在榜**，本週期穩健度最高專案。
- **[ogulcancelik/herdr](https://github.com/ogulcancelik/herdr)** — 自 07-03 起**連續 11 日在榜**，穩定 full list。
- **[usestrix/strix](https://github.com/usestrix/strix)** — 自 07-03 起**連續 11 日在榜**，長期穩居 #3–#7。
- **[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)** — 自 07-07 起連續 7 日在榜。
- **[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)** — 自 07-11 起連續 3 日在榜，動能最強新寵。
- **[TencentCloud/CubeSandbox](https://github.com/TencentCloud/CubeSandbox)** — 自 07-09 起連續 5 日在榜。
- **[asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)** — 06-16 起多次進出，今日創歷史新高後重新站穩 Top 5。

### 掉出 Top 5

- **[openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc)** — 昨日 #2（4,030 ⭐）→ 今日 #11（2,803 ⭐，▼ -30.4%）。OpenAI 桥接 Codex 至 Claude Code 的跨 agent 插件在單日暴漲後迅速退潮，單日跌幅最高。
- **[usestrix/strix](https://github.com/usestrix/strix)** — 昨日 #4（4,987 ⭐）→ 今日 #7（4,143 ⭐，▼ -16.9%）。
- **[JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)** — 昨日 #5（4,696 ⭐）→ 今日 #8（3,992 ⭐，▼ -15.0%）。穴居人 token 優化法在連續兩日後回落。

### 掉出榜單（出現在 07-12 但不在 07-13 榜單）

- **[addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)** — 07-12 在 full list → 07-13 **消失**。老牌 skills 賽道領導者持續不穩定。

### 成長異常

- **[asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)**：昨日 estimated ~5,715 ▲ +25.3% 週增，7,155 ⭐ 創歷史新高。本成长为幅度最大專案，且首次進入 Top 5。
- **[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)**：連續 3 日上升無回落（07-11 → 07-12 6,549 → 07-13 6,978，▲ +6.6%），動能極強。
- **[openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc)**：▼ -30.4% 單日跌幅，從 4,030 跌至 2,803，為本榜今日最大回落。

---

**資料來源**：[GitHub Trending (weekly)](https://github.com/trending?since=weekly)，抓取時間 2026-07-13 08:00 CST
**歷史比對範圍**：`reports/github-trending/` 全檔（51 份，2026-05-23 至今），以 `grep -r -F <repo>` 精確比對。
