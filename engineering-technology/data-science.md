---
domain: engineering-technology
subdomain: data-science
title: "Data Science & Engineering"
description: "The practice of extracting knowledge and building systems from large-scale data"
created: 2026-05-15
updated: 2026-06-02
tags: [data, big data, machine learning, pipelines, analytics, visualization, ETL, cloud, MLOps, data-governance, deep-learning, feature-stores]
prerequisites: [engineering-technology/computer-science, natural-sciences/statistics]
related: [natural-sciences/statistics, engineering-technology/computer-science, social-sciences/economics]
difficulty: intermediate
completeness: comprehensive
---

# Data Science & Engineering

## Overview

Data science combines statistics, computer science, and domain expertise to extract insights and build systems from data. Data engineering focuses on the infrastructure — pipelines, storage, and processing — that makes large-scale data analysis possible. Together, they power modern decision-making in business, science, government, and technology.

## Core Concepts

### Data Engineering
- **Data Pipelines**: ETL (Extract, Transform, Load) and ELT; batch vs streaming; orchestration (Airflow, Prefect, Dagster); idempotency; retry logic; dead-letter queues
- **Data Storage**: Data warehouses (Snowflake, BigQuery, Redshift, Databricks SQL), data lakes (S3, ADLS, GCS, Delta Lake, Iceberg, Hudi), lakehouses; columnar vs row storage; column compression
- **Data Modeling**: Star schema, snowflake schema; dimensional modeling; slowly changing dimensions (SCD types 1-6); fact tables (transactional, periodic snapshot, accumulating snapshot)
- **Batch Processing**: MapReduce, Apache Spark, Hadoop, Dask; processing large historical datasets; partitioning; bucketing; caching strategies
- **Stream Processing**: Apache Kafka, Flink, Spark Streaming, Kafka Streams; real-time event processing; windowing (tumbling, sliding, session); exactly-once semantics
- **Data Quality**: Validation (Great Expectations, dbt tests), deduplication, missing value handling; data contracts; observability (data freshness, latency, error rates); profiling (Pandas Profiling, ydata-profiling)
- **Data Integration**: CDC (Change Data Capture) with Debezium; data synchronization; master data management (MDM); data virtualization

### Data Governance & Metadata Management
- **Data Catalogs**: Discovery and documentation; tools (Amundsen, DataHub, Collibra); lineage tracking
- **Data Governance Frameworks**: Roles (data owner, data steward, data engineer); policies; compliance (GDPR, CCPA, HIPAA)
- **Access Control**: RBAC (Role-Based Access Control), ABAC (Attribute-Based Access Control); data masking; encryption at rest and in transit
- **Metadata Management**: Business glossaries; data dictionaries; schema evolution; versioning
- **Data Lineage**: End-to-end tracking from source to consumption; impact analysis; root cause analysis

### MLOps (Advanced)
- **Model Lifecycle Management**: Training, validation, deployment, monitoring, retirement; MLOps maturity stages
- **Experiment Tracking**: MLflow, Weights & Biases, Neptune; hyperparameter tracking; artifact storage; reproducibility
- **Model Versioning**: DVC, Git LFS, MLflow Model Registry; model lineage; A/B/n testing
- **Model Deployment**: Batch inference, real-time inference (REST/gRPC), serverless (AWS Lambda, Google Cloud Functions); model serving (TorchServe, TensorRT, ONNX Runtime)
- **Model Monitoring**: Drift detection (data drift, concept drift, model performance drift); monitoring tools (Evidently AI, Arize, WhyLabs); alerting; retraining pipelines
- **Feature Stores**: Feast, Tecton, Hopsworks; feature validation; online vs offline storage; point-in-time correctness
- **CI/CD for ML**: Automated testing; model quality gates; infrastructure as code; canary deployments

### Statistical Foundations
- **Exploratory Data Analysis**: Distributions, correlations, outliers; visualization as first step
- **Hypothesis Testing**: A/B testing; significance, effect size, power
- **Regression & Prediction**: Linear, logistic, regularized (Lasso, Ridge); cross-validation
- **Time Series Analysis**: Trend, seasonality, stationarity; ARIMA, Prophet, neural approaches
- **Causal Inference**: Observational vs experimental; difference-in-differences, instrumental variables, propensity scores

### Machine Learning (Advanced)
- **Supervised Learning**: 
  - **Tree-Based Models**: Random forest, gradient boosting (XGBoost, LightGBM, CatBoost), stacking/ensemble methods
  - **Linear Models**: Linear regression, logistic regression, regularized variants (Lasso, Ridge, Elastic Net)
  - **Neural Networks**: Feedforward networks, CNNs (computer vision), RNNs/LSTMs/Transformers (sequence data); attention mechanisms
  - **Support Vector Machines**: Kernel trick; SVM for classification and regression
- **Unsupervised Learning**: 
  - **Clustering**: k-means, DBSCAN, HDBSCAN, hierarchical clustering, Gaussian Mixture Models
  - **Dimensionality Reduction**: PCA, t-SNE, UMAP, autoencoders, TSNE variants
  - **Anomaly Detection**: Isolation Forest, Autoencoder-based, One-Class SVM, DBSCAN outliers
- **Reinforcement Learning**: Q-learning, Deep Q-Networks (DQN), Policy Gradients, Actor-Critic, PPO (Proximal Policy Optimization)
- **Deep Learning Specializations**: 
  - **Natural Language Processing**: BERT, GPT, T5; text classification, NER, question answering, summarization
  - **Computer Vision**: ResNet, EfficientNet, YOLO (object detection), Stable Diffusion (generative)
  - **Time Series**: Transformers (Temporal Fusion Transformer, TimeNet), LSTM/GRU, Prophet, ARIMA variants
- **Feature Engineering**: Domain-informed feature creation; encoding categoricals (one-hot, target encoding, embeddings); handling imbalanced data (SMOTE, ADASYN); feature selection (mutual information, ANOVA, L1 regularization)
- **Model Evaluation**: Accuracy, precision, recall, F1, AUC-ROC, AUC-PR; confusion matrices; cross-validation (k-fold, stratified, time-series); calibration curves; lift charts
- **Hyperparameter Optimization**: Grid search, random search, Bayesian optimization (Optuna, Hyperopt); automated ML (AutoML tools)

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
| PAC Learning | Probably Approximately Correct learning framework; sample complexity bounds |
| Occam's Razor | Simpler models are preferred when they fit the data equally well |
| Curse of Dimensionality | High-dimensional data becomes sparse; distance metrics lose discriminative power |
| Universal Approximation Theorem | Neural networks with one hidden layer can approximate any continuous function |
| Ensemble Learning | Combining multiple models improves prediction accuracy (wisdom of crowds) |
| Representer Theorem | Solutions to kernel methods can be expressed as linear combinations of training examples |

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
