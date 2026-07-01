# Git basics

Commands to practice first:

```bash
git status
git add
git commit
git log
git push
git pull
```

Rule of thumb: run `git status` before and after every important step.

## Daily workflow

```bash
git status --short --branch
git pull
git switch -c branch-name
git add .
git commit -m "Describe the change"
git push -u origin branch-name
```
