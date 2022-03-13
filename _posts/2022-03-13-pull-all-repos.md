---
layout: post
title: "Pull from origin/main for all repos in a directory"
description: ""
comments: false
keywords: ""
color: ""
---

```bash
find . \
-maxdepth 1 \
-type d \
-print \
-execdir git \
--git-dir={}/.git \
--work-tree=$PWD/{} pull origin main \;
```
