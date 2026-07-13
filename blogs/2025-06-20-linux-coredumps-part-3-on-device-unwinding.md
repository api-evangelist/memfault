---
title: "Linux Coredumps (Part 3) － On Device Unwinding"
url: "https://interrupt.memfault.com/blog/linux-coredumps-part-3"
date: "2025-06-20"
author: "Blake Hildebrand"
feed_url: "https://interrupt.memfault.com/feed.xml"
---
In this post, we’ll go over a method of coredump collection that does the stack unwinding on-device. This approach allows devices that may be sensitive to leaking PII (Personally Identifiable Information) that may be stored in memory on the stack or heap to safely collect coredumps in addition to greatly reducing the size needed to store them. Continue reading…
