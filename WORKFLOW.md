# Repository Workflow

## 目的
此倉庫由多個 agent 共用。為避免互相覆蓋工作目錄、branch checkout 衝突、或把變更做在錯誤 branch，所有 agent 都必須使用固定 worktree 流程。

## 固定角色
- `main`：共享同步基線
- `openclaw`：OpenClaw 專用 branch
- `hermes`：Hermes 專用 branch

## 固定路徑
- Base repo：`~/workspace/shitcode-agent-hub`
- OpenClaw worktree：`~/workspace/shitcode-agent-hub-openclaw`
- Hermes worktree：`~/workspace/shitcode-agent-hub-hermes`

## 強制規則
1. **不要直接在 base repo (`main`) 做功能性修改。**
2. **開始任何作業前，先更新 `main`：**
   ```bash
   cd ~/workspace/shitcode-agent-hub
   git checkout main
   git pull --ff-only origin main
   ```
3. **之後只在自己的 worktree 操作：**
   - OpenClaw：`~/workspace/shitcode-agent-hub-openclaw`
   - Hermes：`~/workspace/shitcode-agent-hub-hermes`
4. **不要在 base repo 直接 checkout 成 `openclaw` 或 `hermes`。**
5. **commit / push 只在自己的 branch 進行。**
6. 若自己的 worktree branch 落後遠端，先在該 worktree 內更新：
   ```bash
   git pull --ff-only origin <your-branch>
   ```

## OpenClaw 每日報告流程
1. 先更新 base repo 的 `main`
2. 進入 `~/workspace/shitcode-agent-hub-openclaw`
3. 確認 branch 為 `openclaw`
4. `git pull --ff-only origin openclaw`
5. 產生 / 更新：
   - `reports/github-trending/github-trending-YYYY-MM-DD.md`
6. 刪除超過 30 天的舊報告
7. `git add` / `git commit` / `git push origin openclaw`

## 衝突處理原則
- 若 `main` 有新規則或共享檔案更新，先 pull `main` 再回到自己的 worktree。
- 若 `openclaw` / `hermes` 之間需要共享新規則，應先進 `main` 整理共通文件，再由各自 branch 決定是否同步。
- 若遇到 merge conflict，不要硬推；先停下來明確處理衝突。

## 報告資料夾規則
- 路徑：`reports/github-trending/`
- 檔名：`github-trending-YYYY-MM-DD.md`
- 保留天數：30 天
