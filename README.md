# sales-skills-public

営業本部の**全社公開用**スキルリポジトリです（デモ用の架空データ）。

- `skills/<スキルID>/` に1スキルずつ置きます。`SKILL.md` がClaudeの読む手順書、`README.md` が人向けの説明です。
- 一覧に載せるタイトルと概要は `catalog.yml` に書きます。書かなかった場合は README の見出しと最初の段落が使われます。
- `main` に変更が入ると `.github/workflows/notify-catalog.yml` が skill-catalog に通知し、全社のスキル一覧が自動で作り直されます。
