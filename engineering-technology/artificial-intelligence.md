---
domain: engineering-technology
subdomain: artificial-intelligence
title: "Artificial Intelligence & Machine Learning"
description: "The study of intelligent agents and systems that learn from data"
created: 2026-06-02
updated: 2026-06-02
tags: [AI, ML, machine-learning, deep-learning, neural-networks, data, algorithms, computer-vision, NLP]
prerequisites: [natural-sciences/mathematics, natural-sciences/statistics, engineering-technology/computer-science]
related: [engineering-technology/computer-science, engineering-technology/data-science]
difficulty: intermediate
completeness: comprehensive
---

# Artificial Intelligence & Machine Learning

## Overview

Artificial Intelligence (AI) is the broad field of creating intelligent systems that can perform tasks typically requiring human intelligence. Machine Learning (ML), a subfield of AI, focuses on developing algorithms that learn patterns from data and improve with experience without explicit programming. Deep Learning, a further subfield, uses deep neural networks inspired by the human brain to model complex patterns in large datasets. These technologies are transforming industries from healthcare to finance to transportation.

## Core Concepts

### AI Fundamentals
- **Strong AI vs Weak AI**: General intelligence vs narrow task-specific intelligence
- **Symbolic AI**: Rule-based systems, expert systems, logic programming
- **Subsymbolic AI**: Neural networks, fuzzy systems, evolutionary computation
- **Reinforcement Learning**: Agents, environments, states, actions, rewards
- **AI Safety & Alignment**: Ensuring AI systems act in human-aligned ways
- **Turing Test**: Evaluating machine intelligence through conversation

### Machine Learning Overview
- **Supervised Learning**: Labeled data, classification, regression
- **Unsupervised Learning**: Unlabeled data, clustering, dimensionality reduction
- **Reinforcement Learning**: Trial-and-error, Markov decision processes, policy learning
- **Semi-Supervised Learning**: Combination of labeled and unlabeled data
- **Self-Supervised Learning**: Learning from data itself, pretext tasks
- **Transfer Learning**: Leveraging pre-trained models for new tasks

### Supervised Learning
- **Classification**: Predicting discrete classes; logistic regression, SVM, decision trees
- **Regression**: Predicting continuous values; linear regression, ridge, lasso
- **Model Evaluation**: Train-validation-test splits, cross-validation, metrics (accuracy, precision, recall, F1, MSE, MAE, R²)
- **Overfitting/Underfitting**: Bias-variance tradeoff, regularization (L1/L2), dropout, early stopping
- **Ensemble Methods**: Random forests, gradient boosting (XGBoost, LightGBM, CatBoost), bagging, stacking
- **Feature Engineering**: Feature selection, extraction, scaling, encoding categorical variables

### Unsupervised & Semi-Supervised Learning
- **Clustering**: K-means, hierarchical, DBSCAN, Gaussian mixture models
- **Dimensionality Reduction**: PCA, t-SNE, UMAP, autoencoders
- **Anomaly Detection**: Isolation forests, One-class SVM, autoencoders, density-based
- **Association Rule Mining**: Apriori, FP-growth, market basket analysis
- **Self-Supervised Learning**: Contrastive learning, masked language modeling, image inpainting
- **Semi-Supervised Methods**: Label propagation, consistency regularization, VAT

### Deep Learning
- **Neural Network Basics**: Neurons, layers, activation functions (ReLU, sigmoid, tanh), backpropagation, gradient descent
- **Feedforward Networks**: MLPs, dense layers, initialization (Xavier, He), optimizers (SGD, Adam, RMSprop)
- **Convolutional Neural Networks (CNNs)**: Convolutions, pooling, architectures (LeNet, AlexNet, VGG, ResNet, Inception, EfficientNet)
- **Recurrent Neural Networks (RNNs) & LSTMs/GRUs**: Sequence modeling, vanishing gradients, gated units
- **Transformers**: Attention mechanisms, self-attention, multi-head attention, positional encoding
- **Autoencoders & Variational Autoencoders (VAEs)**: Dimensionality reduction, generation, latent spaces
- **Generative Models**: GANs, diffusion models, normalizing flows, autoregressive models

