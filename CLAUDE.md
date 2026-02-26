# CLAUDE.md

## Git ワークフロー

- `git push` の前に必ず `git pull --rebase` を実行すること（GitHub Actions による自動コミットが入る可能性があるため）
- push 後は GitHub Actions のデプロイ（`pages-build-deployment`）が完了するまで `gh run watch` で見届けること
