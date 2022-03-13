---
layout: post
title: "Clean terraform dot files"
description: ""
comments: false
keywords: ""
color: ""
---

```bash
find ./ -name ".terraform*" -exec rm -rf {} \;
```