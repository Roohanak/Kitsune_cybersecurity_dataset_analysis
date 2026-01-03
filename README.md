# Kitsune_cybersecurity_dataset_analysis
A personal cybersecurity ML project using the **Kitsune** dataset to detect malicious network activity (e.g., botnet-style behavior) from traffic-derived features.   This repo includes preprocessing, model training, evaluation, and interpretability artifacts (ROC curves, confusion matrices, and feature importance).

##  Project Objectives
- Detect malicious IoT network activity using ML techniques
- Evaluate model performance using standard classification metrics
- Interpret model decisions using feature importance analysis
- Produce reproducible, well-documented results suitable for cybersecurity research or internships

---

## Dataset
- **Kitsune Network Attack Dataset**
- Dataset is **not included** in this repository
- Features are derived from network traffic statistics
- Labels represent benign vs malicious activity

> This repo focuses on modeling and analysis, not dataset redistribution.

---

##  Methodology
1. **Data Preprocessing**
   - Feature selection and redundancy analysis
   - Preparation of train/test splits

2. **Model Training**
   - Trained ML models on extracted network features
   - Stored trained models for evaluation and reuse

3. **Evaluation**
   - Accuracy, precision, recall, F1-score
   - ROC curves and confusion matrices

4. **Interpretability**
   - Feature importance computation
   - Top contributing features analysis

---

##  Results & Artifacts
The repository includes the following evaluation outputs:

- **ROC Curves** → `roc_plots/`
- **Confusion Matrices & Metric Plots** → `metric_plots/`
- **Feature Importance Analysis** → `feature_importances/`
- **Consolidated Metrics** → `evaluation_metrics.csv`
- **Top & Redundant Features** → `combined_feature_importances.csv`, `redundant_features.csv`
