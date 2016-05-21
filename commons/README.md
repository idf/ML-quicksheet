# commons-latex
Common Commands for LaTeX

# Usage
Use as subtree
```bash
git remote add -f commons git@github.com:idf/commons-latex.git
git subtree add --prefix commons commons master --squash
git subtree pull --prefix commons commons master --squash
git subtree push --prefix commons commons master
```

**Force push**. If come across the "Updates were rejected because the tip of your current branch is behind. Merge the remote changes, then need to nest git commands so as to force a push.

```bash
git push commons `git subtree split --prefix commons master`:master --force
```
