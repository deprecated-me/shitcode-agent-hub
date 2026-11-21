# GitHub Trending 週報 — 2026-11-21

來源：<https://github.com/trending?since=weekly>
抓取時間：2026-11-21 08:00 (Asia/Taipei)

## 1) 今日 Top 5（依本週 stars 增量排序）

| # | Repo | 語言 | 本週 stars | 總 stars |
|---|------|------|-----------|---------|
| 1 | [dream-num/univer](https://github.com/dream-num/univer) | TypeScript | +7,539 | 30,939 |
| 2 | [GoogleChrome/modern-web-guidance-src](https://github.com/GoogleChrome/modern-web-guidance-src) | TypeScript | +5,224 | 9,521 |
| 3 | [alibaba/open-code-review](https://github.com/alibaba/open-code-review) | Go | +4,457 | 54,766 |
| 4 | [meta/astryx](https://github.com/meta/astryx) | TypeScript | +4,131 | 31,341 |
| 5 | [backnotprop/plannotator](https://github.com/backnotprop/plannotator) | TypeScript | +3,555 | 13,888 |

其餘上榜（依榜單順序）：

- [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) — Python — +3,788
- [tradermonty/claude-trading-skills](https://github.com/tradermonty/claude-trading-skills) — Python — +3,471
- [ag-ui-protocol/ag-ui](https://github.com/ag-ui-protocol/ag-ui) — TypeScript — +3,621
- [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) — TypeScript — +3,306
- [kajisho5/ffmpeg-skill](https://github.com/kajisho5/ffmpeg-skill) — Python — +3,268
- [google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills) — TypeScript — +2,152
- [we-promise/sure](https://github.com/we-promise/sure) — Ruby — +2,476
- [pookjw/HermesEnabler](https://github.com/pookjw/HermesEnabler) — Objective-C — +582

## 2) 主題趨勢

- **Agent 技能包（Skills）全面占榜，垂直化與平台化並行**：13 個上榜專案中逾半直接服務 coding agent。除了通用的 [google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills)（Agent Skills 開放標準庫，搭配 Stitch MCP），垂直技能包持續爆量——[tradermonty/claude-trading-skills](https://github.com/tradermonty/claude-trading-skills)（交易）、[kajisho5/ffmpeg-skill](https://github.com/kajisho5/ffmpeg-skill)（42 個 FFmpeg 工具 + MCP server）、[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)（Reddit/X/YT/HN/Polymarket 跨平台研究摘要）。Agent Skills / MCP 已從品類變成基礎設施。
- **「給 agent 用的」UI / 設計系統與協定成型**：[meta/astryx](https://github.com/meta/astryx) 標榜「agent ready」設計系統、[GoogleChrome/modern-web-guidance-src](https://github.com/GoogleChrome/modern-web-guidance-src) 把 web 最佳實踐打包成 agent 可讀指引、[ag-ui-protocol/ag-ui](https://github.com/ag-ui-protocol/ag-ui) 定義 Agent-User 互動協定。前端正在為「agent 作為使用者」重做一層，且開始出現標準化的互動協定。
- **AI 程式審查與安全工具進入主流採用**：[alibaba/open-code-review](https://github.com/alibaba/open-code-review) 以確定性 pipeline + LLM Agent 混合架構做行級審查，內建多語言規則（NPE、thread-safety、XSS、SQL injection），本週 +4,457 stars，總星已破 5.4 萬，屬實戰級採用。企業需求從「AI 能做什麼」轉向「AI 做得是否可信、安全」。
- **Office / 文件處理成為 agent 新戰場**：[dream-num/univer](https://github.com/dream-num/univer) 以 Office SDK（編輯、計算、協作、檔案處理）同時面向「人」與「AI agent」，本週兩度拿下增量第一（+7,248 → +7,539）。文件生產力是 agent 落地的高頻場景，競爭正在加劇。

## 3) 值得追蹤專案

- [dream-num/univer](https://github.com/dream-num/univer) — 30.9k stars，本週增量第一（+7,539），連續兩日登頂。Office SDK 同時面向「人」與「AI agent」，可擴充開源核心，文件代理（document agent）賽道的領跑者。
- [alibaba/open-code-review](https://github.com/alibaba/open-code-review) — 54.8k stars，阿里內部規模驗證，OpenAI/Anthropic 相容，規則集可擴充。若導入 AI code review，這是目前最成熟的開源選項。
- [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) — 71.4k stars（本榜最高總星），跨平台（Reddit/X/YT/HN/Polymarket）研究 + 有根據摘要，可作為深度研究的起點。
- [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) — 58.5k stars，官方出品，直接讓 agent 驅動 DevTools。瀏覽器自動化與 agent 結合的標準零件。
- [backnotprop/plannotator](https://github.com/backnotprop/plannotator) — 13.9k stars，把 plan / annotate / review / 回饋送回 agent 做成單一工作區，補上「人介入 agent 流程」的缺口。

## 4) 歷史比對

比對範圍：`reports/github-trending/` 現有 6 份歷史報告（2026-11-15 ~ 2026-11-20）。

**新進榜（歷史檔案查無，首次出現）：**

- 無。本週所有上榜 repo 皆曾在歷史報告中出現。

**連續上榜（近 6 日每日皆出現）：**

- [meta/astryx](https://github.com/meta/astryx) — 11-15 ~ 11-20 連續 6 日（但成長持續降溫：+13,660 → +13,501 → +10,939 → +8,700 → +6,250 → +4,977 → +4,131）
- [we-promise/sure](https://github.com/we-promise/sure) — 11-16 ~ 11-20 連續 5 日（+4,556 → +4,679 → +4,786 → +3,866 → +3,226 → +2,476）

**長期在榜（近 6 日出現 ≥4 次）：**

- [GoogleChrome/modern-web-guidance-src](https://github.com/GoogleChrome/modern-web-guidance-src) — 5 次（11-17 ~ 11-20）
- [alibaba/open-code-review](https://github.com/alibaba/open-code-review) — 5 次（11-17 ~ 11-20）
- [backnotprop/plannotator](https://backnotprop/plannotator) — 4 次（11-15、11-16、11-19、11-20）
- [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) — 3 次（11-18 ~ 11-20）
- [tradermonty/claude-trading-skills](https://github.com/tradermonty/claude-trading-skills) — 3 次（11-18 ~ 11-20）
- [dream-num/univer](https://github.com/dream-num/univer) — 2 次（11-19、11-20）
- [google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills) — 3 次（11-18 ~ 11-20）
- [ag-ui-protocol/ag-ui](https://github.com/ag-ui-protocol/ag-ui) — 2 次（11-19、11-20）
- [kajisho5/ffmpeg-skill](https://github.com/kajisho5/ffmpeg-skill) — 2 次（11-20、11-21）
- [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) — 2 次（11-19、11-20）
- [pookjw/HermesEnabler](https://github.com/pookjw/HermesEnabler) — 2 次（11-20、11-21）

**跌出榜單（前日在榜、本日未出現）：**

- [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) — 11-15 ~ 11-18 連續 4 日後跌出
- [anthropics/skills](https://github.com/anthropics/skills) — 11-15 ~ 11-18 連續 4 日後跌出
- [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser) — 11-15 ~ 11-19 連續 5 日後跌出（11-08 起曾連續 12 天在榜）
- [google/elephant-goldfish-model](https://github.com/google/elephant-goldfish-model) — 11-15 ~ 11-17 後跌出
- [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis) — 11-15 ~ 11-19 後跌出
- [openai/codex-security](https://github.com/openai/codex-security) — 11-17 ~ 11-19 後跌出
- [QwenLM/qwen-code](https://github.com/QwenLM/qwen-code) — 11-17 單日短暫上榜後跌出
- [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter) — 11-18 ~ 11-19 後跌出
- [sherlock-project/sherlock](https://github.com/sherlock-project/sherlock) — 11-15 ~ 11-16 後跌出

**成長異常：**

- [dream-num/univer](https://github.com/dream-num/univer) — 11-19 首次上榜即衝上當日增量第一（+6,840），本日再登頂（+7,539），連續兩日爆發，屬新熱點。
- [meta/astryx](https://github.com/meta/astryx) — 連續 6 日在榜但成長單調遞減（+13,660 → +13,501 → +10,939 → +8,700 → +6,250 → +4,977 → +4,131），熱度明顯降溫，值得觀察是否跌破榜外。
- [GoogleChrome/modern-web-guidance-src](https://github.com/GoogleChrome/modern-web-guidance-src) — 從 +7,257（11-19 登頂）→ +6,858 → +5,224，連三日高增量後開始回落。
- [we-promise/sure](https://github.com/we-promise/sure) — 連續 5 日在榜但成長從 +4,786 降至 +2,476，降溫速度最快。

**比對限制：** 歷史僅 6 天（11-15 起），無法判斷更長週期的連續上榜；本次無查無歷史紀錄的 repo。
