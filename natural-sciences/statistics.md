---
domain: natural-sciences
subdomain: statistics
title: "Statistics & Data Science"
description: "The science of collecting, analyzing, and interpreting data"
created: 2026-05-15
updated: 2026-06-02
tags: [probability, inference, regression, hypothesis testing, data analysis, machine learning, bayesian, time-series, survival-analysis, causal-inference, spatial-statistics]
prerequisites: [natural-sciences/mathematics]
related: [natural-sciences/mathematics, social-sciences/economics, engineering-technology/computer-science]
difficulty: intermediate
completeness: comprehensive
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
- **Principal Component Analysis (PCA)**: Dimensionality reduction; finding orthogonal axes of maximum variance; explained variance; scree plots; biplots
- **Factor Analysis**: Latent variable modeling; exploratory vs confirmatory; factor rotation (varimax, promax); factor loadings interpretation
- **Cluster Analysis**: K-means (elbow method, silhouette score), hierarchical (agglomerative, divisive), DBSCAN, HDBSCAN; finding natural groupings; validation metrics
- **Discriminant Analysis**: Linear discriminant analysis (LDA), quadratic discriminant analysis (QDA); classification based on group differences; Fisher's linear discriminant
- **Correspondence Analysis**: Analyzing contingency tables; visualizing categorical relationships

### Time Series Analysis
- **Components**: Trend (long-term direction), seasonality (periodic fluctuations), cyclical (non-periodic), residual (noise)
- **Stationarity**: Weak vs strong stationarity; Augmented Dickey-Fuller test; differencing for stationarity
- **Autocorrelation**: ACF (autocorrelation function), PACF (partial autocorrelation function); identifying ARMA orders
- **ARIMA Models**: Autoregressive Integrated Moving Average; AR(p), MA(q), ARMA(p,q), ARIMA(p,d,q); seasonal ARIMA (SARIMA)
- **Exponential Smoothing**: Simple, Holt's linear trend, Holt-Winters (additive/multiplicative seasonality); ETS models
- **GARCH Models**: Generalized Autoregressive Conditional Heteroskedasticity; volatility clustering; financial time series
- **Spectral Analysis**: Fourier transform; periodogram; wavelet analysis for time-frequency decomposition
- **State Space Models**: Kalman filtering; dynamic linear models; structural time series

### Survival Analysis
- **Survival Functions**: Kaplan-Meier estimator; cumulative hazard function; survivor function
- **Censoring**: Right-censoring, left-censoring, interval-censoring; handling incomplete data
- **Hazard Models**: Cox proportional hazards model (semi-parametric); accelerated failure time (AFT) models; parametric models (Weibull, exponential)
- **Log-Rank Test**: Comparing survival curves between groups; hypothesis testing
- **Time-Varying Covariates**: Handling time-dependent predictors in survival models
- **Competing Risks**: Multiple failure types; cumulative incidence function

### Bayesian Statistics (Advanced)
- **Prior Specification**: Conjugate vs non-conjugate; weakly informative priors; prior elicitation
- **Posterior Inference**: Analytical solutions; Markov Chain Monte Carlo (MCMC); Gibbs sampling, Metropolis-Hastings, Hamiltonian Monte Carlo
- **Hierarchical Models**: Multilevel modeling; shrinkage; partial pooling; exchangeability
- **Bayesian Model Comparison**: Bayes factors; Deviance Information Criterion (DIC); Leave-One-Out Cross-Validation (LOO)
- **Approximate Bayesian Computation**: Simulation-based inference for intractable likelihoods
- **Variational Inference**: Mean-field approximation; black-box variational inference; stochastic variational inference

### Experimental & Quasi-Experimental Methods
- **Randomized Controlled Trials (RCTs)**: Gold standard; complete randomization, block randomization, stratified randomization
- **Quasi-Experiments**: Regression discontinuity design (sharp, fuzzy); difference-in-differences (DiD); instrumental variables (IV)
- **Propensity Score Methods**: Matching (nearest neighbor, caliper), weighting (IPW), stratification; balancing covariates
- **Regression Adjustment**: ANCOVA; post-stratification; covariate adjustment in experiments
- **Sample Size Calculation**: Power analysis; minimum detectable effect; Type I/II error rates

### Causal Inference (Advanced)
- **Potential Outcomes Framework**: Rubin causal model; individual treatment effect (ITE), average treatment effect (ATE), conditional average treatment effect (CATE)
- **Directed Acyclic Graphs (DAGs)**: Confounders, mediators, colliders; backdoor criterion; frontdoor adjustment
- **Mediation Analysis**: Direct and indirect effects; causal mediation; natural effects
- **Instrumental Variables**: Relevance, exogeneity, monotonicity assumptions; two-stage least squares (2SLS)
- **Regression Discontinuity**: Sharp vs fuzzy designs; bandwidth selection; local linear regression
- **Synthetic Control**: Constructing counterfactuals for policy evaluation; placebo tests

