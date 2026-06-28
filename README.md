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

## 参考文献

db-review スキルのチェック項目は、以下の書籍で紹介されている知見を参考にしています。

- [失敗から学ぶRDBの正しい歩き方](https://gihyo.jp/book/2019/978-4-297-10408-5)（曽根壮大 著、技術評論社）
- [達人に学ぶDB設計 徹底指南書](https://www.shoeisha.co.jp/book/detail/9784798124704)（ミック 著、翔泳社）

## ライセンス

MIT
