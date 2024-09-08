---
title: "Team Strength Model"
image: "images/model_cover.png"
date: 2024-09-07
layout: post
desc: "An ensemble Dixon-Coles inspired model using xG and Goals to estimate team strength and predict match outcomes. "
---


# Team Strength Model

![Model predictions for a gameweek of Premier League Fixtures](/images/model_cover.png)
This project (find here on [GitHub](https://github.com/louis-porter/football-analytics/blob/main/models/team-strength-models/ensemble_dixon_coles_model.ipynb)) uses Python to create a team strength model. The final model is an ensemble of a xG and a Goals model that produces an attacking strength and a defensive strength coefficient for each team and a value for the home effect constant. The model is heavily inspired by the works of Dixon-Coles and incorporates a time decay and a "rho" value which captures the correlation between teams' goal counts, which essentially just adjusts the probabilities for low-scoring outcomes in football matches which Dixon-Coles showed is something that models such as these often under-report on.
