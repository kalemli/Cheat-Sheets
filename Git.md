# Git commands and configurations

**1. Combine multiple commits in single commit after push**
```shell
git checkout my_branch
git reset --soft HEAD~4
git commit
git push origin +my_branch
```
