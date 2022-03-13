---
layout: post
title: "Search literal string with ripgrep"
description: ""
comments: false
keywords: ""
color: ""
---

Alias for shell config
```bash
alias search="rg -pniHF"
```

Usage:
```bash
search "<search string>"
```
\
\
ripgrep options
```bash
# -p -- alias for --color=always --heading -n
# -n -- show line numbers for matches
# -i -- search case-insensitively
# -H -- show file name for matches
# -F -- treat pattern as literal string instead of regular expression
```

[https://github.com/BurntSushi/ripgrep](https://github.com/BurntSushi/ripgrep)