### Computer Vision
- **Image Classification**: CNN architectures, transfer learning, fine-tuning
- **Object Detection**: R-CNN, Fast R-CNN, Faster R-CNN, YOLO, SSD, RetinaNet
- **Semantic/Instance/Panoptic Segmentation**: U-Net, Mask R-CNN, DeepLab, Panoptic FPN
- **Image Generation**: GANs, diffusion models (Stable Diffusion, DALL-E), VAEs, autoregressive models
- **Video Understanding**: Action recognition, video classification, optical flow, tracking
- **3D Computer Vision**: Point clouds, 3D reconstruction, NeRF, 3D object detection
- **Face Recognition & Analysis**: Face detection, verification, recognition, landmark detection

### Natural Language Processing (NLP)
- **Text Preprocessing**: Tokenization, stemming, lemmatization, stopword removal
- **Word Embeddings**: Word2Vec, GloVe, FastText, contextual embeddings
- **Language Models**: N-grams, RNN/LSTM language models, transformer language models
- **Sequence Modeling**: Text classification, sentiment analysis, named entity recognition (NER), part-of-speech tagging
- **Machine Translation**: Seq2Seq, attention, transformers, multilingual models
- **Question Answering**: Extractive QA, generative QA, reading comprehension
- **Text Generation & Summarization**: Abstractive/extractive summarization, chatbots, dialogue systems

### Reinforcement Learning
- **Markov Decision Processes (MDPs)**: States, actions, transitions, rewards, discount factor
- **Value-Based Methods**: Q-learning, Deep Q-Networks (DQN), Double DQN, Dueling DQN
- **Policy-Based Methods**: REINFORCE, policy gradients, PPO, TRPO, A2C/A3C
- **Actor-Critic Methods**: Advantage estimation, combined policy/value learning
- **Multi-Agent RL**: Cooperative/competitive settings, MARL, MADDPG
- **Inverse RL & Imitation Learning**: Learning from demonstrations, behavioral cloning
- **RL in Practice**: Exploration vs exploitation, reward engineering, training stability

### Foundation Models & Large Language Models (LLMs)
- **Transformer Architectures**: GPT, BERT, T5, PaLM, Llama, Mistral
- **Pre-training & Fine-Tuning**: Self-supervised pre-training, instruction tuning, RLHF
- **Prompt Engineering**: Few-shot learning, chain-of-thought, prompt tuning
- **Alignment & Safety**: RLHF, constitutional AI, red-teaming, safety training
- **Capabilities**: Reasoning, coding, creativity, multilinguality, tool use
- **Applications**: Chatbots, content generation, coding assistants, tutoring, research
- **Limitations**: Hallucinations, context window, biases, computational cost

### ML Engineering & MLOps
- **Data Engineering**: Data pipelines, ETL/ELT, data lakes, data warehouses
- **Feature Stores**: Centralized feature management, offline/online features
- **Model Training**: Experiment tracking (MLflow, Weights & Biases), distributed training, hyperparameter tuning
- **Model Deployment**: REST APIs, batch/streaming inference, serverless, edge deployment
- **Model Monitoring**: Data drift, concept drift, performance monitoring, logging
- **MLOps Platforms**: Kubeflow, MLflow, SageMaker, Vertex AI
- **Responsible AI**: Fairness, accountability, transparency, explainability, privacy

### Explainable AI (XAI)
- **Interpretability vs Explainability**: Transparent models vs post-hoc explanations
- **Local Explanations**: LIME, SHAP, attention weights, gradient-based methods
- **Global Explanations**: Feature importance, partial dependence plots, surrogate models
- **Model-Agnostic Methods**: Working with any ML model
- **Visual Explanations**: Saliency maps, activation maximization, concept activation vectors
- **Human-Centered XAI**: Designing explanations for human understanding, trust, and decision-making

### AI Ethics & Responsible AI
- **Bias & Fairness**: Algorithmic bias, fairness metrics, debiasing techniques
- **Privacy**: Differential privacy, federated learning, anonymization
- **Accountability & Transparency**: Model cards, data sheets, auditability
- **Safety & Robustness**: Adversarial examples, robustness, safe exploration
- **Existential Risk**: AGI safety, alignment, long-term risks
- **Regulation & Policy**: AI Act, executive orders, industry guidelines

### AI Applications
- **Healthcare**: Medical imaging, drug discovery, diagnostics, personalized medicine
- **Finance**: Fraud detection, algorithmic trading, credit scoring, risk assessment
- **Autonomous Systems**: Self-driving cars, drones, robotics, warehouse automation
- **Recommendation Systems**: Content recommendation, collaborative filtering, hybrid systems
- **Creative AI**: Art generation, music composition, writing, design
- **Climate & Sustainability**: Climate modeling, weather prediction, energy optimization, carbon capture
- **Education**: Intelligent tutoring, personalized learning, automated grading

