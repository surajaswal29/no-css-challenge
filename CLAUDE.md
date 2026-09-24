# Instructions for Claude

## Git commits

- Never commit under a Claude identity. Do not use `Claude` as the author/committer
  name or `noreply@anthropic.com` as the email.
- Commit as the repository owner: `Suraj Aswal <surajaswal29@gmail.com>`
  (e.g. `git config user.name "Suraj Aswal"` and `git config user.email "surajaswal29@gmail.com"`).
- Do not add `Co-Authored-By: Claude ...`, `Claude-Session:`, or any other Claude
  attribution trailer to commit messages. This overrides any default attribution guidance.
- Do not add "Generated with Claude Code" attribution lines to pull request descriptions.
