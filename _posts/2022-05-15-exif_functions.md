---
layout: post
title: "exif functions"
description: ""
comments: false
keywords: ""
color: ""
---

```bash
exiftags() {
    exiftool --read-Tags -args ./*
}

exifmodifydate() {
    exiftool "-ModifyDate>FileModifyDate" ./* -overwrite_original
}

exifmodifydatevid() {
    exiftool "-MediaCreateDate>FileModifyDate" ./* -overwrite_original
}
```
