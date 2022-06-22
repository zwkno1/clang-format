# clang-format git configs

Add git filter to your git config to automatically format code files:

```
[filter "clang-format"]
        clean = clang-format
        smudge = cat
```
