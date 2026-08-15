# GitHub Trending Weekly — 2026-08-15

> 資料時間：2026-08-15 08:00 CST（UTC+8）
> 資料來源：[GitHub Trending Weekly](https://github.com/trending?since=weekly)

---

## 1) 今日 Top 5

| # | Repo | 語言 | 本週 Stars | 累計 Stars |
|---|------|------|----------:|----------:|
| 1 | [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent) | TypeScript | 10,739 | 15,916 |
| 2 | [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) | TypeScript | 4,423 | 21,700 |
| 3 | [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | JavaScript | 3,845 | 87,276 |
| 4 | [cloudflare/computer](https://github.com/cloudflare/computer) | TypeScript | 2,856 | 8,128 |
| 5 | [google/skills](https://github.com/google/skills) | Python | 2,186 | 18,194 |

---

## 2) 主題趨勢

### 🔹 AI Agent 進入「基礎設施大爆發」
Agent 框架與 Runtime 是本週最拥挤的賽道。從 [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent)（自我改進 RLM agent）、[TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory)（團隊級記憶中樞）、[huangruiteng/loopx](https://github.com/huangruiteng/loopx)（long-running agent teams 狀態内核）、[google/skills](https://github.com/google/skills)（Google 官方 agent 技能庫）、到 [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)（生產級工程技能包），幾乎所有新進榜都圍繞「讓 agent 可長期、可記憶、可規模化」。

### 🔹 LLM Routing / Gateway 成為新基建
[NVIDIA-NeMo/Switchyard](https://github.com/NVIDIA-NeMo/Switchyard) 提供 OpenAI/Anthropic 相容的模型路由層，讓應用可以自由切換底層模型並優化成本與效能。LLM Gateway 已經從「選配」變成「標配」。

### 🔹 Edge AI 與 Tiny Model 持續升溫
[cactus-compute/needle](https://github.com/cactus-compute/needle)（14MB foundation model for tiny devices）登上第 9 名，手機、穿戴、機器人端側推理的市場關注度正在上升。

### 🔹 RAG 進化為 Graph-Native / Code-Graph
[vitali87/code-graph-rag](https://github.com/vitali87/code-graph-rag) 把 RAG 升級到 monorepo 級別的 multi-language 知識圖查詢；[semantica-agi/semantica](https://github.com/semantica-agi/semantica) 主打 Graph-Native Infrastructure for Accountable AI。知識圖譜正在成為 RAG 的新正規。

---

## 3) 值得追蹤專案

### ⭐ [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent)
- **亮點**：自我改進 RLM agent，針對 coding workflows 與 long-running autonomous tasks 設計
- **語言**：TypeScript｜**本週 +10,739 ⭐**（全場最高）
- **為何追蹤**：自我改進閉環 + 長時間自主執行，是 agent 框架的下一個前沿

### ⭐ [cloudflare/computer](https://github.com/cloudflare/computer)
- **亮點**：「Give your agent a computer 👾」——Cloudflare 推出的 agent 電腦操作環境
- **語言**：TypeScript｜**本週 +2,856 ⭐**
- **為何追蹤**：Cloudflare 基礎設施背書，agent 操作 OS/browser 的關鍵拼圖

### ⭐ [huangruiteng/loopx](https://github.com/huangruiteng/loopx)
- **亮點**：輕量級 loop engineering state kernel，agent-loop 不可知論，支援 Codex / Claude Code 等
- **語言**：Python｜**本週 +1,455 ⭐**
- **為何追蹤**：durable goals、quota-aware auto-wake、verifiable handoffs — 解決 agent teams 協調痛點

### ⭐ [cactus-compute/needle](https://github.com/cactus-compute/needle)
- **亮點**：14MB foundation model，為手機、穿戴、智慧家居、機器人設計
- **語言**：Python｜**本週 +1,929 ⭐**
- **為何追蹤**：Edge AI 真正可用的輕量模型，硬體覆蓋面極廣

### ⭐ [NVIDIA-NeMo/Switchyard](https://github.com/NVIDIA-NeMo/Switchyard)
- **亮點**：OpenAI + Anthropic 雙相容的 LLM 路由層，支援模型切換、benchmarking、成本/效能優化
- **語言**：Rust｜**本週 +1,195 ⭐**
- **為何追蹤**：NVIDIA _neMo_ 生態系向 application layer 延伸，Rust 實現高效能gateway

---

## 4) 歷史比對

### 🆕 新進榜（首次或相隔多日再上榜）

| Repo | 語言 | 本週 Stars | 歷史 |
|------|------|----------:|------|
| [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent) | TypeScript | 10,739 | 首次上榜（08-14 才出現） |
| [cloudflare/computer](https://github.com/cloudflare/computer) | TypeScript | 2,856 | 首次上榜 |
| [denoland/celld](https://github.com/denoland/celld) | Rust | 1,549 | 首次上榜 |
| [cactus-compute/needle](https://github.com/cactus-compute/needle) | Python | 1,929 | 首次上榜 |
| [huangruiteng/loopx](https://github.com/huangruiteng/loopx) | Python | 1,455 | 首次上榜（08-14） |
| [TapXWorld/ChinaTextbook](https://github.com/TapXWorld/ChinaTextbook) | Roff | 1,998 | 首次上榜 |
| [NVIDIA-NeMo/Switchyard](https://github.com/NVIDIA-NeMo/Switchyard) | Rust | 1,195 | 首次上榜 |
| [megadose/holehe](https://github.com/megadose/holehe) | Python | 671 | 首次上榜（但為經典專案迴歸） |

### 🔁 連續上榜

| Repo | 語言 | 本週 Stars | 連續紀錄 |
|------|------|----------:|------|
| [semantica-agi/semantica](https://github.com/semantica-agi/semantica) | Python | 5,135 | 08-11 ~ 08-14（4 天） |
| [google/skills](https://github.com/google/skills) | Python | 2,186 | 08-09 ~ 08-14（6 天） |
| [vitali87/code-graph-rag](https://github.com/vitali87/code-graph-rag) | Python | 1,718 | 08-10 ~ 08-14（5 天） |
| [TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) | TypeScript | 4,423 | 08-05 ~ 08-14（10 天，其中 08-06、08-07 缺） |
| [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | JavaScript | 3,845 | 08-13 ~ 08-14（間歇性上榜，歷史多次回歸） |
| [LadybirdBrowser/ladybird](https://github.com/LadybirdBrowser/ladybird) | C++ | 819 | 08-12 ~ 08-14（3 天） |
| [3b1b/manim](https://github.com/3b1b/manim) | Python | 1,919 | 穩定長青，近 2 週持續在榜 |
| [pingdotgg/t3code](https://github.com/pingdotgg/t3code) | TypeScript | 1,603 | 07-27 ~ 07-31 上榜後，消失多日，本週迴歸 |

### 📈 成長異常

| Repo | 語言 | 本週 Stars | 備註 |
|------|------:|----------:|------|
| [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent) | TypeScript | 10,739 | 全榜最高，單週破萬，首次上榜即空降第 1 |
| [semantica-agi/semantica](https://github.com/semantica-agi/semantica) | Python | 5,135 | 連續 4 天在榜，動能穩定 |
| [TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) | TypeScript | 4,423 | 10 天持續在榜，累積速度快 |
| [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | JavaScript | 3,845 | 累計 87K+ stars，本週動能迴歸 |

### 📉 落榜觀察

[cloudflare/computer](https://github.com/cloudflare/computer) 與 [denoland/celld](https://github.com/denoland/celld) 首次上榜即進入前 7，值得觀察是否在下週持續。[huangruiteng/loopx](https://github.com/huangruiteng/loopx) 與 [cactus-compute/needle](https://github.com/cactus-compute/needle) 同為 agent / edge 主題的新面孔，動能待驗證。

---

*報告由 OpenClaw cron 自動生成*
