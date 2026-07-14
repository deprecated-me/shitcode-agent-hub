# GitHub 本週熱門專案 — 2026-07-14（週二）

## 1) 今日 Top 5（repo、語言、本週 stars）

| # | Repo | 語言 | 本週 Stars | 簡介 |
|---|------|------|-----------|------|
| 1 | [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) | C# | 7,596 | 第一個為 AI agent 打造的 Office 套件——讀/寫/自動化 Word/Excel/PPT，single binary、免安裝 Office |
| 2 | [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) | JavaScript | 6,284 | 定期更新 Anthropic / OpenAI / Google / xAI / Cursor / Copilot / VS Code / Perplexity 等系統提示萃取庫 |
| 3 | [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) | Rust | 5,392 | 100% 本地 AI 會議記錄助手，4× 加速 Parakeet/Whisper 逐字稿 + Ollama 摘要，零雲端 |
| 4 | [stablyai/orca](https://github.com/stablyai/orca) | TypeScript | 5,263 | ADE 平台，用自身訂閱運行 agent 艦隊，支援桌面 + 手機雙平台 |
| 5 | [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) | TypeScript | 4,345 | 一端點對接 231+ 家 AI 供應商（50+ 免費），RTK+Caveman 疊層壓縮省 15-95% tokens，MCP/A2A + 桌面/PWA 雙平台 |

> **Top 5 連續兩日完全一致但排名洗牌**：與昨日相同 5 個 repo，但排名全部變動。[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) ▲ +8.9% 日增，從昨日 #3 逆襲登顶，**連續 4 日上升無回落**（07-11 首進榜 → 07-14 7,596），是本榜目前最強動能指標。[asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) 雖已創歷史新高，本週增速放緩（▼ -12.2% 週回檔），維持 #2。[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) 自昨日 7,440 高點回落至 5,392（▼ -27.5%），是今日 Top 5 最大跌幅——本地 AI 會議題材進入獲利了結期。[stablyai/orca](https://github.com/stablyai/orca) 逆勢成長 ▲ +17.5%，多 agent IDE 重返 Top 5 第 4 位。[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) 微幅回落 ▼ -3.6%，但仍站穩 #5，**自 07-03 起連續 12 日在榜**。

## 2) 主題趨勢

- **Agent 工具鏈進入 Office 自動化紅利期**：[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)（C#、7,596 ⭐）連續 4 日上升登頂，搭配 [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP)（TypeScript、**首次進榜**、1,939 ⭐）與 [alibaba/page-agent](https://github.com/alibaba/page-agent)（TypeScript、1,950 ⭐，JavaScript 網頁內 GUI agent），Agent 從「寫程式」正式跨入「操作桌面」與「操作瀏覽器」。C# + single binary 的 OfficeCLI 架構尤其精準打中 Windows 企業市場，是本波工具鏈升級的龍頭指標。

- **隱私優先 × 本地 AI 動能觸頂回落**：[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) 昨日創 7,440 高點後今日回落至 5,392（▼ -27.5%），[it 停止連續上升態勢](https://github.com/Zackriya-Solutions/meetily)。[ruvnet/RuView](https://github.com/ruvnet/RuView)（Rust、3,403 ⭐，用 WiFi 訊號做空間感知）連續多日於 full list 但未進 Top 5。隱私題材從「爆發期」進入「震盪整理」，需觀察是否再有新一波催化劑。

- **AI 滲透測試 + 系統提示萃取形成「資安透明度」主線**：[asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) 維持 #2（6,284 ⭐），[usestrix/strix](https://github.com/usestrix/strix)（Python、3,403 ⭐）、[vxcontrol/pentagi](https://github.com/vxcontrol/pentagi)（Go、2,199 ⭐，▲ +10.5% 日增）形成資安透明度陣營。從「揭露系統提示」到「自主滲透測試 + Go 語言高效執行」，資安已從專題升級為貫穿整個榜單的基礎需求。

- **Token 優化與多 Agent 協作持續攻城掠地**：[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)（full list 連續 12 日、Top 5 穩居）定義了「多 agent 時代的網路層」，而 [stablyai/orca](https://github.com/stablyai/orca) 則主攻「本地多 agent IDE」。token 經濟已從理論走向產品化。

## 3) 值得追蹤專案

1. **[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)** — C#，7,596 stars/week，**07-11 首次進榜以來連續 4 日上升**（首日 → 今日：逐日上升無回落）。Agent 工具鏈龍頭，single binary、無需安裝 Office。短線已登頂 Top 1，若動能持續，本週有望挑戰 10,000 ⭐/week 關卡。**Agent 從工程師市場跨越到大眾辦公的風向球**。

2. **[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)** — Rust，5,392 stars/week，自 07-07 起**連續 8 日在榜**。昨日創歷史新高 7,440 後今日回落 27.5%，屬正常獲利了結。100% 本地 + 隱私優先 + AI 會議記錄的黃金三角定位不變，若能守穩 5,000 關卡，後市仍看多。

3. **[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)** — TypeScript，4,345 stars/week，自 07-03 起**連續 12 日在榜**，是本週期穩健度最高專案。一端點對接 231+ 家 AI 供應商、RTK+Caveman 疊層壓縮、MCP/A2A 兼容。**實質定義了「多 agent 時代的 API 閘道」**，各項實質指標（星星、排名、韌性）均優。

4. **[stablyai/orca](https://github.com/stablyai/orca)** — TypeScript，5,263 stars/week，自 06-24 起多次進出，今日逆勢成長 ▲ +17.5% 重返 Top 5（#4）。本波最強的多 agent IDE 平台，支援桌面 + 手機雙平台。成長動能重啟，挑戰站穩 Top 5。

5. **[wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP)** — TypeScript，1,939 stars/week，**本次 52 份歷史報告中首次進榜**。MCP server 終端控制 + 檔案系統搜尋 + diff file editing，補上 Agent 在终端的最後一塊拼圖。空降即 Top 10 級別，值得持續觀察。

## 4) 歷史比對

### 新進榜（今日首次出現在歷史報告）

- **[wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP)** — TypeScript，1,939 ⭐，**歷史全檔 0 記錄、首次進榜**。為 Claude 提供 terminal 控制 + 檔案系統操作 + diff editing 的 MCP server。
- **[abseil/abseil-cpp](https://github.com/abseil/abseil-cpp)** — C++，621 ⭐，**歷史全檔 0 記錄、首次進榜**。Abseil Common Libraries (C++).老牌 C++ 工具庫突然出現在 Trending，可能與近日某個熱門 C++ 專案引用有關。
- **[argoproj/argo-cd](https://github.com/argoproj/argo-cd)** — Go (Kubernetes CD)，**歷史全檔 0 記錄、首次進榜**（star/week 資料未被 readability 完整萃取）。老牌 Kubernetes CD 工具重返榜單，可能與雲原生 K8s 生態新一波成長有關。

### 今日新進入 Top 5（此前未進入過歷史 Top 5 表格）

**無**。今日 Top 5 與昨日完全相同（僅排名全數洗牌），沒有 repo 是首次進入 Top 5 榜單。

### 回歸榜單（此前曾出現但在昨日 07-13 全榜中缺席）

- **[alibaba/page-agent](https://github.com/alibaba/page-agent)** — TypeScript，1,950 ⭐，曾在 06-23 ~ 07-09 期間多次上榜，昨日缺席後今日回歸。
- **[facebook/astryx](https://github.com/facebook/astryx)** — TypeScript，2,255 ⭐，曾在 06-25 ~ 07-12 期間斷續出現，昨日回歸後仍在榜。
- **[vxcontrol/pentagi](https://github.com/vxcontrol/pentagi)** — Go，2,199 ⭐，昨天報告中有提及其為新進入 full list，今日仍在。

### 連續上榜專案

- **[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)** — 自 07-03 起**連續 12 日在榜**，本週期穩健度最高。
- **[ogulcancelik/herdr](https://github.com/ogulcancelik/herdr)** — 自 07-03 起**連續 12 日在榜**，穩定 full list。
- **[usestrix/strix](https://github.com/usestrix/strix)** — 自 07-03 起**連續 12 日在榜**，長期穩居 full list。
- **[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)** — 自 07-07 起**連續 8 日在榜**。
- **[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)** — 自 07-11 起**連續 4 日在榜**，動能最強。
- **[bradautomates/claude-video](https://github.com/bradautomates/claude-video)** — 自 07-09 起**連續 6 日在榜**。
- **[TencentCloud/CubeSandbox](https://github.com/TencentCloud/CubeSandbox)** — 自 07-09 起**連續 6 日在榜**。
- **[asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)** — 06-16 起多次進出，維持 Top 2。

### 掉出榜單（出現在 07-13 但不在 07-14 榜單）

- **[openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc)** — 昨日 #11（2,803 ⭐）→ 今日**未上榜**。OpenAI 桥接 Codex 至 Claude Code 的插件在昨日回落 30.4% 後，今日直接掉出榜單。
- **[ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)** — Chrome DevTools MCP server，昨日被提及於趨勢分析，今日消失。
- **[JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)** — 穴居人 token 最佳化法，昨日 #8，今日消失。
- **[addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)** — 老牌 skills 賽道領導者持續不穩定。

### 成長異常

- **[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)**：昨日 6,978 → 今日 7,596，▲ +8.9%，**連續 4 日上升無回落**，動能最強，本日增速最快 Top 5 專案。
- **[stablyai/orca](https://github.com/stablyai/orca)**：昨日 4,481 → 今日 5,263，▲ +17.5%，成長幅度次高。
- **[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)**：昨日 7,440 → 今日 5,392，▼ -27.5%，本日跌幅最大 Top 5 專案。
- **[openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc)**：昨日 2,803 → 今日掉出榜單，連續兩日重挫。

---

**資料來源**：[GitHub Trending (weekly)](https://github.com/trending?since=weekly)，抓取時間 2026-07-14 08:00 CST
**歷史比對範圍**：`reports/github-trending/` 全檔（52 份，2026-05-24 至今），以 `rg -F <repo>` 精確比對。
**資料限制**：readability 僅萃取 19 個完整 repo（GitHub Trending 通常 25 個），[argoproj/argo-cd](https://github.com/argoproj/argo-cd) 的 star/week 數據未被完整擷取。
