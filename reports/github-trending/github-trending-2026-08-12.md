# GitHub Trending 週榜摘要 — 2026-08-12

> 數據來源：[GitHub Trending (weekly)](https://github.com/trending?since=weekly)，抓取時間 2026-08-12 08:00 CST

---

## 1) 今日 Top 5

| # | Repo | 語言 | 本週 Stars | 總 Stars |
|---|------|------|----------:|---------:|
| 1 | [cloudflare/computer](https://github.com/cloudflare/computer) | TypeScript | 6,775 | 7,595 |
| 2 | [huangruiteng/loopx](https://github.com/huangruiteng/loopx) | Python | 2,687 | 4,159 |
| 3 | [firecrawl/pdf-inspector](https://github.com/firecrawl/pdf-inspector) | Rust | 5,367 | 14,696 |
| 4 | [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) | TypeScript | 7,017 | 19,874 |
| 5 | [semantica-agi/semantica](https://github.com/semantica-agi/semantica) | Python | 2,712 | 4,847 |

---

## 2) 主題趨勢

1. **Agent 執行環境與長時間狀態管理升到榜首層級** — [cloudflare/computer](https://github.com/cloudflare/computer) 首次出現在本地歷史檔案即登上 #1，主打「Give your agent a computer」；[huangruiteng/loopx](https://github.com/huangruiteng/loopx) 則從昨日 #1 守在 #2，代表 agent 不只需要模型與工具，也開始需要可控執行環境、durable state、quota-aware wake 與交接紀錄。

2. **Agent memory / skills 生態仍是本週主線** — [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory)、[zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill)、[google/skills](https://github.com/google/skills)、[virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill) 持續在榜，分別覆蓋記憶中心、技能路由、官方 skills 目錄與技術書知識轉技能。

3. **文件理解、程式碼圖譜與 accountable context 持續升溫** — [firecrawl/pdf-inspector](https://github.com/firecrawl/pdf-inspector) 連續三日位於前段，[semantica-agi/semantica](https://github.com/semantica-agi/semantica) 升入 Top 5，[vitali87/code-graph-rag](https://github.com/vitali87/code-graph-rag) 週星繼續放大，顯示「把 PDF、程式碼與上下文轉成可查、可治理知識結構」仍是強需求。

4. **成熟工具與基礎設施長尾穩定存在** — [drawdb-io/drawdb](https://github.com/drawdb-io/drawdb)、[Comfy-Org/ComfyUI](https://github.com/Comfy-Org/ComfyUI)、[LadybirdBrowser/ladybird](https://github.com/LadybirdBrowser/ladybird)、[goauthentik/authentik](https://github.com/goauthentik/authentik) 都在今日榜單內，代表資料庫建模、影像生成 GUI、瀏覽器與身份驗證等成熟開源工具仍能吸收週期性流量。

---

## 3) 值得追蹤專案

1. **[cloudflare/computer](https://github.com/cloudflare/computer)** — Cloudflare 推出的 agent computer 題材，TypeScript 實作，首次在本地歷史檔案出現即 #1，本週 6,775 stars。它把「agent 可操作電腦」包成平台能力，值得追蹤是否會成為 Cloudflare agent runtime / sandbox 生態的入口。

2. **[huangruiteng/loopx](https://github.com/huangruiteng/loopx)** — 輕量級 agent loop 狀態核心，支援長時間 agent team 的 durable goals、quota-aware auto-wake、可執行 todos、evidence logs 與 handoffs。昨日首次進榜即 #1，今日仍守 #2，說明長時間 agent operation 題材不是單日噪音。

3. **[TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory)** — 團隊級 Agent memory hub，將 conversations、docs、code 轉為 Chat Memory、Skill、LLM-Wiki、Code-Graph 等可治理資產。自 08-05 起連續多日位於前段，今日仍有 7,017 stars/week。

4. **[semantica-agi/semantica](https://github.com/semantica-agi/semantica)** — Graph-native infrastructure for context and accountable AI systems。昨日首次記錄在 #7，今日升至 #5，週星 2,009 → 2,712，和 memory / code graph / RAG 題材形成強呼應。

5. **[firecrawl/pdf-inspector](https://github.com/firecrawl/pdf-inspector)** — Rust PDF inspection / classification / text extraction library，可判斷掃描式與文字式 PDF 以做智慧路由。雖然週星從高峰回落，但仍連續三日 Top 3，文件 AI 管線題材熱度仍強。

---

## 4) 歷史比對與變動分析

### 新進榜 / 新進榜候選

| Repo | 今日排名 | 週星 | 歷史狀態 |
|------|---------:|-----:|----------|
| [cloudflare/computer](https://github.com/cloudflare/computer) | #1 | 6,775 | 歷史全檔 0 記錄，首次進榜候選 |
| [LadybirdBrowser/ladybird](https://github.com/LadybirdBrowser/ladybird) | #14 | 679 | 歷史全檔 0 記錄，成熟瀏覽器專案新進榜候選 |
| [goauthentik/authentik](https://github.com/goauthentik/authentik) | #15 | 2,003 | 昨日已有提及但非 Top 5，今日仍在榜，屬短期新進候選 |

### 連續上榜專案

| Repo | 已連續在榜 | 趨勢 |
|------|----------:|------|
| [virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill) | 10 次+（07-31 起） | 今日 #9，週星 4,155，技能化知識轉換題材仍穩 |
| [zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill) | 7 次+（08-05 起） | 今日 #6，週星 6,730，從 Top 5 外緣回落但仍是安全 / 逆向 skills 代表 |
| [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) | 7 次+（08-05 起） | 今日 #4，週星 7,017，agent memory 題材維持高位 |
| [lyogavin/airllm](https://github.com/lyogavin/airllm) | 6 次+（08-06 起） | 今日 #13，週星 2,798，端側大模型推理從前段降至中後段 |
| [esengine/DeepSeek-Reasonix](https://github.com/esengine/DeepSeek-Reasonix) | 5 次+（08-07 起） | 今日 #7，週星 3,517，終端 AI coding agent 熱度仍穩但較昨日回落 |
| [google/skills](https://github.com/google/skills) | 4 次+（08-09 起） | 今日 #8，週星 2,216，官方 Agent Skills 庫持續升溫 |
| [unclebob/swarm-forge](https://github.com/unclebob/swarm-forge) | 4 次+（08-08 起） | 今日 #10，週星 671，多 agent 協調工具維持低量穩定 |
| [drawdb-io/drawdb](https://github.com/drawdb-io/drawdb) | 3 次+（08-10 起） | 今日 #11，週星 597，資料庫圖表工具短期留在榜內 |
| [Comfy-Org/ComfyUI](https://github.com/Comfy-Org/ComfyUI) | 3 次+（08-09 起） | 今日 #12，成熟 diffusion GUI 工具仍有長尾流量；今日 `web_fetch` Markdown 未提供語言與週星欄位 |

### 成長異常

| Repo | 變化 | 分析 |
|------|------|------|
| [cloudflare/computer](https://github.com/cloudflare/computer) | 歷史 0 記錄 → 今日 #1，6,775 週星 | Cloudflare 品牌加持與 agent computer 題材同時發酵，屬今日最大新進異常 |
| [semantica-agi/semantica](https://github.com/semantica-agi/semantica) | 2,009 → 2,712，約 +35.0% | 昨日首次記錄後快速升入 Top 5，graph-native context 題材加速 |
| [vitali87/code-graph-rag](https://github.com/vitali87/code-graph-rag) | 920 → 1,189，約 +29.2% | monorepo graph RAG 連續放大，從低量新進轉為可追蹤成長 |
| [google/skills](https://github.com/google/skills) | 2,159 → 2,216，約 +2.6% | 官方 skills 目錄熱度仍在高位，增速放緩但未衰退 |
| [firecrawl/pdf-inspector](https://github.com/firecrawl/pdf-inspector) | 8,641 → 7,143 → 5,367 | 首次爆發後連續回落，但仍連三日 Top 3，文件 AI 題材仍強 |
| [lyogavin/airllm](https://github.com/lyogavin/airllm) | 5,711 → 5,129 → 4,042 → 2,798 | 端側推理題材明顯降溫，從 Top 5 附近退到中後段 |

### 從昨日榜單中消失的專案

| Repo | 昨日狀態 | 今日狀態 |
|------|----------|----------|
| [microsoft/AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) | 昨日 #13，週星 4,028 | 跌出今日 `web_fetch` 可見榜單 |
| [DataExpert-io/data-engineer-handbook](https://github.com/DataExpert-io/data-engineer-handbook) | 昨日 #17，週星 781 | 跌出今日 `web_fetch` 可見榜單 |
| [usekaneo/kaneo](https://github.com/usekaneo/kaneo) | 昨日 #12，週星 1,396 | 跌出今日 `web_fetch` 可見榜單 |

---

*報告產生時間：2026-08-12 08:00 CST | 追蹤區間：2026-05-23 至今 | 歷史比對使用 shell / `rg -F` / 完整 repo 名稱；查無結果已依規則視為未出現 / 新進榜候選。今日 `web_fetch` Markdown 可讀取主要榜單，但 [Comfy-Org/ComfyUI](https://github.com/Comfy-Org/ComfyUI) 區塊缺少語言、總星與本週 stars，因此該項目的成長比對不足。*
