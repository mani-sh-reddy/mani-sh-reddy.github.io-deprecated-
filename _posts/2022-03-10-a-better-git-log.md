---
layout: post
title: "A Better Git Log"
description: ""
comments: false
keywords: ""
color: ""
---

```bash
BB='%C(bold blue)'
BG='%C(bold green)'
AR='(%ar)' # author date, relative
W='%C(white)'
DW='%C(dim white)'
BY='%C(bold yellow)'
X='%C(reset)' # reset color
# %h : abbreviated commit hash
# %s : subject
# %an : author name
# %d : ref names

git log --graph --abbrev-commit --decorate \
--format=format:"$BB%h$X - $BG$AR$X $W%s$X $DW- %an$X$BY%d$X" \
--all

unset BB BG AR W DW BY X # clean variabes
```

\
alias for shell config

 <p style="font-size:0.9vw" style="color:MediumSeaGreen;">
alias glog="git log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"
</p> 
\
\
[https://git-scm.com/docs/pretty-formats](https://git-scm.com/docs/pretty-formats)