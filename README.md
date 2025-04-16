
# FairnessDPLab: A Comprehensive Benchmark for Evaluating Fairness in Artificial Intelligence (AI)

FairnessDPLab is a benchmarking tool designed to measure and evaluate fairness under different settings for artificial intelligence pipelines. One can experiment with different AI models on various datasets with or without differential privacy. This tool provides a structured environment to explore different fairness metrics, identify potential biases, and assess their impact on model outcomes when differential privacy is introduced.

## Features

With FairnessDPLab, you can:

- Experiment with various algorithms, including Naive Bayes, Logistic Regression, Random Forest, Decision Tree, Deep Learning, or implement custom models.
- Utilize multiple datasets to evaluate fairness under different conditions.
- Implement fairness metrics to analyze the performance and equity of AI models.
- Introduce differential privacy and see its effect on model outcomes.
- Save and track experimental results, enabling a deeper understanding of how different variables influence fairness in AI.

## Modules

![FairnessDPLab Overview](https://github.com/user-attachments/assets/205688f8-7c68-4dea-99f2-872e3202577e =800x600)

### Modeling Module
- Non-Private Modeling
- Differentially Private Models (DP Models)

### Experiment Tracking Module
- Track parameters and results over multiple experiments to identify patterns and biases.

### Data Ingestion Module
- Datasets supported: Adult, COMPAS, German Credit, and Custom Datasets

### Fairness Metrics Module
- Fairness metrics: Statistical Parity Difference (SPD), Disparate Impact (DI), Average Odds Difference (AOD), Equal Opportunity Difference (EOD), Theil Index (TI), False Discovery Rate Difference (FDRD), False Negative Rate Difference (FNRD), False Positive Rate Difference (FPRD)

## Installation

To get started with FairnessDPLab, clone the repository and just run the notebook.

## Usage

1. Configure the models and datasets as per your requirements.
2. Run experiments by selecting the models and metrics.
3. Track and analyze the results to understand fairness outcomes.

