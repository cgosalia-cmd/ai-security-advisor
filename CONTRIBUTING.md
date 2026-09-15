#Contributing

##Branching
A new branch for every day's taks - `day##-short-name`

##Commits
[Conventional Commit](https://www.conventionalcommits.org/) message (`feat:`, `fix:`, `refactor:`, `test:`, `docs:`, `chore:`)

##Pull Request
Every change should go through a PR against 'main", no matter how small. Description template:
- **What** - What is changed
- **Why** - What problem does this change solve
- **Testing/Validatin** - what you ran to confirm this works

##Checklist
- [] Tests pass locally and in CI
- [] `ruff check` clean
- [] No secrets/keys commmited (`.env` untracked, nothing printed/logged)
- [] README updated if any behavior changed