## Key Theories

| Theory | Key Figure | Core Idea |
|--------|-----------|-----------|
| Turing Machine | Alan Turing | Universal computational model |
| Information Theory | Claude Shannon | Quantifying information, entropy |
| Backpropagation | Rumelhart, Hinton, Williams | Efficient gradient computation for neural networks |
| Reinforcement Learning | Sutton & Barto | Framework for learning from interaction |
| Universal Approximation Theorem | Hornik et al. | Neural networks can approximate any continuous function |
| Attention Mechanism | Vaswani et al. | Focusing on relevant parts of input |
| Transformer | Vaswani et al. | Architecture based solely on attention |

## Important Figures

- **Alan Turing**: Turing machine, Turing test, computing foundations
- **John McCarthy**: Coined "artificial intelligence", LISP
- **Marvin Minsky**: AI pioneer, perceptrons, MIT AI Lab
- **Geoffrey Hinton**: Backpropagation, deep learning, CNNs, "Godfather of AI"
- **Yann LeCun**: CNNs, LeNet, Facebook AI, "Godfather of AI"
- **Yoshua Bengio**: Deep learning, RNNs, neural language models, "Godfather of AI"
- **Andrew Ng**: Online education, Google Brain, Coursera, deep learning popularization
- **Demis Hassabis**: DeepMind, AlphaGo, AlphaFold
- **Ilya Sutskever**: OpenAI co-founder, AlexNet, GPT, ChatGPT
- **Jürgen Schmidhuber**: LSTMs, deep learning, meta-learning
- **Fei-Fei Li**: ImageNet, computer vision, AI4All
- **Timnit Gebru**: AI ethics, fairness, bias in AI

## Frontiers

- **AGI & Superintelligence**: Artificial general intelligence, human-level and beyond
- **Multimodal AI**: Combining vision, language, audio, robotics in unified models
- **AI for Science**: Drug discovery, materials science, climate science, mathematics
- **Neuro-Symbolic AI**: Combining neural networks with symbolic reasoning
- **Edge AI & TinyML**: Running AI on edge devices, low-power, real-time
- **Quantum AI**: Quantum computing for machine learning, quantum neural networks
- **Human-AI Collaboration**: Augmented intelligence, human-in-the-loop systems
- **Biologically Inspired AI**: Spiking neural networks, neuromorphic computing, brain-computer interfaces

## Applications

- **Computer Vision**: Image classification, object detection, face recognition, medical imaging
- **Natural Language Processing**: Machine translation, chatbots, sentiment analysis, summarization
- **Speech Recognition & Synthesis**: Speech-to-text, text-to-speech, voice assistants
- **Recommender Systems**: E-commerce, streaming, social media recommendations
- **Healthcare AI**: Medical diagnostics, drug discovery, personalized treatment
- **Autonomous Vehicles**: Self-driving cars, ADAS, perception, planning
- **Finance AI**: Fraud detection, algorithmic trading, risk assessment
- **Gaming AI**: Game playing, NPCs, procedural content generation

## Classic Works

- **"Computing Machinery and Intelligence"** by Alan Turing — Introduced Turing test
- **"Perceptrons"** by Minsky & Papert — Analyzed limitations of single-layer perceptrons
- **"Learning Representations by Back-Propagating Errors"** by Rumelhart, Hinton, Williams — Backpropagation breakthrough
- **"Reinforcement Learning: An Introduction"** by Sutton & Barto — RL textbook
- **"Deep Learning"** by Goodfellow, Bengio, Courville — Deep learning textbook
- **"Attention Is All You Need"** by Vaswani et al. — Transformer architecture
- **"ImageNet Classification with Deep Convolutional Neural Networks"** by Krizhevsky, Sutskever, Hinton — Deep learning revolution

## See Also

- [Computer Science](computer-science.md) — Algorithms, data structures, programming
- [Data Science](data-science.md) — Data pipelines, analytics, visualization
- [Neuroscience](neuroscience.md) — Biological inspiration for AI
- [Statistics](statistics.md) — Statistical foundations of ML
- [Mathematics](mathematics.md) — Linear algebra, calculus, optimization

