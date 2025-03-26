# Overview of Code.Rmd

This document analyzes the relationship between Reaction Time and Betrayal Choices across different Conditions (Excited, Angry, Calm, Sad). The analysis includes the following components:

Data Simulation: Simulated reaction times and responses on a Likert scale for several emotional conditions.

ANOVA Analysis: An analysis of variance (ANOVA) to assess the impact of Condition and BetrayalChoices on Reaction Time.

Post-Hoc Analysis: Estimated marginal means (EMMs) and pairwise comparisons using least significant difference (LSD) tests.

Visualization: Plots including bar plots with error bars and significance annotations.

# Statistical Methods
ANOVA: The model tests the main effects of Condition and Betrayal Choices as well as their interaction on Reaction Time.

Post-Hoc Comparisons (LSD): Pairwise comparisons between condition pairs using the emmeans package to calculate estimated marginal means.

Visualization: The ggplot2 package is used to create the bar plots, while the geom_signif function adds significance annotations.

# Prerequisites
Make sure to install the following R packages before running the analysis:
ggplot2, readr, emmeans, stats, and tidyverse

To install these packages, run:

install.packages(c("ggplot2", "readr", "emmeans", "stats", "tidyverse"))

# Conclusion
This document provides a comprehensive statistical analysis and visualization of Reaction Time data in relation to different emotional Conditions and Betrayal Choices. It serves to explore how Condition (Excited, Angry, Calm, Sad) influences reaction times and whether Betrayal Choices interact with emotional states.