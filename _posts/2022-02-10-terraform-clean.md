---
layout: post
title: "Clean Terraform Dot Files"
description: ""
comments: false
keywords: ""
---

```bash
find ./ -name ".terraform*" -exec rm -rf {} \;
```