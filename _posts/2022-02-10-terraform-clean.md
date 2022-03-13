---
layout: post
title: "Clean Terraform Dot Files"
description: ""
comments: false
keywords: ""
color: ""
---

```bash
find ./ -name ".terraform*" -exec rm -rf {} \;
```