---
title: "How Memory Usage Patterns Can Derail Real-time Performance"
url: "https://interrupt.memfault.com/blog/memory-debugging"
date: "2024-08-29"
author: "Bert Schiettecatte"
feed_url: "https://interrupt.memfault.com/feed.xml"
---
In this article, we will learn how memory usage patterns can affect the real-time performance of an embedded application, drawing from a recent experience tracing an audio DSP application running on an embedded Linux platform. First, I will introduce the product in question and the real-time audio software I developed for it. Then, I’ll describe the issues I encountered with audio callbacks and the strategy I followed to determine the cause of the issues, ending with my solution and lessons learned.
