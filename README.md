# Applied Machine Learning & Data Science Portfolio

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

> **An end-to-end applied machine learning repository featuring six distinct projects spanning healthcare, bioinformatics, finance, real estate, and computer vision.**

---

## Project Directory

| No. | Project                              | Domain                     | Description |
|-----|--------------------------------------|----------------------------|-------------|
| 1   | Multi-Domain Data Clustering         | Environment & Genomics     | Applies robust preprocessing, PCA, and KMeans clustering across urban microclimate, obesity, and high-dimensional gene expression datasets. |
| 2   | Supervised Classification Suite      | Finance & Energy           | Predicts bank deposit subscriptions and smart grid stability using GridSearchCV-tuned SVMs, Logistic Regression (L1/L2), and KNN. |
| 3   | Neural Network Double Descent        | Deep Learning / CV         | Explores Multi-Layer Perceptron (MLP) architectures to successfully simulate and reproduce the theoretical "Double Descent" risk curve on MNIST. |
| 4   | Liver Cirrhosis Survival Prediction  | Healthcare Analytics       | Forecasts patient survival outcomes using Random Forest, SVM, and Logistic Regression, utilizing statistical imputation and SMOTE for extreme class imbalance. |
| 5   | Housing Price Prediction & App       | Real Estate (PropTech)     | Predicts urban property values using XGBoost and Random Forest, serialized and fully deployed as an interactive Streamlit web application. |
| 6   | Drug-Induced Autoimmunity (DIA)      | Bioinformatics             | Reproduces pharmaceutical research and introduces a novel, calibrated ElasticNet + RBF-SVM ensemble using mRMR-lite feature selection for drug safety screening. |


---

## 📖 Repository Overview
This repository serves as a comprehensive portfolio demonstrating the complete data science lifecycle. It houses six rigorous, independent projects that tackle complex, domain-specific business problems. The suite bridges the gap between theoretical machine learning and practical industry application, showcasing expertise in:

- > Unsupervised Learning: High-dimensional data clustering and dimensionality reduction.

- > Supervised Learning: Complex classification and regression pipelines handling extreme class imbalances.

- > Deep Learning: Neural network architecture optimization and theoretical risk curve validation.

- > Bioinformatics & Cheminformatics: Advanced feature selection (mRMR, Stability Selection) on molecular descriptors.

- > MLOps & Deployment: Translating predictive models into interactive, user-facing Streamlit web applications.

👉 **Explore the project notebooks in the root directory to see the full analysis.**

## Technical Architecture & Skills

**Core Technologies**

Machine Learning Capabilities

- **Algorithms:** Random Forest, XGBoost, Support Vector Machines (SVM), Logistic Regression, K-Nearest Neighbors, KMeans, Multi-Layer Perceptrons (MLP).

- **Feature Engineering:** PCA, ANOVA F-Tests, L1-Regularized Stability Selection, mRMR-lite (Minimum Redundancy Maximum Relevance), Genetic Algorithms.

- **Data Handling:** Statistical Imputation, SMOTE (Synthetic Minority Over-sampling Technique), Min-Max/Standard Scaling, Z-Score Normalization.

- **Model Evaluation:** K-Fold Cross Validation, ROC-AUC, Matthews Correlation Coefficient (MCC), F1-Score, Adjusted Rand Index (ARI), Platt Scaling (Probability Calibration).

## 🚀 Featured Deployment: Real Estate Price Prediction (Task 5)

As part of the fifth project, a robust machine learning model (utilizing XGBoost and Random Forest) for predicting urban property values has been fully serialized and deployed as an interactive web application. This demonstrates the complete MLOps lifecycle, transitioning from model training to production deployment.

- **Live Application:** [Streamlit Web App](https://house-price1-7xejatqm52axwjwiprxumh.streamlit.app/)
- **Application Source Code:** [GitHub Repository](https://github.com/nabankur14/House-Price-Prediction-App)

## Unified Methodology
While each project addresses a unique domain, they adhere to a strict, industry-standard machine learning pipeline:

1. Data Ingestion & Integrity Checks: Parsing structured/unstructured data, handling missing values via domain-appropriate imputation (Mean, Median, Mode), and identifying anomalies.

2. Exploratory Data Analysis (EDA): Utilizing Seaborn and Matplotlib to uncover hidden temporal trends, spatial distributions, and feature correlations.

3. Feature Engineering & Dimensionality Reduction: Applying PCA for genomic data, spatial parsing for environmental data, and mRMR-lite for molecular descriptors to eliminate noise and reduce multicollinearity.

4. Algorithmic Training & Tuning: Systematically evaluating multiple algorithms against baselines, utilizing GridSearchCV for exhaustive hyperparameter optimization.

5. Rigorous Validation: Preventing data leakage and ensuring generalizability through strict 5-Fold and 10-Fold cross-validation strategies, backed by external holdout sets.

6. Production Readiness: Serializing final models (Joblib/Pickle) and wrapping them in interactive web interfaces (Streamlit) for end-user accessibility.

## Getting Started
1. Prerequisites
Ensure you have Python 3.8+ installed. It is highly recommended to use a virtual environment.

### Installation

1. **Clone the repository:**

```bash
git clone https://github.com/nabankur14/sig720-machine-learning-course-projects.git
cd sig720-machine-learning-course-projects
```
2. **Create and activate a virtual environment:**

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. **Launch a specific project notebook:**
```bash
jupyter notebook "1-Cross-Domain-Data-preprocessing _ K-Means _ PCA.ipynb"
```

## Repository Structure

```text
sig720-machine-learning-course-projects/
│
├── Datasets/                # Project datasets (CSV, XLSX)
│   ├── 1(a) microclimate-sensors-data.csv
│   ├── 1(b) ObesityDataSet_raw_and_data_sinthetic.csv
│   └── ... (and others)
│
├── 1-Cross-Domain-Data-preprocessing _ K-Means _ PCA.ipynb
├── 2-Logistic-Regression-&-SVM-Comparative-Analysis.ipynb
├── 3-MNIST-MLP-Double-Descent-Analysis.ipynb
├── 4-Liver-cirrhosis-survival-prediction.ipynb
├── 5-Real-Estate-Price-Prediction.ipynb
├── 6-Drug-Induced-Autoimmunity-Prediction.ipynb
│
├── LICENSE                  # MIT License
└── README.md                # Project documentation
```



## 👨‍💻 Author
 **Nabankur Ray** 
 
 Passionate about real-world data-driven solutions
 
 [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?style=flat&logo=github)](https://github.com/nabankur14) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/nabankur-ray-876582181/) 
 
![GitHub Stats](https://github-readme-stats-eight-theta.vercel.app/api?username=nabankur14&show_icons=true)

⭐ If you like this project

Give it a ⭐ on GitHub — it helps a lot!