# GitHub Trending 週報 — 2026-11-20

來源：<https://github.com/trending?since=weekly>
抓取時間：2026-11-20 08:00 (Asia/Taipei)

## 1) 今日 Top 5（依本週 stars 增量排序）

| # | Repo | 語言 | 本週 stars | 總 stars |
|---|------|------|-----------|---------|
| 1 | [dream-num/univer](https://github.com/dream-num/univer) | TypeScript | +7,248 | 30,433 |
| 2 | [GoogleChrome/modern-web-guidance-src](https://github.com/GoogleChrome/modern-web-guidance-src) | TypeScript | +6,858 | 9,111 |
| 3 | [meta/astryx](https://github.com/meta/astryx) | TypeScript | +4,977 | 30,954 |
| 4 | [alibaba/open-code-review](https://github.com/alibaba/open-code-review) | Go | +4,492 | 54,379 |
| 5 | [backnotprop/plannotator](https://github.com/backnotprop/plannotator) | TypeScript | +3,468 | 13,660 |

其餘上榜（依榜單順序）：

- [ag-ui-protocol/ag-ui](https://github.com/ag-ui-protocol/ag-ui) — TypeScript — +3,455
- [tradermonty/claude-trading-skills](https://github.com/tradermonty/claude-trading-skills) — Python — +3,385
- [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) — TypeScript — +3,229
- [we-promise/sure](https://github.com/we-promise/sure) — Ruby — +3,226
- [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) — Python — +3,179
- [kajisho5/ffmpeg-skill](https://github.com/kajisho5/ffmpeg-skill) — Python — +2,998
- [google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills) — TypeScript — +1,829
- [pookjw/HermesEnabler](https://github.com/pookjw/HermesEnabler) — Objective-C — +904

## 2) 主題趨勢

- **Agent 工具鏈全面占榜**：14 個上榜專案中，超過一半直接服務 coding agent — plannotator（agent 協作審碼）、stitch-skills（Agent Skills 標準庫）、chrome-devtools-mcp（DevTools MCP）、ffmpeg-skill（42 個 FFmpeg 工具 + MCP server）、last30days-skill（多平台研究摘要）。Agent Skills / MCP 生態已成獨立品類。
- **「給 agent 用的」UI/設計系統興起**：[meta/astryx](https://github.com/meta/astryx) 標榜「agent ready」設計系統，[GoogleChrome/modern-web-guidance-src](https://github.com/GoogleChrome/modern-web-guidance-src) 把 web 最佳實踐打包成 agent 可讀指引，[ag-ui-protocol/ag-ui](https://github.com/ag-ui-protocol/ag-ui) 定義 Agent-User 互動協定。前端正在為「agent 作為使用者」重做一層。
- **AI 程式審查與品質工具進主流**：[alibaba/open-code-review](https://github.com/alibaba/open-code-review) 以確定性 pipeline + LLM agent 混合架構做行級審查，內建多語言規則（NPE、thread-safety、XSS、SQL injection），本週 +4,492 stars，總星已破 5.4 萬，屬實戰級採用。
- **垂直領域 agent skill 成長**：交易（claude-trading-skills）、個人財務（we-promise/sure，Ruby）、辦公室文件（univer）等非通用領域開始出現高星 skill/SDK，代表 agent 應用從通用助手往專業工作流擴散。

## 3) 值得追蹤專案

- [alibaba/open-code-review](https://github.com/alibaba/open-code-review) — 54.4k stars，阿里內部規模驗證，OpenAI/Anthropic 相容，規則集可擴充。若導入 AI code review，這是目前最成熟的開源選項。
- [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) — 58.4k stars，官方出品，直接讓 agent 驅動 DevTools。瀏覽器自動化與 agent 結合的標準零件。
- [backnotprop/plannotator](https://github.com/backnotprop/plannotator) — 13.7k stars，把 plan / annotate / review / 回饋送回 agent 做成單一工作區，補上「人介入 agent 流程」的缺口。
- [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) — 70.8k stars（本榜最高總星），跨平台（Reddit/X/YT/HN/Polymarket）研究 + 有根據摘要，可作為深度研究的起點。
- [dream-num/univer](https://github.com/dream-num/univer) — 30.4k stars，本週增量第一（+7,248）。Office SDK 同時面向「人」與「AI agent」，值得關注其外掛架構。

## 4) 歷史比對

比對範圍：`reports/github-trending/` 現有 5 份歷史報告（2026-11-15 ~ 2026-11-19）。

**新進榜（歷史檔案查無，首次出現）：**

- [pookjw/HermesEnabler](https://github.com/pookjw/HermesEnabler) — 在 Apple Watch 上啟用 Hermès 錶面，Objective-C，+904 stars。非 agent 主題，屬硬體/越獄向應用。
- [kajisho5/ffmpeg-skill](https://github.com/kajisho5/ffmpeg-skill) — 本地影片編輯 skill，42 個 FFmpeg 工具 + MCP server，+2,998 stars。

**連續上榜（近 5 日每日皆出現）：**

- [meta/astryx](https://github.com/meta/astryx) — 11-15 ~ 11-19 連續 5 日
- [we-promise/sure](https://github.com/we-promise/sure) — 11-16 ~ 11-19 連續 4 日

**長期在榜（近 5 日出現 ≥3 次）：**

- [GoogleChrome/modern-web-guidance-src](https://github.com/GoogleChrome/modern-web-guidance-src) — 4 次（11-17 ~ 11-19）
- [alibaba/open-code-review](https://github.com/alibaba/open-code-review) — 4 次（11-17 ~ 11-19）
- [backnotprop/plannotator](https://github.com/backnotprop/plannotator) — 3 次（11-15、11-16、11-19）
- [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) — 2 次（11-18、11-19）
- [tradermonty/claude-trading-skills](https://github.com/tradermonty/claude-trading-skills) — 2 次（11-18、11-19）
- [google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills) — 2 次（11-18、11-19）

**成長異常：**

- [dream-num/univer](https://github.com/dream-num/univer) — 前 4 日未在榜，本日首次出現即衝上增量第一（+7,248），屬爆發式新熱點。
- [GoogleChrome/modern-web-guidance-src](https://github.com/GoogleChrome/modern-web-guidance-src) — 11-17 首次上榜，隔日即跳升 +6,858，為本週第二高增量，成長速度異常快（總星僅 9.1k，屬早期爆發階段）。

**比對限制：** 歷史僅 5 天（11-15 起），無法判斷更長週期的連續上榜；`pookjw/HermesEnabler`、`kajisho5/ffmpeg-skill` 查無歷史紀錄，視為新進榜候選，非錯誤。
