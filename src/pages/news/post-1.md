---
title: 'Ghostpad has a website!'
pubDate: 2023-11-14
layout: ../../layouts/NewsLayout.astro
---

I wanted to build a minimalistic static site that could be broken up into reusable parts, and I was worried that it might be a huge pain. I've built many Wordpress sites before, and really didn't want to go down that road again. Jekyll and Hugo seemed like decent options, but would have involved adding dependencies on Ruby or Go tooling - not the end of the world, but not ideal. Gatsby seemed to be a bit heavy-duty for what I'm trying to accomplish, and they aren't subtle about their desire to sell me cloud services. I'm just trying to spit out some HTML files here.

&nbsp;

So I came across Astro, which seems to do everything I need within the Typescript ecosystem. Support for Markdown, React, Vue, Svelte, ".astro" templates that aren't tied to any frameworks, fancy CSS scoping... This is kind of awesome. I think I've found my solution.

&nbsp;

I'm hosting on Github Pages, not running a line of Javascript within the site itself, and I feel like I've accomplished my goal of building some plain old HTML files without over-engineering anything. 🎉

&nbsp;

Although Ghostpad itself is released under the AGPL license for compatibility with its parent project, KoboldAI, the source for this website is released under the MIT license at https://github.com/ghostpad/ghostpad-site