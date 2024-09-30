---
layout: post
title:  "What about the FHIRPath VSCode extension?"
date:   2024-09-30 18:35:00 +0200
categories: blog
---

Today, I have a lot of work to do in "offline" mode with Implementation Guide files. When I say "offline", I mean that the files are stored locally on my computer, and I am reading them directly from there.

I've been working with a profile-resources.json file. If you're familiar with it, you know it's a huge file. Naturally, I don't want to read it as-is. I need a way to manipulate the data using FHIRPath. Currently, I select all the lines in my editor, copy them, and paste them into fhirpath.me to run queries. I don’t like doing it this way.

Perhaps I should create a VSCode extension that acts as a wrapper for fhirpath.js. This could be a useful tool for developers.