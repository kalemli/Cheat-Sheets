# Git commands and configurations

**1. Change commit author**
```shell
git commit --amend --author="Name <name@domain.tld>"
```

**2. Combine multiple commits in single commit after push**
```shell
git checkout my_branch
git reset --soft HEAD~4
git commit
git push origin +my_branch
```
**OR**

```shell
git rebase -i origin/master~5 master
git push origin +master
```
