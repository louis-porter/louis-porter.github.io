---
title: "Using Python to Optimize Football Manager 2024 Squad Planning: A Data-Driven Approach"
image: "images/solver.png"
date: 2024-12-20
layout: post
desc: "I used Python to optimise future squad planning in FM24."
---


# Using Python to Optimize Football Manager 2024 Squad Planning: A Data-Driven Approach

![Example solver output](/images/solver.png)
This project (find here on [GitHub](https://github.com/louis-porter/football-analytics/tree/main/optimisation/multi-season-squad-planning-fm24)) details a Python-based optimization system for squad planning in Football Manager 2024, inspired by real-world football analytics. I created a solver that uses linear programming to make transfer decisions, testing it with Crystal Palace. The system evaluates players based on position-specific attributes, club DNA (favoring pressing style), and applies multipliers for age and performance. It operates within constraints like transfer budgets, wage limits, and squad size requirements.

The system was tested across two transfer windows. In the January window, it suggested three signings including Sergio Carreira, Fredrik Bjorkan, and Tommaso De Nipoti, with mixed success. The summer window saw larger changes, with multiple signings including Raul Torrente (who proved most successful) and several others who had varying impacts. While not all signings excelled on the pitch, most increased in value, suggesting good talent identification. I noted potential improvements needed, particularly in managing squad depth expectations and better wage estimation for incoming players.