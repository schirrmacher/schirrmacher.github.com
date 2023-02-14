---
layout: project-right # alternative layouts: project, project-left, project-right, project-top
title: "Betriebssystem"
description: false
year: 2022
weight: 3
thumbnail: "/assets/images/gen/projects/betriebssystem.jpg"
image: "/assets/images/gen/projects/betriebssystem.jpg"
categories: []
format: "Drucke auf DIN A4 Papier"
gallery:
  - image: "/assets/images/gen/projects/betriebssystem.jpg"
  - image: "/assets/images/gen/projects/betriebssystem2.jpg"
---

When preparing my first exhibition, I wanted to create something visually appealing which reveals the hidden world of computing.
I had a simple idea: print the source code of the Linux Kernel, a popular open-sourde operating system, and put it into a room.

The Linux Kernel has 31,475,301 lines of code (commit ef4d3ea40565). 
When doing some calculations it would be insane to print it. 
A regular DIN A4 page has 50 lines of text. So I would end up printing 629,507 pages.
No text editor I tried was able to handle such a giant file. Still the idea hooked me.

I implementeted the file creation on my own, created page after page.
I removed whitespaces and newlines from the text and wrapped the content to 220 characters for each line.
I chose the lowest acceptable font size (4pt), the smallest possible setting for page margins and put 190 lines on a single page.
After that I was left with 4,038,118 lines which fit on 21,254 DIN A4 pages.
The creation of all pages took around 16 hours. Merging all pages to the final 1.8 gigabyte large file took 3.5 hours.

Here are the first 1000 pages.