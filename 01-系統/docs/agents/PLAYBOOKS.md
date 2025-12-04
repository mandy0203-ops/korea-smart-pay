# Agent Playbooks

## 中文指令快查 (Chinese Shortcuts)
- **#發佈** (Publish)
  - Intent: Push current changes to GitHub and ensure Pages are active.
  - Steps: `git add .`, `git commit`, `git push`, check `gh pages` status.
- **#備份** (Backup)
  - Intent: Create a local zip backup of the `03-輸出` folder.
  - Steps: Zip `03-輸出` to `03-輸出/backups/backup-YYYYMMDD.zip`.
- **#檢查** (Check)
  - Intent: Verify system health and project status.
  - Steps: Run scaffold check, verify `status.html` is up to date, check git status.
- **#狀態** (Status)
  - Intent: Open the project dashboard.
  - Steps: Open `03-輸出/專案儀表板/status.html` in browser.

## Standard Playbooks

Map natural language phrases to intents and steps.

## Format
- **Phrase**: "..."
  - **Intent**: ...
  - **Steps**:
    1. ...
  - **Expected Output**: ...
