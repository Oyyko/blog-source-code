---
title: Fix a grub bug
date: 2021-03-20
tag: 
- BUG
category: BUG
mathjax: false
---
In this article, I will record how to fix the problem that grub can't find Windows on nvme. So that someday, I can reuse this to help myself.
<!-- more -->

First of all, install `os-prober`.

Then, run `update-grub` or `grub-mkconfig`.
Then you will find that os-prober is not working. Because:
