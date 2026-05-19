---
domain: engineering-technology
subdomain: data-science
title: "Data Science & Engineering"
description: "The practice of extracting knowledge and building systems from large-scale data"
created: 2026-05-15
updated: 2026-05-15
tags: [data, big data, machine learning, pipelines, analytics, visualization, ETL, cloud]
prerequisites: [engineering-technology/computer-science, natural-sciences/statistics]
related: [natural-sciences/statistics, engineering-technology/computer-science, social-sciences/economics]
difficulty: introductory
completeness: developing
---

# Data Science & Engineering

## Overview

Data science combines statistics, computer science, and domain expertise to extract insights and build systems from data. Data engineering focuses on the infrastructure — pipelines, storage, and processing — that makes large-scale data analysis possible. Together, they power modern decision-making in business, science, government, and technology.

## Core Concepts

### Data Engineering
- **Data Pipelines**: ETL (Extract, Transform, Load) and ELT; batch vs streaming; orchestration (Airflow, Prefect)
- **Data Storage**: Data warehouses (Snowflake, BigQuery, Redshift), data lakes (S3, Delta Lake), lakehouses
- **Data Modeling**: Star schema, snowflake schema; dimensional modeling; slowly changing dimensions
- **Batch Processing**: MapReduce, Apache Spark, Hadoop; processing large historical datasets
- **Stream Processing**: Apache Kafka, Flink, Spark Streaming; real-time event processing
- **Data Quality**: Validation, deduplication, missing value handling; data contracts; observability

### Statistical Foundations
- **Exploratory Data Analysis**: Distributions, correlations, outliers; visualization as first step
- **Hypothesis Testing**: A/B testing; significance, effect size, power
- **Regression & Prediction**: Linear, logistic, regularized (Lasso, Ridge); cross-validation
- **Time Series Analysis**: Trend, seasonality, stationarity; ARIMA, Prophet, neural approaches
- **Causal Inference**: Observational vs experimental; difference-in-differences, instrumental variables, propensity scores

### Machine Learning
- **Supervised Learning**: Classification (random forest, gradient boosting, neural networks), regression
- **Unsupervised Learning**: Clustering (k-means, DBSCAN), dimensionality reduction (PCA, t-SNE, UMAP)
- **Feature Engineering**: Domain-informed feature creation; encoding categoricals; handling imbalanced data
- **Model Evaluation**: Accuracy, precision, recall, F1, AUC-ROC; confusion matrices; cross-validation
- **MLOps**: Model versioning, deployment, monitoring, retraining; experiment tracking (MLflow, W&B)

### Big Data Technologies
- **Distributed Computing**: Spark, Dask, Ray; parallel processing across clusters
- **Cloud Platforms**: AWS (Glue, Athena, EMR), GCP (Dataflow, Dataproc), Azure (Synapse, Databricks)
- **Query Engines**: Presto, Trino, Athena; querying data where it lives without moving it
- **Containerization**: Docker, Kubernetes for reproducible data environments
- **Infrastructure as Code**: Terraform, Pulumi; reproducible cloud infrastructure

### Data Visualization & Communication
- **Visualization Principles**: Tufte's data-ink ratio; choosing appropriate chart types; avoiding misleading graphics
- **Tools**: Matplotlib, Seaborn, Plotly, D3.js, Tableau, Power BI
- **Dashboards**: Real-time monitoring; drill-down capability; stakeholder-appropriate detail
- **Storytelling with Data**: Narrative structure; context and annotation; actionable recommendations
- **Notebooks**: Jupyter, Observable; literate programming for reproducible analysis

### Natural Language Processing for Data
- **Text Processing**: Tokenization, stemming, lemmatization, stop words; TF-IDF
- **Sentiment Analysis**: Opinion mining; aspect-based sentiment
- **Named Entity Recognition**: Extracting people, organizations, locations from text
- **Topic Modeling**: LDA, BERTopic; discovering themes in document collections
- **Large Language Models**: GPT, Claude, Llama; prompt engineering; RAG (retrieval-augmented generation)

### Ethics & Privacy
- **Data Privacy**: GDPR, CCPA; consent, right to deletion; anonymization vs pseudonymization
- **Algorithmic Fairness**: Bias detection; disparate impact; fairness constraints
- **Responsible AI**: Explainability (SHAP, LIME); model cards; impact assessments
- **Data Governance**: Ownership, access control, lineage tracking; regulatory compliance

## Key Theories

| Theory | Description |
|--------|-------------|
| No Free Lunch Theorem | No single model is best for all problems; domain knowledge matters |
| Bias-Variance Tradeoff | Model complexity trades off between underfitting and overfitting |
| CAP Theorem | Distributed systems: pick 2 of consistency, availability, partition tolerance |
| CRISP-DM | Cross-Industry Standard Process for Data Mining; standard workflow |

## Important Figures

- **DJ Patil & Jeff Hammerbacher**: Coined "data scientist" (~2008)
- **Hadley Wickham**: Tidyverse; grammar of graphics; tidy data principles
- **Jeff Dean**: Google's distributed systems and TensorFlow architecture
- **Fei-Fei Li**: ImageNet; democratized visual AI research
- **Cathy O'Neil**: Weapons of Math Destruction; algorithmic accountability
- **Hilary Mason**: Data science practice; Fast Forward Labs

## Frontiers

- **Foundation Models for Structured Data**: Can LLMs and large pretrained models revolutionize tabular data analysis the way they transformed NLP?
- **Real-Time ML**: Closing the gap between batch model training and real-time inference at scale
- **Data-Centric AI**: Shifting focus from model architecture to data quality, labeling, and curation
- **Synthetic Data**: Generating realistic training data for privacy, rare events, and model bootstrapping
- **Federated Learning**: Training models across distributed datasets without centralizing sensitive data

## Applications

- **Business Intelligence**: Customer analytics, revenue forecasting, market basket analysis
- **Healthcare**: Clinical trial analytics, disease prediction, operational efficiency
- **Finance**: Fraud detection, algorithmic trading, credit scoring, risk modeling
- **Science**: Genomics, climate modeling, particle physics, astronomy
- **Government**: Census analytics, policy evaluation, public health surveillance
- **Technology**: Recommendation systems, search ranking, ad targeting, A/B testing

## Classic Works

- **"Designing Data-Intensive Applications"** by Martin Kleppmann — Essential guide to distributed data systems; covers storage, replication, partitioning, and consistency
- **"The Elements of Statistical Learning"** by Hastie, Tibshirani & Friedman — Comprehensive reference for statistical learning methods underlying data science
- **"Python for Data Analysis"** by Wes McKinney — Practical guide to pandas, NumPy, and data wrangling by the creator of pandas
- **"Data Pipelines Pocket Reference"** by James Densmore — Concise guide to building reliable data pipelines
- **"Storytelling with Data"** by Cole Nussbaumer Knaflic — Practical guide to data visualization and communication

## See Also

- [Computer Science](./computer-science.md) — Algorithms, databases, distributed systems
- [Statistics](../natural-sciences/statistics.md) — Probability, inference, modeling
- [Mathematics](../natural-sciences/mathematics.md) — Linear algebra, optimization
- [Economics](../social-sciences/economics.md) — Econometrics, causal inference