### Spatial Statistics
- **Spatial Autocorrelation**: Moran's I, Geary's C; testing spatial dependence
- **Geostatistics**: Kriging (ordinary, universal, indicator); variograms; spatial interpolation
- **Spatial Regression**: Spatial lag model, spatial error model; accounting for spatial dependence
- **Point Pattern Analysis**: Ripley's K-function; nearest neighbor analysis; quadrat counting
- **GIS Integration**: Geocoding; spatial visualization; map projections

### Nonparametric Statistics
- **Distribution-Free Methods**: No assumptions about underlying distribution
- **Rank-Based Tests**: Wilcoxon signed-rank, Mann-Whitney U, Kruskal-Wallis; Friedman test
- **Nonparametric Regression**: Kernel regression, local polynomial regression; spline smoothing
- **Bootstrap Methods**: Nonparametric bootstrap; parametric bootstrap; bias-corrected intervals
- **Permutation Tests**: Exact inference via random permutation of labels

### High-Dimensional Statistics
- **Regularization**: Lasso (L1), Ridge (L2), Elastic Net; variable selection; shrinkage
- **Dimensionality Reduction**: t-SNE, UMAP, autoencoders; visualization of high-dimensional data
- **Sparse Learning**: Sparse PCA, sparse regression; compressed sensing
- **Multiple Testing**: Bonferroni correction, Benjamini-Hochberg FDR; controlling family-wise error rate
- **Stability Selection**: Ensuring robust variable selection across subsamples

## Key Theories

| Theory | Description |
|--------|-------------|
| Central Limit Theorem | Sample means are normally distributed for large n, regardless of population distribution |
| Bayes' Theorem | Posterior probability proportional to prior × likelihood |
| Neyman-Pearson Framework | Hypothesis testing with controlled error rates |
| Gauss-Markov Theorem | OLS estimators are best linear unbiased estimators under standard assumptions |
| Law of Large Numbers | Sample averages converge to expected value as sample size grows |
| Lindeberg-Lévy CLT | More general form of CLT without identical distribution assumption |
| Cramér-Rao Lower Bound | Lower bound on variance of unbiased estimators |
| Sufficiency Principle | Sufficient statistics capture all information about parameters |
| Rao-Blackwell Theorem | Improve unbiased estimators using sufficient statistics |
| Bootstrap Principle | Resample data to estimate sampling distribution |
| Propensity Score Theorem | Conditional independence given propensity score implies unconfoundedness |
| Rubin Causal Model | Potential outcomes framework for causal inference |

## Important Figures

- **Carl Friedrich Gauss**: Least squares; normal distribution
- **Ronald Fisher**: ANOVA, maximum likelihood, fiducial inference; experimental design
- **Thomas Bayes**: Bayesian inference (posthumously published)
- **Jerzy Neyman & Egon Pearson**: Hypothesis testing framework
- **John Tukey**: Exploratory data analysis; Fast Fourier Transform
- **Bradley Efron**: Bootstrap resampling method
- **Judea Pearl**: Causal inference; do-calculus; DAGs

## Frontiers

- **Causal Machine Learning**: Combining causal inference with ML for robust predictions and interventions; heterogeneous treatment effects; uplift modeling
- **High-Dimensional Statistics**: Inference when variables outnumber observations (p >> n); sparsity assumptions; stability selection; multiple testing correction
- **Reproducibility Crisis**: p-hacking, publication bias; pre-registration, registered reports, open data, and open code as solutions
- **Algorithmic Fairness**: Detecting and mitigating bias in statistical models and ML systems; fairness metrics; debiasing techniques
- **Privacy-Preserving Statistics**: Differential privacy; federated learning; secure multi-party computation; analyzing sensitive data without exposure
- **Bayesian Deep Learning**: Combining deep neural networks with Bayesian inference for uncertainty quantification; probabilistic deep learning
- **Online & Streaming Statistics**: Real-time inference on streaming data; concept drift adaptation; incremental learning
- **Topological Data Analysis**: Using algebraic topology to analyze complex datasets; persistent homology; shape recognition
- **Explainable AI (XAI)**: Interpreting black-box models; SHAP, LIME, attention visualization; model-agnostic explanations
- **Time Series Forecasting with Deep Learning**: Transformers for time series; Temporal Fusion Transformers; long-range dependencies

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
