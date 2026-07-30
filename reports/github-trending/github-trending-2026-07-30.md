# GitHub Trending Weekly Report — 2026-07-30

> 資料來源：[github.com/trending?since=weekly](https://github.com/trending?since=weekly) | 擷取時間：2026-07-30 08:00 CST

---

## 🔥 今日 Top 5

| # | Repo | Language | Stars (本週) |
|---|------|----------|-------------|
| 1 | [block/buzz](https://github.com/block/buzz) | Rust | 13,317 ⭐ |
| 2 | [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) | TypeScript | 9,420 ⭐ |
| 3 | [bojieli/ai-agent-book](https://github.com/bojieli/ai-agent-book) | Python | 8,998 ⭐ |
| 4 | [koala73/worldmonitor](https://github.com/koala73/worldmonitor) | TypeScript | 8,681 ⭐ |
| 5 | [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd) | Python | 5,544 ⭐ |

### Top 5 簡介

1. **[block/buzz](https://github.com/block/buzz)** — Block 推出的「蜂巢式通訊平台」(hive mind communication platform)，Rust 實作，本週狂吸 13,317 stars，空降榜首。社群對去中心化通訊基礎設施的關注度極高。

2. **[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)** — 免費 MIT AI Gateway，統一端點接入 290+ provider、500+ 模型（含 Claude、GPT、Gemini、DeepSeek、GLM 等），支援 CLAUDE、Codex、Cursor、Cline、Copilot。Quota-aware 自動 fallback 與 token 壓縮節省 15-95% token。連續上榜 5 天，持續高熱度。

3. **[bojieli/ai-agent-book](https://github.com/bojieli/ai-agent-book)** — 李博杰著《深入理解 AI Agent：设计原理与工程实践》開源書，附 PDF 與代碼。連續 5 天在榜，是中文 AI Agent 領域的現象級教材。

4. **[koala73/worldmonitor](https://github.com/koala73/worldmonitor)** — 即時全球情報儀表板：AI 驅動新聞聚合、地緣政治監控、基礎設施追蹤，統一使用界面。連續上榜 5 天。

5. **[ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd)** — 給 coding agent 的 ADHD 技能，防止它「把答案埋在廢話裡」而輸出 ADHD 友善的結果。Python 實作，連兩天爬榜，快速上升中。

---

## 📊 主題趨勢

1. **AI Agent 生態爆炸** — 本週同時出現「AI Agent 教材 (ai-agent-book)」、「Agent 技能 (adhd / i-have-adhd)」、「Agent SDK (OmniRoute)」與「Agent 瀏覽器 (ego-lite)」。從教育、工具鏈到運行時，Agent 全棧正在全面成型。

2. **開源替代品浪潮** — [CoreBunch/Instatic](https://github.com/CoreBunch/Instatic) 對標 Webflow/Framer/WordPress、[every-app/open-seo](https://github.com/every-app/open-seo) 對標 Semrush/Ahrefs、[oblien/openship](https://github.com/oblien/openship) 自託管部署平台、[alibaba/open-code-review](https://github.com/alibaba/open-code-review) 對標商業 code review 工具。「開源平替」策略成主流。

3. **Rust 從基礎設施向通訊/監控拓展** — [block/buzz](https://github.com/block/buzz)、[1jehuang/jcode](https://github.com/1jehuang/jcode)、[Pumpkin-MC/Pumpkin](https://github.com/Pumpkin-MC/Pumpkin)、[ruvnet/RuView](https://github.com/ruvnet/RuView) 涵蓋通訊協定、RAM 效率工具、Minecraft Server、Wi-Fi 空間感知。Rust 不再是 exclusive 系統語言，是"hard problem"領域的終極選擇。

4. **「自託管部署平台」熱度再起** — [oblien/openship](https://github.com/oblien/openship) 與 [CoreBunch/Instatic](https://github.com/CoreBunch/Instatic) 代表 self-hosted / agent-driven 部署的兩條路線，反映開發者對「用自己的機器跑自己的東西」的持續追求。

---

## 🎯 值得追蹤專案（3-5 個）

1. **[alibaba/open-code-review](https://github.com/alibaba/open-code-review)** 🆕 — 阿里巴巴開源的混合架構 code review 工具：決定性 pipeline + LLM Agent，精確行級註釋，內建經調教過的規則N + 同行評審（NPE、線程安全、XSS、SQL注入）。Go 實作，阿里級實戰驗證。本週首度登榜就直接 4,875 ⭐。

2. **[block/buzz](https://github.com/block/buzz)** 🆕 — 暫落 1 位，不可錯過。Block（原 Square）出品，Rust 通訊平台「蜂巢思想」。公開技術細節尚未完全釋出，但 17K total stars 說明大家對其方向的期待。

3. **[citrolabs/ego-lite](https://github.com/citrolabs/ego-lite)** 🆕 — 主打「AI Agent 的自帶瀏覽器」。直接共享你登錄的 Chrome 狀態給 Claude Code、Codex 等 agent，不打斷你自己的工作流程。零成本、零配置，概念新穎。

4. **[UditAkhourii/adhd](https://github.com/UditAkhourii/adhd)** — 與 ayghri/i-have-adhd 同屬 「adhd-for-agents」流派，但走的是 Tree-of-thought + pruning 路線——多種認知框架下扇形探索、評分、剪枝。基於 Claude & Codex Agent SDK，若是做創意/跨學科 agent 很值得一試。

5. **[earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad)** — 針對 CAD、機器人、硬體設計的 agent skill 集合。若你是硬體背景的開發者或對製造業 AI 應用感興趣，這範疇還在早期，超前部署好時機。

---

## 📈 歷史比對分析

### 新進榜（近 5 日首次出現）

| Repo | Language | Weekly Stars |
|------|----------|-------------|
| [block/buzz](https://github.com/block/buzz) | Rust | 13,317 ⭐ |
| [citrolabs/ego-lite](https://github.com/citrolabs/ego-lite) | JavaScript | 4,863 ⭐ |
| [alibaba/open-code-review](https://github.com/alibaba/open-code-review) | Go | 4,875 ⭐ |

### 連續上榜（近 5 日全勤）

- [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) (5/5，已成固定班底)
- [bojieli/ai-agent-book](https://github.com/bojieli/ai-agent-book) (5/5)
- [koala73/worldmonitor](https://github.com/koala73/worldmonitor) (5/5)
- [earendil-works/pi](https://github.com/earendil-works/pi) (5/5)
- [1jehuang/jcode](https://github.com/1jehuang/jcode) (5/5)
- [mattpocock/skills](https://github.com/mattpocock/skills) (5/5)

### 成長異常

- **[block/buzz](https://github.com/block/buzz)** 本週 13,317 ⭐ 是第二名 OmniRoute 的 1.4x → 代表 Block·Square 品牌力 + 去中心化話題的爆炸性結合
- **[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)** 5 天連續上榜，週星維持 9k+ => AI agent 工具剛需強勁且持續發酵
- **[ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd)** 從前天 (7/28) 入榜到今天 Top 5，三天飆速 => ADHD/效率輸出概念正高速擴散

---

## 📋 本週完整榜單

| # | Repo | Language | Weekly Stars |
|---|------|----------|-------------|
| 1 | [block/buzz](https://github.com/block/buzz) | Rust | 13,317 |
| 2 | [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) | TypeScript | 9,420 |
| 3 | [bojieli/ai-agent-book](https://github.com/bojieli/ai-agent-book) | Python | 8,998 |
| 4 | [koala73/worldmonitor](https://github.com/koala73/worldmonitor) | TypeScript | 8,681 |
| 5 | [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd) | Python | 5,544 |
| 6 | [earendil-works/pi](https://github.com/earendil-works/pi) | TypeScript | 4,979 |
| 7 | [alibaba/open-code-review](https://github.com/alibaba/open-code-review) | Go | 4,875 |
| 8 | [citrolabs/ego-lite](https://github.com/citrolabs/ego-lite) | JavaScript | 4,863 |
| 9 | [ruvnet/RuView](https://github.com/ruvnet/RuView) | Rust | 4,504 |
| 10 | [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch) | Python | 2,965 |
| 11 | [CoreBunch/Instatic](https://github.com/CoreBunch/Instatic) | TypeScript | 2,892 |
| 12 | [oblien/openship](https://github.com/oblien/openship) | TypeScript | 2,743 |
| 13 | [1jehuang/jcode](https://github.com/1jehuang/jcode) | Rust | 2,594 |
| 14 | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) | Python | 2,516 |
| 15 | [every-app/open-seo](https://github.com/every-app/open-seo) | TypeScript | 2,332 |
| 16 | [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) | JavaScript | 2,242 |
| 17 | [Pumpkin-MC/Pumpkin](https://github.com/Pumpkin-MC/Pumpkin) | Rust | 2,199 |
| 18 | [pingdotgg/t3code](https://github.com/pingdotgg/t3code) | TypeScript | 1,296 |
| 19 | [agegr/pi-web](https://github.com/agegr/pi-web) | TypeScript | 1,260 |
| 20 | [UditAkhourii/adhd](https://github.com/UditAkhourii/adhd) | TypeScript | 996 |

---

*報告自動生成。歷史比對基於 2026-07-25 至 2026-07-29 共 5 份日報。*