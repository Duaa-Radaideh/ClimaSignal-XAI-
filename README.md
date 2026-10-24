# ClimaSignal-XAI

**Digital Signal Processing and Explainable AI for Climate Anomaly Detection**

## Overview

ClimaSignal-XAI is a research-oriented project exploring how Digital Signal Processing (DSP) techniques and Explainable Artificial Intelligence (XAI) can be combined to investigate climate anomaly detection.

The project focuses on daily air temperature data from selected locations in Jordan, using signal processing, machine learning, and explainability methods to study patterns, detect unusual observations, and evaluate model behavior.

## Research Question

Does digital signal preprocessing improve climate anomaly-detection performance, and how reliable are the explanations produced by the resulting machine-learning models?

## Objectives

- Collect and explore daily temperature data from NASA POWER.
- Analyze temporal patterns and frequency characteristics of climate signals.
- Apply digital signal processing techniques and extract relevant features.
- Compare machine-learning models using baseline and signal-processed features.
- Investigate model predictions using explainable AI techniques.
- Evaluate predictive performance and explanation reliability using appropriate metrics.

## Data Source

**NASA POWER Project**

The initial data collection focuses on daily mean air temperature at 2 meters (`T2M`) for Amman, Irbid, and Aqaba, Jordan.

The initial dataset covers 2020 and is intended for pipeline development and preliminary exploration. A longer observation period may be required for more robust seasonal and climate-related conclusions.

## Methodology

1. Data collection and quality assessment.
2. Exploratory data analysis and visualization.
3. Temporal and frequency-domain signal analysis.
4. Signal preprocessing and feature extraction.
5. Machine-learning model development and comparison.
6. Explainability analysis and robustness evaluation.
7. Results interpretation and documentation.

## Technology Stack

- Python
- Jupyter Notebook
- NumPy and Pandas
- SciPy
- Matplotlib
- Scikit-learn
- SHAP and LIME (planned)

## Project Status

**Early development**

The initial project structure, environment setup, and data collection workflow are being developed. Model evaluation and explainability experiments have not yet been completed.

## Scientific Considerations

- Anomaly definitions must be clearly established and documented.
- Model evaluation should respect temporal ordering to reduce data leakage.
- Any statistically generated anomaly labels must be distinguished from independently verified climate events.
- Feature importance and model explanations do not establish causal relationships.
- Results will be reported based on experimental evidence rather than assumed improvements.

## Repository Structure

```text
ClimaSignal-XAI/
├── notebooks/
├── data/
│   ├── raw/
│   └── processed/
├── results/
│   ├── figures/
│   └── tables/
├── src/
├── docs/
└── README.md
```

## Research Goal

To develop a transparent and reproducible experimental framework for investigating the relationship between digital signal processing, climate anomaly detection, and explainable machine learning.

---

*This project is under active development. Findings and conclusions will be added after the experiments have been conducted and evaluated.*
