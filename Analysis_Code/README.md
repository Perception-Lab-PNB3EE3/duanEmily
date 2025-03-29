# Overview of Code.Rmd

This R markdown file analyzes the relationship between Reaction Time and Betrayal Choices across different Conditions (Excited, Angry, Calm, Sad). The analysis includes the following components:

Data Simulation: Simulated reaction times, betrayal choices, and responses on a Likert scale for several emotional conditions. The responses on likert scale is for collection purpose, therefore not counting into the analysis part.

ANOVA Analysis: Two one-way analysis of variance (ANOVA) to assess the impact of Condition on Reaction Time and BetrayalChoices.

Post-Hoc Analysis: Estimated marginal means (EMMs) and pairwise comparisons using least significant difference (LSD) tests. Hypotheses are all proofed within this section.

Visualization: Plots including (1) a histogram that has a mixed distribution of data in the 4 conditions on reaction time, (2) a box plot that shows the average reaction time across 4 conditions, (3) a box plot showing the average betrayal choices across 4 conditions, and (4) a scatterplot including each participant's reaction time and betrayal choices with dashed lines representing the range of each condition's distributed data.

# Statistical Methods
ANOVA: The model tests the main effects of Condition and Betrayal Choices as well as their interaction on Reaction Time.

Post-Hoc Comparisons (LSD): Pairwise comparisons between condition pairs using the emmeans package to calculate estimated marginal means.

# Prerequisites
Make sure to install the following R packages before running the analysis:
ggplot2, viridis, emmeans, stats, and tidyverse

To install these packages, run:

install.packages(c("ggplot2", "viridis", "emmeans", "stats", "tidyverse"))