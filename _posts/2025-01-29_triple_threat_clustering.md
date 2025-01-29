---
title: "Identifying Triple Threat Forwards Using Data"
image: "images/3dchart.png"
date: 2025-01-29
layout: post
desc: "Using k-means clustering to identify different attacking profiles in forward players."
---


# Identifying Triple Threat Forwards Using Data

![3d chart](/images/3dchart.png)
Read my long blog post [here](https://databetweenthelines.substack.com/p/identifying-triple-threat-forwards).

This project (find here on [GitHub](https://github.com/louis-porter/football-analytics/tree/main/blog-posts/deep-dives/triple-threat-forwards)) expands on an idea from Ian Graham's hit book "How to Win the Premier League" where he discusses the notion of Triple Threat Forwards, those who bring value to possessions via passing, shooting, or carrying. 

Using that idea, the analysis attempts to group players into categories using a k-means clustering algorithm based on an ensemble metric calculated to represent skill in eaach of those threats.