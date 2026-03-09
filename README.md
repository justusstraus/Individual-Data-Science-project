# Explainable AI in the Finance Sector

This project investigates how **Explainable AI (XAI)** techniques can improve transparency and interpretability in machine-learning models used in the financial sector.

The notebook demonstrates how explanation methods such as **SHAP** and **LIME** can be applied to understand model predictions in financial classification tasks.

**Course:** Data Science for Engineers
**Student:** J.V.D. Straus
**Student Number:** S2636662
**Date:** 23 January 2026

---

# Project Overview

Machine-learning models are widely used in finance for tasks such as:

* credit risk assessment
* fraud detection
* anti-money-laundering monitoring

However, complex models often behave as **black boxes**. This project explores how explainability techniques can help interpret these models and provide insights into their decision-making process.

---

# Methods

The notebook implements two machine-learning workflows on separate datasets.

For each dataset:

1. Data preprocessing
2. Handling class imbalance
3. Model training
4. Model evaluation
5. Model explanation using XAI methods

Models used include **tree-based classifiers** such as gradient boosting.

---

# Explainability Techniques

### SHAP (SHapley Additive Explanations)

* Global feature importance
* Local prediction explanations
* Model behaviour visualization

### LIME (Local Interpretable Model-Agnostic Explanations)

* Local explanations for individual predictions
* Interpretable approximation of complex models

---

# Installation

Python **3.12** was used.

Install dependencies:

```
pip install numpy pandas scikit-learn xgboost lightgbm catboost shap lime matplotlib seaborn scipy imbalanced-learn kagglehub
```

---

# Running the Notebook

Clone the repository:

```
git clone <repository-url>
```

Open the notebook:

```
jupyter notebook DataScienceIndividualNotebook_JVDStraus_S2636662_23012026.ipynb
```

Datasets are automatically downloaded from **Kaggle** using `kagglehub`.

---

# Repository Structure

```
.
├── DataScienceIndividualNotebook_JVDStraus_S2636662_23012026.ipynb
├── README.md
└── requirements.txt
```

---

# Key Takeaways

* Explainable AI methods provide insights into complex financial models.
* **SHAP** offers robust global and local interpretability.
* **LIME** provides intuitive local explanations but may be less stable.
* XAI techniques improve **trust and transparency** in financial machine-learning systems.
