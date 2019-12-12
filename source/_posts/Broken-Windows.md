---
title: Broken Windows
date: 2019/12/12 00:00:00
coverImage: https://res.cloudinary.com/drzgzthur/image/upload/v1576073474/Blog/broken-window.png
coverSize: partial
autoThumbnailImage: yes
thumbnailImagePosition: left
metaAlignment: center
disqusIdentifier: broken-windows-post
categories:
- Code
tags:
- The Pragmatic Programmer
---

I recently started reading "The Pragmatic Programmer" by [Andrew Hunt](https://twitter.com/PragmaticAndy) and [David Thomas](https://twitter.com/pragdave). Written 20 years ago, this book surprisingly stays current with its use of analogies and short stories to help the reader develop into a productive programmer. Think of it as the "How to Win Friends & Influence People" for programmers.

One story that stuck with me describes how quickly great code can go rotten.

### Broken Windows

Anyone who has been to a city knows that they are filled with beautiful timeless buildings. But there are also buildings that look like they were left and forgotten, decaying in plain sight.

How do these buildings go from something beautiful to something so ugly? In short, it can stem from a single broken window.

I'll let Andrew and David explain:

> One broken window, left unrepaired for any substantial length of time, instills in the inhabitants of the building a sense of abandonment — a sense that the powers that be don’t care about the building. So another window gets broken. People start littering. Graffiti appears. Serious structural damage begins. In a relatively short space of time, the building becomes damaged beyond the owner’s desire to fix it, and the sense of abandonment becomes reality.

This phenomenon has been studied and coined as "[The Broken Window Theory](https://en.wikipedia.org/wiki/Broken_windows_theory)".

Can you recognize how this "Broken Window Theory" can relate to our codebases?

When we make bad design decisions in our code or notice a function is written incorrectly, do not leave it with the intention to come back later and fix it. Fix it now, or else you'll find yourself looking at a codebase full of broken windows.

Other code maintainers will begin to adhere to the same standard, ignoring code that should be fixed, and they will continue to implement additional sloppy commits. Over time, the general sentiment towards this codebase can best be described as carelessness. There will be no concern about the quality or maintainability. Then, finally your codebase will be unmaintainable and eventually abandoned.

**So fix any broken windows you may come across**. This will cultivate a mindset that the codebase is handled with care and responsibility.
