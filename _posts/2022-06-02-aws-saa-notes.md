---
layout: post
title: "AWS SAA-C02 Notes"
description: ""
comments: false
keywords: ""
color: ""
---

# aws saa notes (rough draft)
## iam identity and access management
- globally resilliant
- data is secure across aws regions

### iam objects
- users humans / apps that need access to your account
- group - collections of related users
- roles - can be used by aws services to grant
- policy - allow ideny access to aws services (only when attached to other identities)

### iam 3 parts
- managed identitities idp (id provider)
- authenticates - proves who claim to be
- authorises - allows + denies

### more iam info
- no cost
- global / global resilliance
- allow/deny identities on its aws account