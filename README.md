<div align="center">

# 🧠 Parkinson's Disease Prediction
### using Machine Learning & Explainable AI

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-Explainable_AI-blueviolet?style=flat)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

> Predicting Parkinson's Disease from biomedical voice features using Random Forest & SVM — with full model transparency via SHAP and LIME.

</div>

---

## 📌 Overview

Parkinson's Disease affects millions worldwide, yet early diagnosis remains challenging. This project builds a machine learning pipeline that predicts Parkinson's Disease from **biomedical voice recordings**, while using **Explainable AI (XAI)** techniques to make predictions interpretable for both developers and medical professionals.

---

## 🎯 Objectives

- Predict Parkinson's Disease from voice-based biomarkers with high accuracy
- Compare performance of **Random Forest** and **SVM** classifiers
- Use **SHAP** and **LIME** to explain model decisions transparently
- Make the pipeline reproducible and accessible for healthcare applications

---

## 🧰 Tech Stack

| Category | Tools |
|---|---|
| Language | Python |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn (Random Forest, SVM) |
| Explainability | SHAP, LIME |
| Visualization | Matplotlib, Seaborn |
| Environment | Jupyter Notebook, VS Code |

---

## 🧪 Methodology

```
Voice Data → Preprocessing → Model Training → Evaluation → XAI Explanation
```

### 1. 📂 Data Preprocessing
- Feature normalization & scaling
- Exploratory Data Analysis (EDA)
- Train-test split with stratification

### 2. 🤖 Model Training
- **Random Forest Classifier** — ensemble-based, robust to noise
- **Support Vector Machine (SVM)** — with hyperparameter tuning via GridSearchCV

### 3. 📊 Model Evaluation
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix
- ROC-AUC Curve

### 4. 🔍 Explainability (XAI)
- **SHAP** — global & instance-level feature importance
- **LIME** — local prediction interpretation for individual patients

---

## 📈 Results

| Metric | Random Forest | SVM |
|---|---|---|
| Accuracy | ✅ High | ✅ Competitive |
| Interpretability | SHAP + LIME | SHAP + LIME |
| Key Insight | Voice biomarkers (MDVP:Fo, HNR) were most predictive |

- SHAP visualizations highlighted the **most influential voice biomarkers** driving predictions
- LIME confirmed **model stability** across diverse patient samples
- Random Forest outperformed SVM on overall predictive performance

---

## 🔍 Why Explainable AI?

In healthcare, a model that says *"this patient has Parkinson's"* isn't enough — clinicians need to know **why**.

- **SHAP** quantifies each feature's contribution to every prediction (globally and locally)
- **LIME** approximates the model locally to explain individual patient predictions
- Together, they bridge the gap between black-box ML and clinical trust

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/vanshiiii11/parkinsons-disease-prediction-voice-xai.git
cd parkinsons-disease-prediction-voice-xai

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch the notebook
jupyter notebook Parkinson_Disease_Prediction.ipynb
```

---

## 📁 Project Structure

```
📦 parkinsons-disease-prediction-voice-xai
 ┣ 📓 Parkinson_Disease_Prediction.ipynb   # Main notebook
 ┣ 📄 requirements.txt                     # Dependencies
 ┣ 📂 data/                                # Dataset files
 ┣ 📂 outputs/                             # Plots & results
 ┗ 📄 README.md
```

---

## 🙏 Acknowledgements

This project was originally developed in collaboration with [Soham Saoji](https://github.com/SohamSaoji). The version in this repository is a **refined and independently documented** version showcasing my learning outcomes in machine learning and XAI.

Special thanks to the open-source creators of [SHAP](https://github.com/slundberg/shap) and [LIME](https://github.com/marcotcr/lime) — whose tools make interpretable AI in healthcare possible.

---

## 👤 Author

**Vanshika Motwani**

[![GitHub](https://img.shields.io/badge/GitHub-vanshiiii11-181717?style=flat&logo=github&logoColor=white)](https://github.com/vanshiiii11)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vanshika_Motwani-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vanshika-motwani-2834b632b)

---

<div align="center">
  <em>"Still learning. Always building. Never stopping."</em>
</div>
