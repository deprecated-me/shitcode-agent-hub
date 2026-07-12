# GitHub 本週熱門專案 — 2026-07-12（週日）

## 1) 今日 Top 5（repo、語言、本週 stars）

| # | Repo | 語言 | 本週 Stars | 簡介 |
|---|------|------|-----------|------|
| 1 | [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) | Rust | 8,579 | 100% 本地 AI 會議記錄助手，4× 加速 Parakeet/Whisper 逐字稿 + Ollama 摘要，零雲端 |
| 2 | [openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc) | JavaScript | 4,030 | 讓 Codex 在 Claude Code 內搭檔工作——跨 agent 互操作正式產品化 |
| 3 | [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) | C# | 6,549 | 第一個為 AI agent 打造的 Office 套件——讀/寫/自動化 Word/Excel/PPT，免安裝 Office |
| 4 | [usestrix/strix](https://github.com/usestrix/strix) | Python | 4,987 | 開源 AI 滲透測試工具，自動發現並修復應用程式漏洞 |
| 5 | [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) | JavaScript | 4,696 | 穴居人 prompt 法——省 65% tokens；07-07 沖至 #2 後消失 3 日，今日回榜 |

> **Top 5 大換血**：[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) 歷史檔案 0 記錄、首次進榜即空降 #3（▲ +13.1%，昨日 5,789 → 今日 6,549）；[JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) 回榜 #5（昨日未在 Top 22）。昨日 #2 [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)（7,944 ⭐）直接掉出榜單。

## 2) 主題趨勢

- **Agent 大舉入侵一般辦公流程，自動化賽道多點開花**：[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)（C#、6,549 ⭐）首次進榜即空降 #3，補上 Agent 在 Office 場景的最後一塊拼圖；[wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP)（TypeScript、1,451 ⭐）**歷史首次進榜**，讓 agent 直接掌控 terminal 與檔案系統。Agent 已從程式碼 editor 擴散到「Office 文件 + 終端機」雙主軸辦公場景。

- **本地端 AI 持續爆發，隱私成為標配而非加分項**：[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)（Rust、100% 本地）**連續 8 日穩居 Top 5**，自 07-05 進榜以來穩定攀升（2,972 → 8,579，▲ +189%），今日終於睽違 2 日再度奪回 #1。[Ruvnet/RuView](https://github.com/ruvnet/RuView)（Rust、3,720 ⭐、用 WiFi 訊號做空間感知、無需視訊畫面）同樣基於 Rust + 本地處理，顯示 **Rust + 隱私優先** 已形成一個明確的技術信仰流派。

- **Cross-agent 互操作從概念推向量產**：[openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc) 重新回攻 Top 5 #2（昨日 #6 → 今日 #2），[CChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)（46.6K 總 stars）持續在榜。OpenAI 讓 Codex 在 Claude Code 裡掛插件 vs. Google 把 Chrome DevTools 做成 MCP server——**大廠開始抢夺「agent 互操作層」的標準定義權**，不再只是比單模型能力。

- **AI 安全從系統提示隔離到滲透測試全棧覆蓋**：[asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) 穩居 Top 5 + [TencentCloud/CubeSandbox](https://github.com/TencentCloud/CubeSandbox)（Rust、2,416 ⭐）+ [usestrix/strix](https://github.com/usestrix/strix)（AI 滲透測試）+ [vxcontrol/pentagi](https://github.com/vxcontrol/pentagi)（Go、1,766 ⭐，**歷史首次進榜**）——「透明 → 隔離 → 攻擊 → 自主滲透」四層安全需求同時在榜上，**Agent 安全已從單一工具升級為體系化基建**。

## 3) 值得追蹤專案

1. **[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)** — Rust，8,579 stars/week，自 07-05 起**連續 8 日在榜**，穩定攀升（2,972 → 5,769 → 7,349 → 8,366 → 8,885 → 8,795 → 8,579），**本榜目前累積增幅最高且最穩定專案**。今日再度奪回 #1。定位極明確：100% 本地 + 隱私優先 + AI 會議記錄。Rust 實作提供效能護城河。（Agent 從工程師族群跨越到大眾市場的風向指標 + 登頂信號）

2. **[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)** — C#，6,549 stars/week，**歷史全檔 0 記錄、首次進榜即空降 #3**。第一個「為 AI agent 而生」的 Office 套件——讀/寫/自動化 Word/Excel/PPT、無需安裝 Office，single binary。Agent 正式跨入一般辦公場景，動能極強（昨日 5,789 → 今日 6,549，▲ +13.1%），有望站穩 Top 5。

3. **[openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc)** — JavaScript，4,030 stars/week，昨日 #6 → 今日 #2 强势回歸 Top 5。OpenAI 將 Codex 桥接到 Claude Code，**「跨 agent 互操作」正式成為產品而非概念**。隨著越来越多 agent 湧現，這種「橋接層」專案會成为基礎設施的关键一環。

4. **[wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP)** — TypeScript，1,451 stars/week，**歷史全檔 0 記錄、首次進榜**。MCP server 讓 agent 直接掌控 terminal、filesystem、diff editing——程式設計 agents 的「手與腳」基礎設施。MCP 生態持續壯大，DesktopCommanderMCP 補上了「本地 terminal 操作」這塊拼图。

5. **[TencentCloud/CubeSandbox](https://github.com/TencentCloud/CubeSandbox)** — Rust，2,416 stars/week，腾讯出品的 agent sandbox。大廠相繼投入 agent 安全隔離層，CubeSandbox 以 Rust 実装 instant + concurrent + secure + lightweight 四大特性，與 [usestrix/strix](https://github.com/usestrix/strix) + [vxcontrol/pentagi](https://github.com/vxcontrol/pentagi) 形成「安全攻防一條龍」。

## 4) 歷史比對

### 新進榜 / 今日首次出現在歷史報告

- **[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)** — C#，6,549 ⭐，**歷史全檔 0 記錄、首次進榜即空降 #3**。Agent 正式跨入一般辦公場景的里程碑。
- **[wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP)** — TypeScript，1,451 ⭐，**歷史全檔 0 記錄、首次進榜**。MCP server 讓 agent 接管 terminal/file system，MCP 生態版圖持續擴張。
- **[vxcontrol/pentagi](https://github.com/vxcontrol/pentagi)** — Go，1,766 ⭐，**歷史全檔 0 記錄、首次進榜**。Fully autonomous agents for penetration testing，Go 實作。
- **[google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills)** — TypeScript，549 ⭐，**歷史全檔 0 記錄、首次進榜**。Google 官方的 Stitch MCP-compatible agent skills 庫。
- **[tt-a1i/archify](https://github.com/tt-a1i/archify)** — JavaScript，1,036 ⭐，**歷史全檔 0 記錄、首次進榜**。讓 agent 產生架構圖（PNG/JPEG/WebP/SVG 匯出）。

### 回歸榜單（此前曾出現但未在 07-11 Top 22）

- **[openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc)** — 07-09 #4 → 07-10 #6 → 07-11 在 full list 但不在 Top 5 → 07-12 **強勢回歸 Top 5 #2**（4,030 ⭐）。Cross-agent 互操作產品化。
- **[JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)** — 07-07 空降 #2 → 07-08~07-10 消失 → 07-11 回 #6 → 07-12 續在 #5。**Token 優化法寶專案**，波動後回歸。

### 連續上榜專案

- **[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)** — 自 07-05 起**連續 8 日在榜**，穩定攀升（2,972 → 8,579），**本榜最穩定上升專案**，今日再登 #1。
- **[usestrix/strix](https://github.com/usestrix/strix)** — 自 07-04 起**連續 9 日在榜**，長期穩居 #1–#4。
- **[ogulcancelik/herdr](https://github.com/ogulcancelik/herdr)** — 自 07-03 起**連續 10 日在榜**，穩定 full list（#5, 4,349 ⭐）。
- **[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)** — 自 07-03 起**連續 10 日在榜**，穩定 full list。
- **[asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)** — 自 06-17 起多次進出，07-09 回 full list → 07-10 Top 5 → 07-12 #4。
- **[stablyai/orca](https://github.com/stablyai/orca)** — 自 07-03 起多次進出 full list，07-12 持續。

### 掉出 Top 5 / 掉出榜單

- **[addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)** — 昨日 #2（7,944 ⭐）→ 07-12 **未出現在 trending page 中**（已掉出前 22）。老牌 skills 賽道領導者突然消失，波動性極高。
- **[facebook/astryx](https://github.com/facebook/astryx)** — 昨日 #7 full list → 07-12 **未出現在 trending page 中**。Meta 的 agent-ready 設計系統在 full list 停留約 1 週後退潮。

### 成長異常

- **[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)**：**全檔 0 記錄 → 首次進榜即空降 #3**，且較昨日成長 ▲ +13.1%（5,789 → 6,549），動能極強。Agent × Office 自動化赛道正式爆發的信號。
- **[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)**：連續 8 日上升後首度小幅回落（昨日 8,795 → 今日 8,579，▼ -2.5%），但仍穩居 #1。**累積增幅 +189%，本榜目前最穩定上升專案**。

---

**資料來源**：[GitHub Trending (weekly)](https://github.com/trending?since=weekly)，抓取時間 2026-07-12 08:00 CST
**歷史比對範圍**：`reports/github-trending/` 全檔（51 份，2026-05-18 至今），以 `rg -F <repo>` 精確比對。
