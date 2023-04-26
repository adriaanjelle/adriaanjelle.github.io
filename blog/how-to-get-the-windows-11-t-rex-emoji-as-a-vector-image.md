---
title: How to get the Windows 11 t-rex emoji as a vector image
layout: default
nav_exclude: true
nav_order: 1
---

# How to get the Windows 11 t-rex emoji as a vector image

**Some of you who have Windows 11 may have noticed the new emojis that microsoft has made for their new operating system. One particular emoji that stood out to me was the T-Rex emoji. It's soooo fucking cute! I desperately wanted the original vector file.**

## Photoshop

So the first thing I tried was Photoshop. I thought placing some text, selection the Segoe UI Emoji font and using Windows 11's fancy emoji selection panel to place the emoji in Photoshop would do the trick. It did not. Instead, what I got was this lousy outlined version of the emoji.

So then I tried the same in Illustrator. I got the exact same thing: an outlined version of it.

## Font editors
So then, I had another idea: what if I used a font editor to extract the emoji from the font itself? After all, all of Windows 11's emojis are stored in the Segoe UI Emoji font. So I tried FontForge, the free, open-source font editor. However, it has no support for color fonts. If you've never heard of the term 'color font' before, learn more about it [here](https://material.io/blog/color-fonts-are-here).

Then, I tried FontLab Studio (don't ask me how I got it). That app does support color fonts, which is great! Or so I thought. In the entire program, there seems to be no option to export any of the glyphs in any practical way whatsoever. Useless then.

However, all is not lost. I had another fantastic idea. I went looking for an app that can automatically extract all glyphs from a font and convert them into usable .SVG files. Something like that must exist, right? After some searching on Google and GitHub, I came across this handy app called Bits'N'Picas. So I used the Microsoft emoji font and... nothing. So what gives?

It turns out there are multiple standards for making color fonts. Microsoft has its own standard, it seems, and it is barely supported by any program. Luckily, I found an option within FontLab Studio to export the emoji font in a different color font format, one that is supported by Bits'N'Picas.

There I had it: the .SVG file I had been waiting for. However, it was a bit weird. Nothing was aligned to a pixel grid, and none of the straight lines were actually straight. I fixed that, though.

## The end product

| <img alt="" src="/assets/downloads/W11-Dino-(Original).svg"/> | <img alt="" src="/assets/downloads/W11-Dino-(Optimized).svg"/> |
| :----: | :----: |
| Original | Optimized |

[.SVG file (original)](/assets/downloads/W11-Dino-(Original).svg){: .btn .btn-purple } [.SVG file (optimized)](/assets/downloads/W11-Dino-(Optimized).svg){: .btn .btn-purple } [.AI file (Adobe Illustrator)](/assets/downloads/W11-Dino.ai){: .btn .btn-purple }
