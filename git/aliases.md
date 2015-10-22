# Git Aliases

A basic set of git aliases that I use. Just copy directly into your .gitconfig (global or local, your choice) or merge with an existing `[alias]` section.

```
[alias]
    st = status
    co = checkout
    ci = commit
    rb = rebase
    aa = add --all
    b = branch
    di = diff
    dc = diff --cached
    pullff = pull --ff-only
    pr = pull --rebase
    mergeff = merge --ff-only
    lg = log --pretty=\"tformat:%C(yellow)%h%Creset  %Cgreen(%ar)%Creset  %C(bold blue)<%an>%Creset  %C(bold red)%d%Creset %s\" --graph --date=short
```
