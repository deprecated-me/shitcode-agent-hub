# GitHub Weekly Trending — 2026-09-25

## 1) 今日 Top 5

| # | Repo | 語言 | 本週 Stars | 總 Stars |
|---|------|------|-----------|----------|
| 1 | [alibaba/open-code-review](https://github.com/alibaba/open-code-review) | Go | +6,920 | 40.8K |
| 2 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | JavaScript | +6,193 | 266.9K |
| 3 | [stablyai/orca](https://github.com/stablyai/orca) | TypeScript | +6,547 | 77.5K |
| 4 | [Tencent/WeKnora](https://github.com/Tencent/WeKnora) | Go | +3,749 | 29.7K |
| 5 | [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | JavaScript | +3,345 | 98.9K |

## 2) 主題趨勢

1. **Agent Harness / Orchestration 持續霸榜，多 Agent 協作成主流** — [stablyai/orca](https://github.com/stablyai/orca)（+6,547）逆勢上升到第 3，[affaan-m/ECC](https://github.com/affaan-m/ECC)（+6,193）穩居第 2，[addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)（+3,345）蟬連 Top 5。Agent 編排、技能管理、效能調校三類工具同時在榜，顯示開發者從「單一 Agent 能力」轉向「Agent  fleet 管理」的架構升級。

2. **中國大廠 Agent 基礎建設雙引擎：Code Review + RAG 知識平台** — [alibaba/open-code-review](https://github.com/alibaba/open-code-review)（+6,920）連 12 天在榜穩居第 1，[Tencent/WeKnora](https://github.com/Tencent/WeKnora)（+3,749）連 7 天在榜。Go 語言在企業級 Agent 工具中持續主導，阿里巴巴的混合架構（deterministic + LLM Agent）Code Review 與 Tencent 的 RAG + 自主推理知識平台並行發展。

3. **Anthropic 生態系多點開花，Claude Code 衍生工具爆發** — [anthropics/claude-code](https://github.com/anthropics/claude-code)（+2,384）、[anthropics/financial-services](https://github.com/anthropics/financial-services)（+5,418）、[anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins)（+1,118）三 repo 同时在榜，外加 [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates)（+965）首次進榜。Anthropic 圍繞 Claude Code 的工具鏈正在形成獨立生態。

4. **Spec-driven Development 與 Agent Memory 成為新興賽道** — [Fission-AI/OpenSpec](https://github.com/Fission-AI/OpenSpec)（+1,415）、[vectorize-io/hindsight](https://github.com/vectorize-io/hindsight)（+3,363，首次進榜）、[akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory)（+1,243，首次進榜）三個專注於「Agent 方法論」的專案同時進榜。開發者開始系統化地解決 Agent 的規格定義、長期記憶、跨廠商交接等基礎問題。

## 3) 值得追蹤專案

1. **[vectorize-io/hindsight](https://github.com/vectorize-io/hindsight)** — Agent Memory That Learns，Python，27.8K 總 stars。首次進榜即衝到 +3,363 ⭐/週，提出「會學習的 Agent 記憶」概念，解決 Agent 在長期對話中的記憶瓶頸，方法論創新值得深入關注。

2. **[TencentCloud/Octop](https://github.com/TencentCloud/Octop)** — 自託管多用戶多 Agent 助手，Python，4.9K 總 stars。首次進榜（+1,608 ⭐/週），定位為企業級私有部署的 AI 助手平台，與 OpenSource 社群對「自託管 AI」的需求趨勢吻合。

3. **[davila7/claude-code-templates](https://github.com/davila7/claude-code-templates)** — Claude Code 配置與監控 CLI 工具，Python，31.7K 總 stars。首次進榜（+965 ⭐/週），隨著 Claude Code 用戶增長，周邊工具鏈開始爆發，此 repo 提供標準化管理模板。

4. **[akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory)** — 跨 Agent 廠商的長期記憶方案，Rust，8.3K 總 stars。首次進榜（+1,243 ⭐/週），解決不同 Agent CLI 之間的記憶交接問題，Rust 實現顯示對效能的追求。

5. **[JustVugg/colibri](https://github.com/JustVugg/colibri)** — 純 C 語言 MoE 推論引擎，零依賴、專家從硬碟串流，37.5K 總 stars。連 4 天在榜（+2,055 ⭐/週），在邊緣 / 本地 LLM 推論賽道持續穩定，Tiny engine + immense model 的設計哲學獨樹一幟。

## 4) 歷史比對

### 連續上榜

| Repo | 連續天數 | 趨勢 |
|------|---------|------|
| [affaan-m/ECC](https://github.com/affaan-m/ECC) | 🔄 連 17 天（09-06 起不間斷） | 09-24: 6,695 → 今日: 6,193，▼ -7.5%，穩定微降，持續刷新最長連續在榜紀錄 |
| [alibaba/open-code-review](https://github.com/alibaba/open-code-review) | 🔄 連 12 天（09-13 起） | 09-24: 9,833 → 今日: 6,920，▼ -29.6%，持續回落但穩居第 1 |
| [stablyai/orca](https://github.com/stablyai/orca) | 🔄 連 8 天（09-18 起） | 09-24: 6,435 → 今日: 6,547，▲ +1.7%，微幅上升，逆勢爬到第 3 |
| [Tencent/WeKnora](https://github.com/Tencent/WeKnora) | 🔄 連 7 天（09-19 起） | 09-24: 4,522 → 今日: 3,749，▼ -17.1%，穩定回落 |
| [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | 🔄 連 2 天（09-24 重返後） | 09-24: 3,867 → 今日: 3,345，▼ -13.5%，重返後維持動能 |
| [JustVugg/colibri](https://github.com/JustVugg/colibri) | 🔄 連 4 天（09-22 起） | 09-24: 2,739 → 今日: 2,055，▼ -25.0%，持續回歸穩定 |
| [anthropics/claude-code](https://github.com/anthropics/claude-code) | 🔄 連 2 天 | 09-24: 2,762 → 今日: 2,384，▼ -13.7%，微幅回落 |
| [anthropics/financial-services](https://github.com/anthropics/financial-services) | 🔄 連 2 天 | 09-24: 1,895 → 今日: 5,418，▲ +186%，爆炸性成長，週星翻倍再翻倍 |
| [Fission-AI/OpenSpec](https://github.com/Fission-AI/OpenSpec) | 🔄 連 2 天 | 09-24: 1,538 → 今日: 1,415，▼ -8.0%，穩定持平 |
| [superdesigndev/treg](https://github.com/superdesigndev/treg) | 🔄 連 2 天 | 09-24: 1,067 → 今日: 1,406，▲ +31.8%，持續成長 |

### 新進榜 / 首次進榜

| Repo | 說明 |
|------|------|
| [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) | 🆕 歷史檔案中首次出現，Agent Memory That Learns（+3,363 ⭐/週），首次進榜即高居第 6 |
| [TencentCloud/Octop](https://github.com/TencentCloud/Octop) | 🆕 歷史檔案中首次出現，自託管多用戶多 Agent 助手（+1,608 ⭐/週） |
| [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) | 🆕 歷史檔案中首次出現，Claude Code 配置與監控 CLI（+965 ⭐/週） |
| [akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory) | 🆕 歷史檔案中首次出現，跨 Agent 廠商長期記憶方案（+1,243 ⭐/週） |
| [cline/cline](https://github.com/cline/cline) | 🆕 歷史檔案中首次出現，Autonomous coding agent SDK（+855 ⭐/週） |
| [LibreChat-AI/LibreChat](https://github.com/LibreChat-AI/LibreChat) | 🆕 歷史檔案中首次出現，開源多模型 ChatGPT 替代方案（+743 ⭐/週） |
| [cilium/cilium](https://github.com/cilium/cilium) | 🆕 歷史檔案中首次出現，eBPF 網路安全與可觀測性（首次進榜，無昨日數據可比） |
| [pytorch/pytorch](https://github.com/pytorch/pytorch) | 🆕 歷史檔案中首次出現，經典深度學習框架重返 trending |
| [cloudflare/quiche](https://github.com/cloudflare/quiche) | 🆕 歷史檔案中首次出現，QUIC / HTTP/3 Rust 實現（+741 ⭐/週） |

### 成長異常

| Repo | 說明 |
|------|------|
| [anthropics/financial-services](https://github.com/anthropics/financial-services) | 📈 09-24: 1,895 → 今日: 5,418，▲ +186%，爆炸性成長，可能與金融業 AI 採用消息或功能更新有關 |
| [superdesigndev/treg](https://github.com/superdesigndev/treg) | 📈 09-24: 1,067 → 今日: 1,406，▲ +31.8%，OpenRouter for agent tools 持續吸引關注 |
| [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) | 📈 首次進榜即 +3,363，Agent Memory 賽道新玩家一鳴驚人 |

### 昨日（09-24）Top 5 變化

- 昨日第 1 [alibaba/open-code-review](https://github.com/alibaba/open-code-review)（+9,833）→ 今日第 1（+6,920），▼ -29.6%，回落但保住王座
- 昨日第 2 [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill)（+15,280）→ **跌出今日榜單**，昨日霸榜後急速冷卻
- 昨日第 3 [affaan-m/ECC](https://github.com/affaan-m/ECC)（+6,695）→ 今日第 2（+6,193），▼ -7.5%，穩定上升到第 2
- 昨日第 4 [stablyai/orca](https://github.com/stablyai/orca)（+6,435）→ 今日第 3（+6,547），▲ +1.7%，微幅上升
- 昨日第 5 [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)（+3,867）→ 今日第 5（+3,345），▼ -13.5%，持平
- [Tencent/WeKnora](https://github.com/Tencent/WeKnora) 昨日第 6（+4,522）→ 今日第 4（+3,749），排名上升
