---
title: "Sequential-storage － Efficiently Store Data in Flash"
url: "https://interrupt.memfault.com/blog/sequential-storage-crate"
date: "2024-11-14"
author: "Dion Dokter"
feed_url: "https://interrupt.memfault.com/feed.xml"
---
While using a full-blown filesystem for storing your data in non-volatile memory is common practice, those filesystems are often too big, not to mention annoying to use, for the things I want to do. My solution? I’ve been hard at work creating the sequential-storage crate .
