# GitHub 本週熱門專案 — 2026-07-10（週五）

## 1) 今日 Top 5（repo、語言、本週 stars）

| # | Repo | 語言 | 本週 Stars | 簡介 |
|---|------|------|-----------|------|
| 1 | [MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search) | TypeScript | 13,847 | AI 求職框架——基於 Claude Code，填 profile → 自動評測職缺、客製 CV + Cover Letter、模擬面試 |
| 2 | [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) | Rust | 8,885 | 100% 本地 AI 會議記錄助手，4× 加速 Parakeet/Whisper 逐字稿 + Ollama 摘要 |
| 3 | [usestrix/strix](https://github.com/usestrix/strix) | Python | 8,370 | 開源 AI 滲透測試工具，自動發現並修復應用程式漏洞 |
| 4 | [facebook/astryx](https://github.com/facebook/astryx) | TypeScript | 4,087 | Meta 開源 fully-customizable、agent-ready 設計系統 |
| 5 | [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) | JavaScript | 7,149 | 收集 Anthropic/OpenAI/Google/xAI/Cursor 等各大平台的系統提示——AI 透明度工具 |

> Top 5 再度大換血：[MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search) 昨日未出現在 Top 22 榜單中，今日強勢回歸空降 #1 並創下 13,847 新高（▲ +157% 從 07-08 的 5,363 暴漲）；[asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) 昨日 full list → 今日 #5，持續爆發（07-09: 6,182 → 07-10: 7,149，▲ +15.6%）。[openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc) 與 [alibaba/page-agent](https://github.com/alibaba/page-agent) 被擠出 Top 5 但仍穩定在 full list 內。

## 2) 主題趨勢

- **Agent 應用場域再度擴張：求職、會議記錄成為新爆破點**：[MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search) 從 07-08 首次進榜 → 昨日消失 → 今日空單週最高 13,847，反映 AI Agent 正從工程師生產力工具**急劇擴展到大眾日常場景**（求職、面試、職涯規劃）。搭配 [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)（本地 AI 會議記錄）連續 4 日穩居前三、動能穩定攀高，Agent 已成功滲透「創作 → 商業 → 個人」三層級場景。

- **隱私優先 × 端側 AI 成為主流標配而非利基選項**：[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)（Rust、100% 本地、0 雲端）自 07-06 首次進榜以來**連續 5 日上升**（2,972 → 5,769 → 7,349 → 8,366 → 8,885），增幅超过 3×，是本榜目前上升最穩定的專案。[huggingface/speech-to-speech](https://github.com/huggingface/speech-to-speech)（開源本地語音 agent）持續在 full list，顯示「local-first」已从早期采纳者为唯一受众，轉為一般用户的明确偏好。

- **AI Agent 安全與合規需求具體化**：[asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) 回歸 Top 5（7,149 ⭐），加上 [TencentCloud/CubeSandbox](https://github.com/TencentCloud/CubeSandbox)（腾讯 agent sandbox，2,284 ⭐），反映 Agent 大規模部署後，**系統透明度與安全隔離**正成為不可回避的刚需要求——「用 agent」已經過半，「管 agent」的基建正在跟進。

- **跨 Agent 互操作與多模型路由形成兩條主線**：[openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc)（Codex↔Claude Code 跨平台）代表「跨 agent 協作」產品化；[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)（231+ 模型供應商單端點）代表「多模型路由 + Token 優化」。二者並存说明 Agent 生態正从「單一工具競爭」走向「系統層級標準化」。

## 3) 值得追蹤專案

1. **[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)** — Rust，8,885 stars/week，自 07-06 首次進榜以來連續 5 日攀升（2,972 → 8,885，▲ +200%）。**本榜上升最穩定專案**。定位極分明確：100% 本地 + 隱私優先 + AI 會議記錄，在 Zoom/Teams AI 壟斷市場中走差異化路線。Rust 實作提供效能護城河。(agent 從工程師族群跨越到大眾市場的風向指標)

2. **[xbtlin/ai-berkshire](https://github.com/xbtlin/ai-berkshire)** — Python，3,757 stars/week，自 07-02 起多次進出榜單。AI 时代价值投资框架：Claude Code / Codex 驱动、多角色对抗分析 + 巴菲特/芒格/段永平/李录四大师方法论。**Agent 正式进入金融投研領域**，跨界應用成熟度持續提高。

3. **[ruvnet/RuView](https://github.com/ruvnet/RuView)** — Rust，3,537 stars/week，5 月底首次出現在歷史報告、05-28 進 Top 5 後持續回到 full list。WiFi 訊號即時空間感測 + 生命體徵監測 + 存在偵測，**零像素純 RF 感測**的設計哲學在 edge AI 赛道具獨特定位。老牌長青專案再次回榜反映 edge sensing 需求穩定存在。

4. **[stablyai/orca](https://github.com/stablyai/orca)** — TypeScript，4,111 stars/week，自 07-03 起持續在 full list。平行 IDE fleet 管理器——用你自己的 subscription 同時跑多個 coding agent，桌面/行動雙平台。**Agent 从單體工具走向艦隊管控層級**的標誌性項目。

5. **[bradautomates/claude-video](https://github.com/bradautomates/claude-video)** — Python，3,630 stars/week，0 歷史記錄首次進榜。讓 Claude 看影片——自動下載、抽幀、轉逐字稿後交由 Claude 处理。[video-use](https://github.com/browser-use/video-use) 生態系的橫向擴展，填補了「影片→Agent」這一塊基礎建設拼圖。

## 4) 歷史比對

### 新進榜 / 今日首次出現在歷史報告

- **[bradautomates/claude-video](https://github.com/bradautomates/claude-video)** — 0 歷史記錄，首次進榜。讓 Claude 看影片——自動下載、抽幀、轉逐字稿，再交給 Claude。

### 回歸榜單（此前曾出現但未在 07-09 Top 22）

- **[MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search)** — 07-08 首次亮相（5,363 ⭐）→ 07-09 未出現在 Top 22 → 07-10 **強勢回歸 #1（13,847 ⭐，▲ +157%）**。趨勢型的劇烈波動代表市場對「Agent 求職」敘事的強烈興趣，但穩定性仍待觀察。
- **[harvard-edge/cs249r_book](https://github.com/harvard-edge/cs249r_book)** — 0 歷史記錄，首次進榜（1,969 ⭐）。哈佛 Machine Learning Systems 教材，教育型專案首次打入 weekly trending，反映 AI 教育需求持續升溫。

### 連續上榜專案

- **[usestrix/strix](https://github.com/usestrix/strix)** — 自 07-04 起連續 7 日在榜，維持 #1–#3 水位。本週略從峰值回落（10,759 → 8,370，▼ -22%），但仍穩居 Top 3，AI 滲透測試領域需求持續強勁。
- **[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)** — 自 07-06 起連續 5 日在榜，**上升最穩定專案**（2,972 → 5,769 → 7,349 → 8,366 → 8,885）。
- **[ogulcancelik/herdr](https://github.com/ogulcancelik/herdr)** — 自 07-03 起連續 8 日在榜，穩定 full list（#7, 4,756）。
- **[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)** — 自 07-03 起連續 8 日在榜，穩定 full list（#9, 4,119）。
- **[alibaba/page-agent](https://github.com/alibaba/page-agent)** — 自 06-28 起連續 14 日在榜，**本榜最長壽專案**，但排名下滑（07-09: #5 → 07-10: #8, 4,459 ⭐ → 4,459 ⭐，動能持平）。
- **[asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)** — 自 06-17 起多次進出，07-09 回歸 full list → 07-10 Top 5（7,149）。
- **[stablyai/orca](https://github.com/stablyai/orca)** — 自 07-03 起多次進出 full list，07-10 持續在榜上（4,111 ⭐）。

### 掉出 Top 5（full list 仍在榜）

- **[openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc)** — 昨日 #4（4,890）→ 今日 #6（4,792），▼ -2.0%，絕對值略降但相對穩定，被 ai-job-search 和 system_prompts_leaks 擠下。
- **[alibaba/page-agent](https://github.com/alibaba/page-agent)** — 昨日 #5（4,295）→ 今日 #8（4,459），▲ +3.8% 絕對值上升但被其他專案擠落——自 06-28 以來首次掉出 Top 5。

### 成長異常

- **[MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search)**：從 07-08 的 5,363 → 07-10 的 13,847（▲ +157%），中間跳過 07-09 未上榜。**本日最爆發增長**，求职 × Agent 的剪切力極強但波動也大。
- **[asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)**：07-09 回歸 full list（6,182）→ 07-10 Top 5（7,149），▲ +15.6%，連續兩日加速。AI 透明度需求從「猎奇」轉為「刚需」。
- **[Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)**：連續 5 日上升無回落，從 2,972 → 8,885（▲ +200%），**本榜目前累積增幅最高且最穩定專案**。

---

**資料來源**：[GitHub Trending (weekly)](https://github.com/trending?since=weekly)，抓取時間 2026-07-10 08:10 CST
**歷史比對範圍**：`reports/github-trending/` 全檔（47 份，2026-05-18 至今），以 `rg -F <repo>` 精確比對。
