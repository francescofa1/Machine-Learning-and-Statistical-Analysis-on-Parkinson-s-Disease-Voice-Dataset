# Machine-Learning-and-Statistical-Analysis-on-Parkinson-s-Disease-Voice-Dataset

# Parkinson's Disease Progression Prediction from Voice Signals

This project explores the use of voice-based biomedical features to predict the severity of Parkinson’s Disease using both statistical analysis and machine learning models.  
The dataset contains biomedical voice measurements from patients with early-stage Parkinson’s disease, collected over several months.

---

## Objectives

- Explore and visualize the relationships between vocal biomarkers and clinical scores (UPDRS)
- Perform statistical hypothesis testing to assess distributional differences and group variability
- Predict `motor_UPDRS` and `total_UPDRS` scores using regression models
- Classify patients into "mild" vs "severe" Parkinson's using classification models
- Understand feature contributions using feature importance and model coefficients
- Evaluate models using metrics (MAE, RMSE, R², Accuracy, AUC, etc.) and comparative plots

---

## Dataset

- **Source:** [UCI Machine Learning Repository – Parkinson Telemonitoring](https://archive.ics.uci.edu/ml/datasets/Parkinsons+Telemonitoring)
- **Description:** Biomedical voice measurements from 42 patients over a 6-month period (5875 total recordings)
- **Target Variables:**  
  - `motor_UPDRS`: Motor component of the Unified Parkinson's Disease Rating Scale  
  - `total_UPDRS`: Total score from clinician evaluation  

Note: The dataset is included for academic use. If needed, it can be downloaded from the official source.

---

## Models and Methods Used

### Statistical Analysis
- Shapiro-Wilk Test for Normality
- Kruskal-Wallis Test for group differences
- Chi-squared Test for categorical association
- Correlation matrix and heatmaps

### Machine Learning
- Regression Models:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- Classification Models:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier

### Clustering
- K-Means Clustering (n=3)
- Cluster-wise UPDRS and sex distribution analysis

---

## Evaluation Metrics

Regression:
- MAE
- RMSE
- R²

Classification:
- Accuracy
- Precision
- Recall
- F1 Score
- AUC-ROC
- Average Precision (PR Curve)

---

## Visualizations

- Boxplots, heatmaps, histograms
- Cluster analysis visualizations
- ROC Curve & Precision-Recall Curve
- Feature Importance and Coefficient Barplots
- Comparative Metric Bar Charts with labels

---

## Repository Structure

