# Trustworthy AI and Data Analysis – Wine Quality Prediction

## Overview

This repository presents a complete data analysis and machine learning workflow using the Wine Quality dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality). The project focuses on building both whitebox and blackbox models, evaluating their behavior, applying model explainability techniques, and reflecting on ethical implications.

The dataset includes physicochemical properties and quality scores of red and white vinho verde wines produced in northern Portugal. This work was completed as part of the "Trustworthy AI and Data Analysis" course at BME VIK.

## Contents

- **Exploratory Data Analysis**  
  `Wine_quality_analysis.ipynb`  
  Dataset profiling, variable descriptions, distributions, correlations, and initial findings.

- **Whitebox Model**  
  `Model_comparison_and_ethical_survey.ipynb`  
  Decision Tree Classifier trained and evaluated to provide a transparent, interpretable baseline model.

- **Blackbox Model**  
  `Black_box_model_analysis.ipynb`  
  Feedforward neural network built using Keras, optimized for performance and later interpreted using explanation tools.

- **Model Comparison & Ethical Evaluation**  
  `Model_comparison_and_ethical_survey.ipynb`  
  Comparison of models' predictive capabilities and interpretability. Discussion of model transparency, potential bias, and ethical use.

- **Model Artifact**  
  `wine_quality_model.keras`  
  Saved Keras model (blackbox), ready for inference or fine-tuning.

## Evaluation Metrics

Models were evaluated using standard performance and fairness metrics, including:

- Accuracy
- Sensitivity (True Positive Rate)
- Specificity (True Negative Rate)
- ROC Curve & AUROC
- Precision & Recall
- Precision-Recall Curve & AUPR

## Explainability

To improve trust and transparency in the blackbox model:

- **LIME** (Local Interpretable Model-agnostic Explanations) was used for instance-level interpretation.
- **SHAP** (SHapley Additive exPlanations) was applied for global and local feature importance analysis.








