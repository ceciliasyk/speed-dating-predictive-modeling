# Stated Preferences vs. Behavior in Romantic Decision-Making

## Overview

Do people actually know what they want in a romantic partner?

This project examines the relationship between individuals' stated
partner preferences and their actual romantic decisions using data
from a large-scale speed-dating experiment.

Using 8,377 individual dating interactions, I compared how well three
types of information predicted mutual matches:

- Demographic characteristics
- Pre-date stated partner preferences
- Post-date impressions following an interaction

## Research Question

To what extent do individuals' pre-date stated partner preferences
predict whether they form mutual matches?

## Methods

The analysis used Python and statistical learning techniques including:

- Logistic regression
- Regularization
- Decision trees
- ROC-AUC and classification metrics
- Permutation feature importance
- Partial dependence analysis

Models were compared to determine whether demographics, stated
preferences, or post-interaction impressions provided the strongest
predictive information.

## Key Findings

Demographic characteristics alone provided little predictive information
about mutual matches.

Pre-date stated preferences showed some predictive signal but remained
limited in their ability to explain actual romantic decisions.

Post-date impressions were the most informative predictors of mutual
matches, suggesting that people's experiences during an interaction
better explain their decisions than what they report wanting beforehand.

Feature analyses identified attractiveness, shared interests, and
partner-rated ambition among the most influential predictors in the
post-date model.

## Takeaway

The results suggest a gap between stated preferences and actual behavior:
what people say they value beforehand may not fully reflect what drives
their decisions after a real interaction.

More broadly, the project demonstrates how behavioral data and predictive
modeling can be used to examine the relationship between self-reported
beliefs and observed decision-making.

## Tools

Python • Pandas • NumPy • Matplotlib 

## Repository Contents

- Analysis notebooks
- Decision tree analysis
- Model evaluation and visualizations
- Technical report
