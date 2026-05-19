---
domain: natural-sciences
subdomain: statistics
title: "Statistics & Data Science"
description: "The science of collecting, analyzing, and interpreting data"
created: 2026-05-15
updated: 2026-05-15
tags: [probability, inference, regression, hypothesis testing, data analysis, machine learning, bayesian]
prerequisites: [natural-sciences/mathematics]
related: [natural-sciences/mathematics, social-sciences/economics, engineering-technology/computer-science]
difficulty: introductory
completeness: developing
---

# Statistics & Data Science

## Overview

Statistics is the science of collecting, organizing, analyzing, and interpreting data to make informed decisions under uncertainty. Data science extends this with computational methods, machine learning, and domain expertise to extract knowledge from large, complex datasets. Together, they form the quantitative backbone of modern science, business, and policy.

## Core Concepts

### Probability Theory
- **Random Variables**: Discrete vs continuous; probability distributions (normal, binomial, Poisson, exponential)
- **Probability Rules**: Addition, multiplication, conditional probability; Bayes' theorem
- **Expectation & Variance**: Mean, standard deviation; measures of central tendency and spread
- **Central Limit Theorem**: Sample means approach normal distribution regardless of population shape
- **Law of Large Numbers**: Sample averages converge to expected value as sample size grows

### Descriptive Statistics
- **Measures of Center**: Mean, median, mode; when each is appropriate
- **Measures of Spread**: Range, interquartile range, variance, standard deviation
- **Distributions**: Shape (skewness, kurtosis); normal, uniform, bimodal
- **Visualization**: Histograms, box plots, scatter plots, heatmaps; exploratory data analysis

### Statistical Inference
- **Point Estimation**: Sample statistics as estimates of population parameters; bias, consistency, efficiency
- **Confidence Intervals**: Range of plausible values for a parameter; interpretation pitfalls
- **Hypothesis Testing**: Null vs alternative hypothesis; p-values; Type I (false positive) and Type II (false negative) errors
- **Effect Size**: Practical significance vs statistical significance; Cohen's d, odds ratios
- **Power Analysis**: Determining sample size needed to detect effects

### Regression & Modeling
- **Linear Regression**: Least squares; assumptions (linearity, independence, homoscedasticity, normality); R²
- **Multiple Regression**: Controlling for confounders; multicollinearity; interaction effects
- **Logistic Regression**: Binary outcomes; odds ratios; classification
- **Generalized Linear Models**: Extending regression to non-normal outcomes (Poisson, gamma)
- **Model Selection**: AIC, BIC, cross-validation; overfitting vs underfitting

### Bayesian Statistics
- **Bayes' Theorem**: Updating beliefs with evidence; prior, likelihood, posterior
- **Bayesian Inference**: Credible intervals vs confidence intervals; posterior distributions
- **Conjugate Priors**: Computational convenience; beta-binomial, normal-normal
- **Markov Chain Monte Carlo (MCMC)**: Sampling from complex posteriors; Gibbs sampling, Metropolis-Hastings
- **Bayesian vs Frequentist**: Philosophical differences; practical implications

### Experimental Design
- **Randomization**: Eliminating confounders; randomized controlled trials (RCTs)
- **Blocking & Stratification**: Controlling for known sources of variation
- **Factorial Designs**: Studying multiple factors simultaneously; interaction effects
- **Sample Size Determination**: Power calculations; minimum detectable effect
- **Observational Studies**: Cohort, case-control, cross-sectional; causal inference challenges

### Multivariate Methods
- **Principal Component Analysis (PCA)**: Dimensionality reduction; finding orthogonal axes of maximum variance
- **Factor Analysis**: Latent variable modeling; exploratory vs confirmatory
- **Cluster Analysis**: K-means, hierarchical clustering; finding natural groupings
- **Discriminant Analysis**: Classification based on group differences
- **Time Series**: Autocorrelation; ARIMA models; trend, seasonality, stationarity

### Causal Inference
- **Correlation vs Causation**: Why observational data alone cannot establish causation
- **Randomized Experiments**: Gold standard for causal claims
- **Natural Experiments**: Instrumental variables, regression discontinuity, difference-in-differences
- **Directed Acyclic Graphs (DAGs)**: Visualizing causal assumptions; confounders, mediators, colliders
- **Rubin Causal Model**: Potential outcomes framework

## Key Theories

| Theory | Description |
|--------|-------------|
| Central Limit Theorem | Sample means are normally distributed for large n, regardless of population distribution |
| Bayes' Theorem | Posterior probability proportional to prior × likelihood |
| Neyman-Pearson Framework | Hypothesis testing with controlled error rates |
| Gauss-Markov Theorem | OLS estimators are best linear unbiased estimators under standard assumptions |

## Important Figures

- **Carl Friedrich Gauss**: Least squares; normal distribution
- **Ronald Fisher**: ANOVA, maximum likelihood, fiducial inference; experimental design
- **Thomas Bayes**: Bayesian inference (posthumously published)
- **Jerzy Neyman & Egon Pearson**: Hypothesis testing framework
- **John Tukey**: Exploratory data analysis; Fast Fourier Transform
- **Bradley Efron**: Bootstrap resampling method
- **Judea Pearl**: Causal inference; do-calculus; DAGs

## Frontiers

- **Causal Machine Learning**: Combining causal inference with ML for robust predictions and interventions
- **High-Dimensional Statistics**: Inference when variables outnumber observations (p >> n); sparsity assumptions
- **Reproducibility Crisis**: p-hacking, publication bias; pre-registration, registered reports as solutions
- **Algorithmic Fairness**: Detecting and mitigating bias in statistical models and ML systems
- **Privacy-Preserving Statistics**: Differential privacy; federated learning; analyzing sensitive data without exposure

## Applications

- **Medicine**: Clinical trials, epidemiology, diagnostic testing, meta-analysis
- **Business**: A/B testing, market research, quality control, risk modeling
- **Science**: Experimental analysis, modeling, simulation, reproducibility
- **Government**: Census, policy evaluation, economic indicators
- **Technology**: Recommendation systems, search ranking, anomaly detection
- **Sports**: Player evaluation, game strategy, predictive modeling

## Classic Works

- **"Statistical Inference"** by Casella & Berger — Rigorous graduate-level treatment of statistical theory
- **"The Elements of Statistical Learning"** by Hastie, Tibshirani & Friedman — Comprehensive reference for statistical learning methods
- **"Bayesian Data Analysis"** by Gelman et al. — Definitive guide to Bayesian methods and practice
- **"Causal Inference in Statistics"** by Pearl, Glymour & Jewell — Accessible introduction to causal reasoning with DAGs
- **"Think Stats"** by Allen Downey — Practical, programming-oriented introduction to statistics

## See Also

- [Mathematics](./mathematics.md) — Probability theory, linear algebra, optimization
- [Economics](../social-sciences/economics.md) — Econometrics, causal inference in social science
- [Computer Science](../engineering-technology/computer-science.md) — Machine learning, algorithms, data structures
- [Psychology](../social-sciences/psychology.md) — Research methods, experimental design
