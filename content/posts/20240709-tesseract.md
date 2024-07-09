---
title: "New alternate frontend: Tesseract. Photon now semi-supported"
slug: "tesseract-2024"
date: 2024-07-09
author: "Ategon"
categories:
  - Programming.Dev
tags:
  - Tesseract
  - Photon
  - Release
  - Alternate Frontend
---

We now have a new alternate frontend for the instance, Tesseract! Tesseract is
a fork of photon with some differences visible on the github page for it:
https://github.com/asimons04/tesseract

The main overall features being:

- Full Media Support in Feed and Posts
- Community Browser / Enhanced Discovery
- Media Bias Fact Check (MBFC) Integration
- Fediseer Integration
- Distinguished and Sticky Comments
- Keyword Filtering
- Multiple Account Support
- Better Moderation Tools than Lemmy-UI

You can find the frontend at https://t.programming.dev

Along with this Photon is currently only semi-supported as opposed to being
pushed as one of the main alternate frontends as we are unable to update to the
most recent versions. There was a swap in some tooling which prevents hosting it
on some versions of operating systems. For now the alternate frontend will exist
frozen on a version and will in the future either break if a lemmy version
breaks that version of the frontend or if the issues are fixed we will upgrade
it and it will be fully supported again.
