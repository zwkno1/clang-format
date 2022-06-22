# clang-format git configs

1. Git filter 

Add git filter to your git config to automatically format code files:

```
[filter "clang-format"]
        clean = clang-format
        smudge = cat
```

2. Git clang-format plugin
use :
``` git clang-format ```

[doc](https://offlinemark.com/2021/04/02/surgical-formatting-with-git-clang-format/)
