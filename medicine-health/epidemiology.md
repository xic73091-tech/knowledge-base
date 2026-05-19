---
domain: medicine-health
subdomain: epidemiology
title: "Epidemiology"
description: "The study of disease distribution, determinants, and control in populations"
created: 2026-05-15
updated: 2026-05-15
tags: [disease, population, incidence, prevalence, risk factors, outbreak, surveillance, public health]
prerequisites: [natural-sciences/biology, natural-sciences/statistics]
related: [medicine-health/public-health, medicine-health/clinical-medicine, natural-sciences/statistics]
difficulty: introductory
completeness: developing
---

# Epidemiology

## Overview

Epidemiology is the foundational science of public health — the study of how diseases are distributed across populations and what factors determine their occurrence. It provides the methods to identify risk factors, evaluate interventions, and inform health policy. From John Snow's cholera investigation to COVID-19 contact tracing, epidemiology is how we understand and control disease at scale.

## Core Concepts

### Measures of Disease Frequency
- **Incidence**: Number of new cases in a population over a time period; measures risk
- **Prevalence**: Number of existing cases at a point in time; measures burden
- **Cumulative Incidence**: Proportion of population that develops disease over a specified period
- **Incidence Rate**: Cases per person-time; accounts for varying follow-up times
- **Mortality Rate**: Deaths per population per year; case fatality rate (deaths/cases)

### Study Designs
- **Descriptive**: Case reports, case series, cross-sectional surveys; generating hypotheses
- **Analytical Observational**:
  - **Cohort**: Follow exposed and unexposed groups forward; measures incidence and relative risk
  - **Case-Control**: Compare diseased and non-diseased groups backward; measures odds ratio
  - **Cross-Sectional**: Snapshot of exposure and disease at one time; prevalence
- **Experimental**: Randomized controlled trials (RCTs); gold standard for causal inference
- **Ecological**: Comparing groups, not individuals; ecological fallacy risk

### Measures of Association
- **Relative Risk (RR)**: Ratio of incidence in exposed vs unexposed; RR=1 means no association
- **Odds Ratio (OR)**: Approximates RR in case-control studies and rare diseases
- **Attributable Risk**: Excess risk due to exposure; public health impact
- **Hazard Ratio**: Time-to-event measure; Cox regression output
- **Number Needed to Treat (NNT)**: How many must be treated to prevent one case

### Bias & Confounding
- **Selection Bias**: Systematic error in how participants are chosen; Berkson's bias
- **Information Bias**: Misclassification of exposure or outcome; recall bias, observer bias
- **Confounding**: A third variable associated with both exposure and outcome; controlled by randomization, stratification, regression, matching
- **Effect Modification**: The association differs across subgroups; tested by interaction terms
- **Collider Bias**: Conditioning on a common effect of exposure and outcome; Berkson's paradox

### Causal Inference
- **Bradford Hill Criteria**: Strength, consistency, specificity, temporality, biological gradient, plausibility, coherence, experiment, analogy
- **Directed Acyclic Graphs (DAGs)**: Visualizing causal assumptions; identifying confounders, mediators, colliders
- **Counterfactual Framework** (Rubin): What would have happened without exposure?
- **Natural Experiments**: Instrumental variables, regression discontinuity, difference-in-differences
- **Mendelian Randomization**: Using genetic variants as instruments for causal inference

### Outbreak Investigation
- **Steps**: Confirm diagnosis, define cases, describe by person/place/time, develop hypotheses, test, implement control, communicate
- **Epidemic Curves**: Visualizing outbreak timing; point source vs propagated vs continuous
- **Contact Tracing**: Identifying and monitoring exposed individuals; quarantine and isolation
- **Basic Reproduction Number (R₀)**: Average number of secondary cases from one infected person in a fully susceptible population
- **Herd Immunity Threshold**: Proportion immune needed to stop transmission; 1 - 1/R₀

### Screening & Diagnosis
- **Sensitivity**: Proportion of true positives correctly identified
- **Specificity**: Proportion of true negatives correctly identified
- **Positive/Negative Predictive Value**: Probability of disease given test result; depends on prevalence
- **ROC Curves**: Trade-off between sensitivity and specificity; AUC as overall accuracy measure
- **Lead Time Bias**: Screening appears to improve survival by detecting disease earlier, not by extending life

### Surveillance
- **Passive Surveillance**: Routine reporting by healthcare providers
- **Active Surveillance**: Proactive case finding; sentinel surveillance
- **Syndromic Surveillance**: Monitoring symptoms before diagnosis; early warning systems
- **Wastewater Surveillance**: Population-level pathogen monitoring; used in COVID-19

## Key Theories

| Theory | Description |
|--------|-------------|
| Epidemiologic Triad | Agent, host, and environment interaction in infectious disease causation |
| Web of Causation | Multiple interacting factors cause disease; no single cause |
| Prevention Paradox | A preventive measure benefits the population but may offer little to each individual |
| Fundamental Cause Theory | Social conditions (poverty, education) are root causes that shape disease risk |

## Important Figures

- **John Snow**: Father of epidemiology; cholera investigation in London (1854)
- **Richard Doll & Austin Bradford Hill**: Smoking and lung cancer; established modern cohort study methodology
- **Edward Jenner**: Smallpox vaccine; origin of immunization
- **Robert Koch**: Koch's postulates; germ theory
- **Alexander Langmuir**: Founded CDC's Epidemic Intelligence Service (EIS)
- **Geoffrey Rose**: "Sick individuals and sick populations"; population-level prevention

## Frontiers

- **Precision Epidemiology**: Integrating genomics, exposomics, and digital data for personalized risk prediction
- **Real-Time Surveillance**: Wearables, mobility data, social media for early outbreak detection; privacy trade-offs
- **Climate Change and Disease**: Shifting vector ranges, heat-related mortality, food insecurity; modeling future burden
- **Causal Inference at Scale**: Applying machine learning to causal questions; target trial emulation from observational data
- **Pandemic Preparedness**: Building resilient surveillance, rapid vaccine development, equitable distribution systems

## Applications

- **Infectious Disease Control**: Outbreak investigation, contact tracing, vaccination programs
- **Chronic Disease**: Risk factor identification, screening program evaluation, prevention strategies
- **Environmental Health**: Air pollution, water contamination, occupational exposures
- **Pharmacoepidemiology**: Drug safety monitoring, post-marketing surveillance, comparative effectiveness
- **Health Services Research**: Access to care, quality of care, health system performance
- **Genetic Epidemiology**: Gene-disease associations, gene-environment interactions, polygenic risk scores

## Classic Works

- **"Epidemiology: An Introduction"** by Kenneth Rothman — Clear, rigorous introduction to epidemiologic reasoning and causal inference
- **"Modern Epidemiology"** by Rothman, Greenland & Lash — The comprehensive reference for epidemiologic methods; advanced and authoritative
- **"Gordis Epidemiology"** by Celentano & Szklo — Accessible textbook widely used in public health courses
- **"The Ghost Map"** by Steven Johnson — Narrative of John Snow's cholera investigation; the birth of epidemiology as a science
- **"Epidemiology: Beyond the Basics"** by Szklo & Nieto — Intermediate-level text on study design and data analysis

## See Also

- [Public Health](./public-health.md) — Population health, health policy, prevention
- [Statistics](../natural-sciences/statistics.md) — Biostatistics, study design, causal inference
- [Clinical Medicine](./clinical-medicine.md) — Individual diagnosis and treatment
- [Biology](../natural-sciences/biology.md) — Microbiology, immunology, genetics
