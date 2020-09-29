---
date: "2018-12-20T00:00:00Z"
external_link: ""
image:
  focal_point: Smart
summary: Development of a tool to assess the benefits of digital Traffic Management Systems.
tags:
- Transport
- Rail
- Innovation
client:
- Network Rail
- Digital Railway
title: TMS Benefits Tool
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
zref: 20200929101552
---



Network Rail's Digital Railway Project was seeking a method of understanding the potential scale of improvements realisable from increased, or more effective use of their trialled Traffic Management System.

To meet this goal I developed an online tool to allow users to input historical performance data and adjust performance based on the effects of the Traffic Management System trial.

The tool analysed this data and categorised each incident into a category based on the overall delay minutes attributed to that delay incident. Users were able to see an analysis of all delay incidents included broken down by incident size, incident time, operators involved and many other aspects.

The user could then adjust the historic performance in order to simulate what the outcomes might have been has the Traffic Management System been in operation.

The TMS benefits tool has a set of default modifications based on expert observation of Traffic Management Systems, but allowed users to add their own profiles or simply adjust the settings and see the results live. All impact profiles could be saved or loaded allowing for replication of results.

The results of this analysis were produced as a mirror of the original delay analysis, i.e. incidents broken down by incident size, incident time, operators involved, etc.

This tool was developed using R and the Shiny library for web visualisations and deployed on the internet allowing users to interact with it without needing to install any additional software and ensuring that fixes or modifications could be rolled out without needing to send new files to users.





