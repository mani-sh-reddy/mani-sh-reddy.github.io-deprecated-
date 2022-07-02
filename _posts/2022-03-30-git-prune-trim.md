---
layout: post
title: "git prune & trim"
description: ""
comments: false
keywords: ""
color: ""
---

```bash
function gprune() {
	git fetch -p 
	for branch in $(git for-each-ref --format '%(refname) %(upstream:track)' refs/heads | awk '$2 == "[gone]" {sub("refs/heads/", "", $1); print $1}') 
	do 
		git branch -D "$branch"
	done
}
```
\
```bash
git checkout main && gprune && git pull"
```
