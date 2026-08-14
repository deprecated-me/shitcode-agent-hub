# GitHub Weekly Trending — 2026-08-14

> 報告產生時間：2026-08-14 08:00 CST | 追蹤區間：2026-05-23 至今 | 歷史比對使用 shell / `rg -F` / 完整 repo 名稱；查無結果已依規則視為未出現 / 新進榜候選。

---

## 1) 今日 Top 5

| # | Repo | 語言 | 本週 Stars | 總 Stars |
|---|------|------|-----------|----------|
| 1 | [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent) | TypeScript | 12,476 | 15,445 |
| 2 | [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) | TypeScript | 5,388 | 21,201 |
| 3 | [semantica-agi/semantica](https://github.com/semantica-agi/semantica) | Python | 4,073 | 6,613 |
| 4 | [zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill) | PowerShell | 5,270 | 24,926 |
| 5 | [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | JavaScript | 4,562 | 86,962 |

**補充說明（依 GitHub 排序的 Top 5）：**

1. **[PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent)** — Self-improving RLM agent for coding workflows and long-running autonomous tasks。TypeScript 實作，本週 12,476 stars，為本週黑馬。歷史比對中查無記錄，屬首次進榜且直接登頂，成長異常顯著。
2. **[semantica-agi/semantica](https://github.com/semantica-agi/semantica)** — Graph-Native Infrastructure for Context and Accountable AI Systems。Python，昨日 #5（3,585）→ 今日 #2（4,073），約 +13.6%，連續兩日上升。
3. **[google/skills](https://github.com/google/skills)** — Agent Skills for Google products and technologies。Python，昨日 #6（2,288）→ 今日 #3（2,359），約 +3.2%，穩定小幅升溫。
4. **[cloudflare/computer](https://github.com/cloudflare/computer)** — Give your agent a computer。TypeScript，昨日 #1（6,020）→ 今日 #4（3,599），約 -40.2%。週星大幅回落但仍在 Top 5，顯示 agent computer 題材仍在但強度減弱。
5. **[TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory)** — Team-level memory hub for AI Agents。TypeScript，昨日 #3（5,720）→ 今日 #5（5,388），約 -5.8%，小幅回落但維持前段。

---

## 2) 主題趨勢

1. **Agent Memory / Skills 生態持續主導週榜** — [TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory)、[google/skills](https://github.com/google/skills)、[zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill)、[virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill)、[addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) 同時在榜，覆蓋記憶中心、官方 skills 目錄、安全技能路由、技術書轉技能與生產級工程技能庫。Agent 的「記憶」與「技能化」仍是最大公認需求。

2. **Graph-native context / Code graph RAG 題材升溫** — [semantica-agi/semantica](https://github.com/semantica-agi/semantica) 從昨日 #5 升至 #2，[vitali87/code-graph-rag](https://github.com/vitali87/code-graph-rag) 也從 1,511 升至 1,628。可治理上下文、程式碼圖譜與 monorepo RAG 的需求明顯升溫，且持續多日。

3. **Agent 執行環境與長時間狀態管理題材分化** — [cloudflare/computer](https://github.com/cloudflare/computer) 週星從 6,020 大幅回落至 3,599（-40.2%），但仍在 Top 5；[huangruiteng/loopx](https://github.com/huangruiteng/loopx) 也從 2,509 降至 1,967（-21.6%）。Agent runtime / sandbox 題材仍在但熱度開始收斂。

4. **Skills 路由與安全技能題材進入「後高峰調整期」** — [zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill) 從昨日 5,573 降至 5,270，已從 10,400 高峰明顯回落但仍維持榜內前半段。安全 / 逆向 skills 題材進入穩定期。

---

## 3) 值得追蹤專案

1. **[PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent)** — Self-improving RLM agent for coding workflows and long-running autonomous tasks。TypeScript，首次進榜即以 12,476 stars/week 登頂，成長異常。RLM（Recursive Language Model）自我改進機制值得關注，可能代表 agent 從「被動執行」轉向「主動進化」的新階段。

2. **[semantica-agi/semantica](https://github.com/semantica-agi/semantica)** — Graph-native infrastructure for context and accountable AI systems。連續兩日上升，從 #5 → #2。Graph-based context management 是當前 agent 開發的核心痛點之一，此專案定位清晰。

3. **[firecrawl/pdf-inspector](https://github.com/firecrawl/pdf-inspector)** — Fast Rust library for PDF inspection, classification, and text extraction。Rust，昨日 #5（4,043）→ 今日 #8（3,251），雖持續回落但仍在前 10。PDF 結構化是文件 AI 管線的剛需，Rust 實作在效能上有顯著優勢。

4. **[addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)** — Production-grade engineering skills for AI coding agents。老牌 skills 庫（06 月長期在榜、07-11 曾回攻 Top 5），本次以 4,562 stars/week 回到 Top 5，顯示生產級工程技能庫仍有周期性需求。

5. **[vitali87/code-graph-rag](https://github.com/vitali87/code-graph-rag)** — The ultimate RAG for your monorepo。Python，從 1,511 升至 1,628（+7.7%），已連續多日成長。Monorepo 是大型企業開發的標配，code graph RAG 的實用性極高。

---

## 4) 歷史比對

### 新進榜 / 首次出現

| Repo | 今日排名 | 本週 Stars | 備註 |
|------|---------|-----------|------|
| [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent) | #1 | 12,476 | 首次進榜即登頂，RLM 自我改進 agent，成長異常 |
| [3b1b/manim](https://github.com/3b1b/manim) | #12 | 1,530 | 首次出現在本地歷史檔案，動畫引擎穩定吸收長尾關注 |
| [TapXWorld/ChinaTextbook](https://github.com/TapXWorld/ChinaTextbook) | #16 | 2,369 | 首次出現在本地歷史檔案，教育資源類持續有需求 |

### 連續上榜

| Repo | 連續天數 | 今日排名 | 本週 Stars | 趨勢 |
|------|---------|---------|-----------|------|
| [semantica-agi/semantica](https://github.com/semantica-agi/semantica) | 3+ 日 | #2 | 4,073 | 3,585 → 4,073（+13.6%），持續上升 |
| [cloudflare/computer](https://github.com/cloudflare/computer) | 2+ 日 | #4 | 3,599 | 6,020 → 3,599（-40.2%），大幅回落但仍前段 |
| [TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) | 9+ 日 | #5 | 5,388 | 5,720 → 5,388（-5.8%），小幅回落 |
| [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | 2+ 日 | #5（並列） | 4,562 | 4,817 → 4,562（-5.3%），老牌回溫 |
| [firecrawl/pdf-inspector](https://github.com/firecrawl/pdf-inspector) | 5+ 日 | #8 | 3,251 | 4,043 → 3,251（-19.6%），持續回落 |
| [virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill) | 11+ 日 | #10 | 3,789 | 3,983 → 3,789（-4.9%），緩慢下降 |
| [esengine/DeepSeek-Reasonix](https://github.com/esengine/DeepSeek-Reasonix) | 7+ 日 | #9 | 2,419 | 2,953 → 2,419（-18.1%），終端 coding agent 持續降溫 |
| [zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill) | 9+ 日 | #4 | 5,270 | 5,573 → 5,270（-5.4%），安全技能路由穩定 |
| [drawdb-io/drawdb](https://github.com/drawdb-io/drawdb) | 5+ 日 | #11 | 693 | 665 → 693（+4.2%），穩定小幅成長 |
| [google/skills](https://github.com/google/skills) | 6+ 日 | #3 | 2,359 | 2,288 → 2,359（+3.2%），穩定升溫 |
| [vitali87/code-graph-rag](https://github.com/vitali87/code-graph-rag) | 5+ 日 | #6 | 1,628 | 1,511 → 1,628（+7.7%），持續成長 |
| [huangruiteng/loopx](https://github.com/huangruiteng/loopx) | 4+ 日 | #7 | 1,967 | 2,509 → 1,967（-21.6%），明顯回落 |
| [LadybirdBrowser/ladybird](https://github.com/LadybirdBrowser/ladybird) | 2+ 日 | #13 | 775 | 743 → 775（+4.3%），穩定 |

### 成長異常

- **[PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent)** — 首次進榜即以 12,476 stars/week 登頂，遠超第二名（TencentDB-Agent-Memory 5,388）2.3 倍，屬異常強勢的新進榜專案。
- **[semantica-agi/semantica](https://github.com/semantica-agi/semantica)** — 連續兩日成長 +32.2% 與 +13.6%，從邊緣升至 #2，graph-native context 題材加速最明顯。
- **[cloudflare/computer](https://github.com/cloudflare/computer)** — 週星從 6,020 大幅回落至 3,599（-40.2%），雖仍在 Top 5 但強度顯著減弱，需觀察是否持續退燒。

---

*報告產生時間：2026-08-14 08:00 CST | 追蹤區間：2026-05-23 至今 | 歷史比對使用 shell / `rg -F` / 完整 repo 名稱；查無結果已依規則視為未出現 / 新進榜候選。今日 `web_fetch` Markdown 可讀取主要榜單，歷史比對均成功完成。*
