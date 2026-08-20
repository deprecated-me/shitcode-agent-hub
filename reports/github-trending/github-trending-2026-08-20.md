# GitHub Weekly Trending — 2026-08-20

> 抓取時間：2026-08-20 08:00 (Asia/Taipei) | 來源：[GitHub Trending Weekly](https://github.com/trending?since=weekly)

---

## 1) 今日 Top 5

| # | Repo | 語言 | 本週 ⭐ | 累積 ⭐ |
|---|------|------|--------:|--------:|
| 1 | [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | HTML | 14,397 | 23,301 |
| 2 | [cactus-compute/needle](https://github.com/cactus-compute/needle) | Python | 3,838 | 7,807 |
| 3 | [semantica-agi/semantica](https://github.com/semantica-agi/semantica) | Python | 4,005 | 9,503 |
| 4 | [megadose/holehe](https://github.com/megadose/holehe) | Python | 1,704 | 13,731 |
| 5 | [basecamp/omarchy](https://github.com/basecamp/omarchy) | Shell | 2,208 | 26,774 |

---

## 2) 主題趨勢

1. **AI 開發者工具基礎設施成為新主軸** — [diagram-design](https://github.com/cathrynlavery/diagram-design) 純 HTML/SVG 的 zero-dependency 設計連續 5 天霸榜，[semantica](https://github.com/semantica-agi/semantica) 主打 graph-native context infrastructure，[macro-inc/macro](https://github.com/macro-inc/macro) 用 Rust 做 agent-native 團隊工作空間，AI 輔助開發正從「生成程式碼」往「理解、視覺化、管理既有程式碼庫」全面擴張。

2. **端側 / 小型模型題材持續加速** — [cactus-compute/needle](https://github.com/cactus-compute/needle) 14MB foundation model 鎖定手機、穿戴、機器人，連續 6 天在榜且**每一天都在成長**（1,929 → 3,838），是當前唯一動能未見停頓的 Top 5 專案。

3. **本地 LLM 工具鏈重新放量** — [unslothai/unsloth](https://github.com/unslothai/unsloth) 老字號 local training UI 本週爆出 3,338 ⭐，[AlexsJones/llmfit](https://github.com/AlexsJones/llmfit) 用 Rust 做 local model 相容性測試工具，[jundot/omlx](https://github.com/jundot/omlx) 為 Apple Silicon 做 continuous batching inference server，三者在榜形成「本地模型全端點」題材。

4. **知識圖譜 / Graph-native context 需求穩定升溫** — [semantica](https://github.com/semantica-agi/semantica) 連續 10 天在榜，[volcengine/OpenViking](https://github.com/volcengine/OpenViking) 新進榜即殺入前段（本週 1,659 ⭐、累積 30K），agent memory + knowledge RAG + skills 統一管理已成顯學。

---

## 3) 值得追蹤專案

- **[cactus-compute/needle](https://github.com/cactus-compute/needle)** — 14MB foundation model for tiny devices，連續 6 天成長（1,929 → 2,950 → 3,627 → 3,772 → 3,838），端側 AI 賽道的指標性專案。唯一 Top 5 仍在正向加速。

- **[volcengine/OpenViking](https://github.com/volcengine/OpenViking)** — Self-evolving Context Database for AI Agents，unify memory / RAG / skills。**歷史檔案查不到**，屬首次進榜。本週 1,659 ⭐ 但累積已 30K，動能強勁，值得觀察是否站穩。

- **[basecamp/omarchy](https://github.com/basecamp/omarchy)** — Beautiful, Modern & Opinionated Linux。DHH 出品。從 08-17 的 759 ⭐ 爆衝到今天 2,208 ⭐（約 3 倍增長），Shell 語言專案罕见地進入 Top 5，社群熱度異常。

- **[unslothai/unsloth](https://github.com/unslothai/unsloth)** — Local UI to run and train LLMs，支援 Qwen3.8、Kimi K3、DeepSeek-V4、FLUX 等。老專案因本地模型浪潮回歸，4 天在榜爆出 3,338 ⭐，波動大但絕對值高。

- **[public-apis/public-apis](https://github.com/public-apis/public-apis)** — 經典 free APIs 清單，**歷史檔案查不到**，屬新進榜候選。本週 10,183 ⭐、累積 466K，是所有列舉專案中絕對值最高者。

---

## 4) 歷史比對（新進榜 / 連續上榜 / 成長異常）

### 新進榜 / 首次記錄

| Repo | 備註 |
|------|------|
| [volcengine/OpenViking](https://github.com/volcengine/OpenViking) | 歷史檔案以完整 repo 名 `rg -F` 查無記錄，屬**首次進榜**。Python，1,659 ⭐/週，累積 30,156。 |
| [jundot/omlx](https://github.com/jundot/omlx) | 歷史檔案以完整 repo 名查無記錄，屬**首次進榜**。Python，1,102 ⭐/週，Apple Silicon LLM inference server。 |
| [CodebuffAI/freebuff](https://github.com/CodebuffAI/freebuff) | 歷史檔案以完整 repo 名查無記錄，屬**首次進榜**。TypeScript，1,037 ⭐/週，免費 coding agent。 |

### 連續上榜

| Repo | 連續天數 | 趨勢 |
|------|----------|------|
| [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | **5 天** (08-16 ~ 08-20) | 14,735 → 15,600 → 16,260 → 15,812 → 14,397，**連續 5 天登頂**但已連 3 天衰退（-2.8%、-9.1%），動能降溫中。 |
| [semantica-agi/semantica](https://github.com/semantica-agi/semantica) | **10 天** (08-11 ~ 08-20) | 2,009 → 2,712 → 3,585 → 4,073 → 5,135 → 5,339（峰值）→ 5,284 → 4,746 → 4,304 → 4,005，已從高點回落約 24%。 |
| [cactus-compute/needle](https://github.com/cactus-compute/needle) | **6 天** (08-15 ~ 08-20) | 1,929 → 2,950 → 3,627 → 3,772 → 3,838，**唯一仍在正向增長的 Top 5 專案**。 |
| [macro-inc/macro](https://github.com/macro-inc/macro) | **~7 天** (08-14 ~ 08-20) | 2,588 → 2,724 → 2,627 → 2,557，穩定但微幅降溫。 |
| [megadose/holehe](https://github.com/megadose/holehe) | **回歸進榜** | 08-15 首現（671）→ 08-16（1,059）→ 08-18（1,416）→ 08-19（1,568）→ 今日 1,704，本週重新放量。 |

### 成長異常

- **[basecamp/omarchy](https://github.com/basecamp/omarchy)** — 從 08-17 的 759 ⭐ → 今日 2,208 ⭐，**約 3 天增長 190%**，Shell 專案罕見爆衝。DHH 個人品牌 + 「Opinionated Linux」的精準定位帶動傳播。
- **[cactus-compute/needle](https://github.com/cactus-compute/needle)** — 唯一連續 6 天且**每一天都比前一天多**的 Top 5 專案，6 天內成長約 99%，端側小模型題材未見疲態。
- **[cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)** — 連 3 天衰退（16,260 → 15,812 → 14,397），雖仍霸榜但已流失約 11.5% 週動能，需觀察是否跌破 14K 後加速下滑。
- **[unslothai/unsloth](https://github.com/unslothai/unsloth)** — 波動型爆量，08-17（2,645）→ 08-18（3,329）→ 08-19（3,636）→ 今日 3,338，衝高回落約 8.2%。

---

> 歷史比對使用 `rg -F` 與完整 repo 名查詢本地 `reports/github-trending/`。`volcengine/OpenViking`、`jundot/omlx`、`CodebuffAI/freebuff` 在歷史檔案中無記錄，依規則視為新進榜候選。
