---
title: 'Ghostpad is now a hard fork (with better conflict resolution)'
pubDate: 2024-02-12
layout: ../../layouts/NewsLayout.astro
---

One of the most challenging aspects of building Ghostpad has been enabling each setting to be changed in real time, and allowing changes from other clients to be received and properly applied to the UI in real time. Previously, I used a combination of timestamps and a ignore-list of changes that the client already knows to be outdated. These were fragile, temporary solutions that were put in place to minimize the backend changes required to create the experience I wanted.

&nbsp;

With the latest revision of Ghostpad, each setting that can be changed, including each chunk of text, has its own "sequence number". When you change a setting locally, this number increases and is sent to the server. When a change is received, its sequence number is checked, and if it is lower than the local sequence number, it is discarded. This results in a "last write wins" conflict resolution strategy.

&nbsp;

What does this mean in simple terms? It means the real-time nature of Ghostpad is now implemented in a more stable manner that should result in less buggy behavior in slow network conditions.
