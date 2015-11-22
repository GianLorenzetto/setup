# Git with BeyondCompare

In order to use [BeyondCompare](http://www.scootersoftware.com) with Git, add the following to your config.

Note - the below is for BeyondCompare 4. For older versions checkout [this BeyondCompare Support topic](http://www.scootersoftware.com/support.php?zz=kb_vcs).

```
[diff]
    tool = bc4
[difftool "bc4"]
    cmd = \"c:/program files (x86)/beyond compare 4/bcomp.exe\" \"$LOCAL\" \"$REMOTE\"
[merge]
    tool = bc4
[mergetool "bc4"]
    cmd = \"c:/program files (x86)/beyond compare 4/bcomp.exe\" \"$LOCAL\" \"$REMOTE\" \"$BASE\" \"$MERGED\"
    trustExitCode = true
```

To activate, just use `git difftool` instead of the usual `git diff`.