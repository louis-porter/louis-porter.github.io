---
title: "Football Match Outcome Predictions"
excerpt: "A study using historic team performance data to try and predict the outcome of matches using form and other features to estimate the expected goals a team will produce.<br/><img src='/images/match_outcome_study.png'>"
collection: portfolio
---

Please find link to Jupyter Notebook file [here](https://github.com/lsp2610/predicting_football_match_outcomes/blob/main/match_outcome_study.ipynb).

---

This project uses a large dataset of football match games from https://beatthebookie.blog/ to model xG in games using prior information relating to team and opponent strength as features.

It uses exponential moving averages (EMAs) of statsitics such as xG, shots, deep completions and more.

Once the xG predictions and the model were selected, the model's xG predictions are used to generated match odds, and then a poission model to predict match outcomes is used - this is then compared against the fair odds from bet365 (margin removed) to evaluate model performance using a Brier score.

---

My XGBoost model slightly outperforms the Bet365 odds, when removing the margin, to predict the outcome of football matches. The EMA of "shots for" is the most important feature when using this model, with the home effect being the least important.