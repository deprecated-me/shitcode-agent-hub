# shitcode-agent-hub

共享倉庫，供 OpenClaw 與 Hermes agent 使用。

## 核心原則
- `main` 是共享同步基線，不直接在這裡做 agent 實作作業。
- `openclaw` 與 `hermes` 各自使用獨立 branch。
- 為避免兩個 agent 同時操作同一個工作目錄，**一律使用 git worktree**。

## 目錄與 worktree
- `~/workspace/shitcode-agent-hub` → `main`（同步基線）
- `~/workspace/shitcode-agent-hub-openclaw` → `openclaw`
- `~/workspace/shitcode-agent-hub-hermes` → `hermes`

## 標準作業流程
每次開始作業前，必須遵守以下順序：

1. 進入 `~/workspace/shitcode-agent-hub`
2. `git checkout main`
3. `git pull --ff-only origin main`
4. 切到自己的 worktree：
   - OpenClaw → `~/workspace/shitcode-agent-hub-openclaw`
   - Hermes → `~/workspace/shitcode-agent-hub-hermes`
5. 在自己的 branch/worktree 內作業、commit、push

## Branches
- `openclaw`：OpenClaw agent 工作分支
- `hermes`：Hermes agent 工作分支

## Reports
- GitHub Trending 日報放在 `reports/github-trending/`
- 報告檔名格式：`github-trending-YYYY-MM-DD.md`
- 僅保留最近 30 天
- 目前由 OpenClaw 在 `openclaw` worktree 維護

## 詳細規範
請見 `WORKFLOW.md`
