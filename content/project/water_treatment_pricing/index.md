---
date: "2018-12-20T00:00:00Z"
external_link: ""
image:
  focal_point: Smart
summary: Development of a charging tool for water treatment.
tags:
- Data Science
client:
- Severn Trent Water
title: Fixed Forward water treatment pricing tool.
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
zref: 20200929101752
---

Severn Trent Water wanted to move from a flat rate chargin model to a fairer usage based model for their industrial water clients. Unfortunately water sampling is often inconsistent and may not tell the full story about a clients usage rates. 

For example, one client, a brewery produced a large volume of contaminated water during one phase of the brewing process (a weekly production cycle) but on other days produced relatively little. Standard statistical analysis of sample data would show wild swings in their usage depending on if their output was sampled during the active period.

In order to correctly set pricing my team developed a tool to perform statistical analyses on water sampling data and use this to deduce the correct pricing level in terms of suspended solids, dissolved oxygen, and ammonia content. 

The client was interested in using an Excel front end, since they were familiar with excel, but to do most of the complicated statistical processing using R. As lead developer I oversaw the process to marry these two systems together, but also developed a web based system allowing themto move away from the cumbersome excel interface if they so chose.