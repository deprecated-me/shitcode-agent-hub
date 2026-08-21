# GitHub Trending Weekly Report - 2026-08-21

來源：https://github.com/trending?since=weekly

> 今日資料優先採用 `web_fetch` 擷取的 GitHub Trending weekly 頁面。歷史比對使用本地 shell 指令 `rg -F` 與完整 repo 名搜尋 `reports/github-trending/`，查無結果依規則視為「未出現 / 新進榜候選」，不視為錯誤。

## 1) 今日 Top 5

| Rank | Repo | 語言 | 本週 stars |
|---:|---|---|---:|
| 1 | [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | HTML | 11,325 |
| 2 | [volcengine/OpenViking](https://github.com/volcengine/OpenViking) | Python | 2,444 |
| 3 | [basecamp/omarchy](https://github.com/basecamp/omarchy) | Shell | 2,395 |
| 4 | [cactus-compute/needle](https://github.com/cactus-compute/needle) | Python | 3,409 |
| 5 | [semantica-agi/semantica](https://github.com/semantica-agi/semantica) | Python | 3,674 |

## 2) 主題趨勢

1. **Agent memory / context 基礎設施仍是主軸** — [volcengine/OpenViking](https://github.com/volcengine/OpenViking) 主打 self-evolving context database，整合 agent memory、knowledge RAG 與 skills；[semantica-agi/semantica](https://github.com/semantica-agi/semantica) 則持續以 graph-native context / accountable AI 留在前段。這條線已從單純 RAG 工具轉向「可治理、可演化的 agent 長期上下文」。
2. **AI 開發者工具與視覺輸出仍有強傳播力** — [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) 連續多日在榜首，雖然本週 stars 從前幾日高點回落到 11,325，但仍遠高於大多數新進專案。純 HTML/SVG、無依賴、面向 Claude Code / Codex 的定位非常清楚。
3. **端側小模型與本地推理持續升溫** — [cactus-compute/needle](https://github.com/cactus-compute/needle) 以 14MB foundation model 鎖定手機、穿戴、智慧家居與機器人，連續多日維持 Top 5。搭配榜單後段的 local AI / inference 題材，端側部署正在從概念轉成可試用專案。
4. **作業系統 / 個人工作環境也能引爆社群** — [basecamp/omarchy](https://github.com/basecamp/omarchy) 以 Shell 專案進入 Top 5，DHH 品牌與「opinionated Linux」定位讓它在 AI 題材主導的榜單中仍能快速吸收注意力。

## 3) 值得追蹤專案

- **[volcengine/OpenViking](https://github.com/volcengine/OpenViking)** — Self-evolving Context Database for AI Agents。昨日歷史檔案才首次記錄，今日已升至頁面第 2，本週 2,444 stars，和 agent memory / RAG / skills 統一管理的需求高度重疊。
- **[cactus-compute/needle](https://github.com/cactus-compute/needle)** — 14MB foundation model for tiny devices，本週 3,409 stars。雖較昨日 3,838 回落，但仍維持 Top 5，是端側 AI 題材最穩定的觀察樣本。
- **[basecamp/omarchy](https://github.com/basecamp/omarchy)** — Beautiful, Modern & Opinionated Linux，本週 2,395 stars。Shell 專案能進 Top 5 並不常見，代表個人開發環境與 Linux 發行體驗仍有強烈社群話題性。
- **[semantica-agi/semantica](https://github.com/semantica-agi/semantica)** — Graph-Native Infrastructure for Context and Accountable AI Systems，本週 3,674 stars。雖然 weekly stars 自高點回落，但已連續多日上榜，足以作為 graph-native context infrastructure 的指標。
- **[NVIDIA-NeMo/Switchyard](https://github.com/NVIDIA-NeMo/Switchyard)** — LLM 應用模型路由層，保留 OpenAI / Anthropic API 相容性，本週 932 stars。雖不在 Top 5，但企業級多模型 routing / benchmarking / cost optimization 是長線需求。

## 4) 歷史比對

### 新進榜 / 新進榜候選

| Repo | 判讀 |
|---|---|
| [volcengine/OpenViking](https://github.com/volcengine/OpenViking) | 08-20 歷史報告首次記錄為新進榜，今日升至 Top 2；本週 stars 1,659 -> 2,444，單日約 +47.3%。 |
| [basecamp/omarchy](https://github.com/basecamp/omarchy) | 08-17 首次記錄，08-20 進 Top 5，今日仍維持 Top 3；759 -> 2,208 -> 2,395，Shell 專案熱度異常強。 |
| [NVIDIA-NeMo/Switchyard](https://github.com/NVIDIA-NeMo/Switchyard) | 08-15 首次記錄，今日仍在榜單前段但不在 Top 5；本週 stars 已從 1,195 降至 932，屬高位回落。 |

### 連續上榜

| Repo | 連續性 | 觀察 |
|---|---:|---|
| [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | 連續約 6 天 | 14,735 -> 15,600 -> 16,260 -> 15,812 -> 14,397 -> 11,325；仍居榜首，但 rolling window 已明顯退燒。 |
| [semantica-agi/semantica](https://github.com/semantica-agi/semantica) | 連續約 11 天 | 08-11 首次記錄後一路留榜，峰值約 5,339，今日 3,674；graph-native context 題材仍穩。 |
| [cactus-compute/needle](https://github.com/cactus-compute/needle) | 連續約 7 天 | 1,929 -> 2,950 -> 3,627 -> 3,772 -> 3,838 -> 3,409；今日首次明顯回落，但仍保住 Top 5。 |
| [basecamp/omarchy](https://github.com/basecamp/omarchy) | 至少 5 天內多次記錄 | 08-17 的 759 -> 08-20 的 2,208 -> 今日 2,395，仍在加速。 |

### 成長異常

- **[volcengine/OpenViking](https://github.com/volcengine/OpenViking)** — 08-20 記錄 1,659，今日 2,444，單日增加 785，約 +47.3%。agent context database 題材與近期榜單主軸完全吻合。
- **[basecamp/omarchy](https://github.com/basecamp/omarchy)** — 08-17 記錄 759，08-20 為 2,208，今日 2,395；短期約 3.2 倍，且以 Shell 專案進 Top 3，屬明顯異常熱度。
- **[cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)** — 從 08-18 高點 16,260 降至今日 11,325，約 -30.4%，但仍排第 1；屬爆紅後 rolling window 回落，不代表需求消失。
- **[cactus-compute/needle](https://github.com/cactus-compute/needle)** — 連續多日增長後從 3,838 回落到 3,409，約 -11.2%；端側小模型仍在 Top 5，但加速段可能暫告一段落。

> 歷史比對沒有中止性失敗；部分 repo 在歷史檔案中查無完整名稱時，已依規則列為未出現 / 新進榜候選。
