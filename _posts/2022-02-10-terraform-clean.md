---
layout: post
title: "rm .terraform files"
description: ""
comments: false
keywords: ""
color: ""
---

```bash
find ./ -name ".terraform*" -exec rm -rf {} \;
```