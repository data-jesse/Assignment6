# Data 712 - Homework 6: Count Data Modeling with Simulation-Based Interpretation

## Project Overview

This assignment explores **count data models** using the **Diabetes Health Indicators Dataset**. 
The focus is on modeling the number of **mentally unhealthy days (ment_hlth)** using key health and demographic variables such as **age**, **high blood pressure**, and **physical activity**. 

The goal is to:

- Identify meaningful predictors of mental health outcomes.
- Compare Poisson vs Negative Binomial models.
- Apply simulation-based interpretation using the `clarify` package.
- Visualize dose-response relationships and average marginal effects (AMEs).

## Methods & Tools

- **Modeling Techniques:**
  - Poisson Regression
  - Negative Binomial Regression
  - Overdispersion Testing
    
- **Simulation Approach:**
  - `clarify::sim()` to simulate model coefficients
  - `sim_ame()` and custom dose-response visualization
    
- **Visualization & Reporting:**
  - `ggplot2`, `texreg`, `readthedown`

## Key Findings

- Overdispersion was detected, making the Negative Binomial model more appropriate than Poisson.
- **Physical activity** was associated with **~2.3 fewer** mentally unhealthy days on average.
- **High blood pressure** was linked to **~1.3 more** mentally unhealthy days.
- A **dose-response relationship** was observed with **age**: older individuals were predicted to report more mentally unhealthy days.

## Files

| File | Description |
|------|-------------|
| `Assignment 6.Rmd` | R Markdown file with full analysis |
| `README.md` | This file |
| _Note:_ Output is in `readthedown` format, which is rendered via RStudio’s viewer or RPubs. No PDF or HTML file is included in this repo.


## Output Note

This assignment uses the `rmdformats::readthedown` format, which is not designed for standalone HTML or PDF distribution. For viewing the full rendered report, please refer to the RPubs link below.


## RPubs Link



