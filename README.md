# Who-Gets-To-Do-Nothing-
Prediction and clustering analysis of leisure time inequality in the U.S. using American Time Use Survey data. K-Means clustering uncovers daily schedule archetypes while OLS regression predicts leisure time from demographic and socioeconomic inputs. Includes an interactive Plotly Dash visualization.


# Who Gets to Do Nothing?
### A Comparative Analysis of Leisure Time in the U.S.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Hugging%20Face-yellow)](https://huggingface.co/spaces/simranmallik/who-gets-to-do-nothing)

> **[👉 Try the live dashboard here](https://huggingface.co/spaces/simranmallik/who-gets-to-do-nothing)**

---

## Overview

An interactive data visualization dashboard exploring how demographic and socioeconomic factors shape access to leisure time across the United States. Using data from the **American Time Use Survey (ATUS)** spanning 2010–2024, we combine unsupervised clustering and regression modeling to identify who has the least leisure time and why.

---

## Key Findings

- **Employment status** is the strongest predictor of leisure time — individuals not in the labor force have over 2 additional hours of leisure per day compared to employed individuals
- A significant **gender gap** exists, with women having ~60 fewer minutes of leisure per day than comparable men
- Each additional **child reduces leisure by ~17 minutes** per day
- Three distinct daily schedule archetypes exist in the U.S. population:
  - 🔴 **Busy Workers** — high work time, low leisure (~126 min/day)
  - 🔵 **Overextended Individuals** — high household/caregiving demands (~210 min/day)
  - 🟢 **Time-Rich Individuals** — low work time, high leisure (~541 min/day)

---

## Dashboard Features

**Cluster Analysis Tab**
- Annotated bar chart of average leisure time per archetype
- Radar chart showing demographic composition of each cluster
- Stacked bar chart of full daily time allocation by activity category

**Leisure Predictor Tab**
- Build a custom demographic profile and get a predicted daily leisure time
- Compare your profile against a fixed OLS baseline using sampling distributions
- Grounded in the Central Limit Theorem — shows both predicted value and uncertainty

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Dash](https://img.shields.io/badge/Dash-Plotly-informational)
![Statsmodels](https://img.shields.io/badge/Statsmodels-OLS-lightgrey)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-KMeans-orange)

- **Data**: American Time Use Survey (ATUS), Bureau of Labor Statistics
- **Modeling**: OLS Regression (Test R² = 0.25), K-Means Clustering
- **Visualization**: Plotly, Dash, Dash Bootstrap Components
- **Deployment**: Hugging Face Spaces

---


## Team

**Team #37 · CSE 6242 · Georgia Tech**

Deepak Alagu · Felix Huang · Simran Mallik · Leah Nuffer · Nayara Paudyal · Yuritzy Ramos

---

## Report

📄 See `Final_Report.pdf` for full methodology, evaluation, and findings.
