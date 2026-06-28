# claude-skills

Claude Code / Cursor / Codex などの AI エージェントで使えるスキル集。

## インストール

```bash
# npx skills（推奨）
npx skills add takuya-38/claude-skills --skill db-review

# GitHub CLI
gh skill install takuya-38/claude-skills db-review --agent claude-code

# 全スキルを一括インストール
npx skills add takuya-38/claude-skills --all
```

## スキル一覧

| スキル | 概要 |
|---|---|
| [db-review](./skills/db-review/) | DB設計（スキーマ）をレビューし、アンチパターンの候補を深刻度別に検出する |

## ライセンス

MIT
