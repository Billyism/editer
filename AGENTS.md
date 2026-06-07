# AGENTS.md

## Workflow

This repo is hosted at `github.com/Billyism/editer` with GitHub Pages:
- Repo: `https://github.com/Billyism/editer`
- Pages: `https://billyism.github.io/editer/`

## After every code change

After modifying any files in this repo, you MUST:

### 1. Git commit

git add -A
git commit -m "description of changes"

### 2. Git push

git push origin master

### 3. (Optional) Check Pages deployment status

gh run list --limit 3

## Rules

- Commit messages must be clear and descriptive (use Chinese or English)
- Use cached token from .git-credentials if git push needs credentials
- Never commit .git-credentials (excluded by .gitignore)
- Write changes in Chinese commit messages when the change is described in Chinese
