---
layout: post
title: A Trip
categories: [writeups]
tags: [bug-bounty, costa-rica]
author: Ronny
---
## Hello World

This is a test of a post

```bash
curl -s https://crt.sh/?q=example.%25&output=json | jq -r '.[].name_value' | sed 's/\*\.//g' | sort -u
```
