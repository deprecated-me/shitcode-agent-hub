# GitHub Trending Weekly 摘要 (2026-06-17)

## 1) 今日 Top 5

| # | Repo | 語言 | 本週 Stars |
|---|------|------|-----------|
| 1 | [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | Shell | 11,431 |
| 2 | [apple/container](https://github.com/apple/container) | Swift | 10,896 |
| 3 | [chopratejas/headroom](https://github.com/chopratejas/headroom) | Python | 9,766 |
| 4 | [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) | Python | 7,226 |
| 5 | [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) | Python | 6,427 |

## 2) 主題趨勢

- **Agent Skills 生態全面爆發**：本週 Top 5 中有 3 個直接圍繞「Skills」——[addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) (61K+ 總 stars，生產級工程技能庫)、[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) (跨平台主題研究)、[NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) (安全掃描)。加計 [phuryn/pm-skills](https://github.com/phuryn/pm-skills) (100+ agentic skills 市場)，skills 已從「擴充插件」演變為完整生態系。
- **Token 成本優化與上下文工程**：[chopratejas/headroom](https://github.com/chopratejas/headroom) 以 9,766 本週 stars 維持高位，主打壓縮 tool output / logs / RAG chunks 達 60-95% token 節省。[LMCache/LMCache](https://github.com/LMCache/LMCache) 提供 KV Cache 層加速 LLM 推論，雖然本週僅 709 stars，但「降低 LLM 運算成本」的需求正從邊緣進入主流。
- **AI 安全透明度升溫**：[NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) 掃描 skill 漏洞與惡意模式、[asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) (42K+ 總 stars，收集各平台 system prompt)、[x1xhlol/system-prompts-and-models-of-ai-tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools) (涵蓋 27+ 工具的 system prompt 與模型資訊) 形成「安全 + 透明」三重奏，反映社群對 Agent 安全風險的集體意識。
- **本地化與開源替代方案加速**：[apple/container](https://github.com/apple/container) 以 Swift 實現 Mac 輕量 VM 跑 Linux container (10,896 本週 stars)、[lfnovo/open-notebook](https://github.com/lfnovo/open-notebook) 作為 Notebook LM 開源實現 (31K+ 總 stars)、[refactoringhq/tolaria](https://github.com/refactoringhq/tolaria) Markdown 知識庫桌面應用——開發者正積極尋找不依賴雲端專有方案的本地化替代。

## 3) 值得追蹤專案

- [iptv-org/iptv](https://github.com/iptv-org/iptv) — TypeScript — 6,246 本週 stars。全球 IPTV 頻道合集，124K+ 總 stars，本週新進 Top 10。在串流媒體與 cord-cutting 趨勢下，此專案持續吸引大量用戶貢獻頻道列表。
- [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) — Python — 5,190 本週 stars。NVIDIA 官方的 AI agent skill 安全掃描工具，連續 4 天在榜，反映安全審計正成為 skill 生態的必要基礎設施。
- [LMCache/LMCache](https://github.com/LMCache/LMCache) — Python — 709 本週 stars。LLM KV Cache 加速層，雖然本週 stars 不高，但「context engineering / token optimization」與 [chopratejas/headroom](https://github.com/chopratejas/headroom) 形成上下游呼應，值得觀察熱度是否跟隨 headroom 攀升。
- [chatwoot/chatwoot](https://github.com/chatwoot/chatwoot) — Ruby — 1,930 本週 stars。開源客服平台，37K+ 總 stars，替代 Intercom / Zendesk。在 AI chatbot 浪潮下，chatwoot 正整合 agent 能力，本週重新進入 trending 值得一追。
- [x1xhlol/system-prompts-and-models-of-ai-tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools) — (未標示語言) — 收集 27+ 主流 AI 工具 (Augment Code、Claude Code、Cursor、Devin、Manus、Replit 等) 的 system prompt、內部工具與 AI 模型資訊，與 [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) 互補，是理解 AI 工具「黑盒」的重要參考。

## 4) 歷史比對分析

- **新進榜（本週首次進入 Top 5）**：
    - [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) — 昨日排名第 6 (5,873 stars)，本週以 6,427 stars 擠進 Top 5，成長明顯。
    - [iptv-org/iptv](https://github.com/iptv-org/iptv) — 過去 30 天歷史報告中查無結果，本次首度進入 trending 頁面前列 (6,246 本週 stars)。
- **連續上榜**：
    - [apple/container](https://github.com/apple/container) — 連續 5 天進入 Top 5，本週 10,896 stars (昨日 10,541)，穩定上升。
    - [chopratejas/headroom](https://github.com/chopratejas/headroom) — 自 2026-06-03 起已連續 15 份報告在榜，本月最持久專案，本週 9,766 stars (昨日 10,660) 略有回落但仍維持高檔。
    - [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) — 本週 11,431 stars 創新高 (昨日 11,088)，60K+ 總 stars 里程碑後持續攀升，首度登上週冠軍。
    - [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) — 已連續 9 份報告位居前列，本週 7,226 stars (昨日 9,676) 回落但仍穩居第 4。
    - [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) — 連續 4 天在榜 (06-14 起)，5,190 本週 stars (昨日 4,633)，持續成長。
    - [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) — 連續 8 天在榜，32K+ 總 stars。
    - [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) — 42K+ 總 stars，持續在榜，熱度不減。
- **成長異常**：
    - [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) 本週 11,431 stars，較昨日 11,088 跳升 343 stars，在 60K+ 總量級下仍保持高速增長，顯示「production-grade agent skills」需求仍在加速擴張。
    - [chopratejas/headroom](https://github.com/chopratejas/headroom) 本週 9,766 stars，較昨日 10,660 回落約 894 stars，結束連續創新高趨勢，可能進入常態成長階段。
    - [lfnovo/open-notebook](https://github.com/lfnovo/open-notebook) 本週 2,873 stars (昨日 3,179)，連續兩天回落，但 31K 總量仍在前 20 名內，開源 Notebook LM 賽道競爭可能加速。
