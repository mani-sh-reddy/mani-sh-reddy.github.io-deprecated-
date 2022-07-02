---
layout: post
title: "git log pretty formatting"
description: ""
comments: false
keywords: ""
color: ""
---

```bash
git log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all
```

\
[https://git-scm.com/docs/pretty-formats](https://git-scm.com/docs/pretty-formats)