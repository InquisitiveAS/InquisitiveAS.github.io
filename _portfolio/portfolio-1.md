---
title: "Silman ConColScheduler"
excerpt: "PyRevit Add-in at Silman TYLin <br/><img src='/images/01_portfolio_1.png'>"
collection: portfolio
---

<!-- This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  

![ConColScheduler](/assets/img/0x_ConColScheduler_logo.png)

-->

This is a Revit Add-in(developed using PyRevit)for generating GCS(Graphical Column Schedule) for Concrete Columns without a grid. The conception for this add-in arose due to two main challenges.
he first challenge was, that Revit API currently does not have a currently have a method to compute or access GCS(Graphical Column Schedule). 

The second challenge is Concrete Columns are usually marked via Grid, we wanted to have a new type parameter where columns are marked by X,Y,Z position.

This plugin/pyrevit addin helps the BIM team to generate a Concrete Column Scheduling in an Excel format.
It grabs a type mark of the concrete columns from the active viewport (3D) and auto-generates an Excel File of the schedule.

