# 🏥 Heart Disease Prediction - Healthcare AI

## 📊 Project Overview
A machine learning system that predicts heart disease risk from clinical data. This project demonstrates responsible AI development with focus on medical interpretability and ethical considerations.

## 🎯 Key Results
- **82% accuracy** in heart disease prediction
- **3% improvement** through medical feature engineering
- **Gender bias detected**: Male patients: 79.0% accuracy & Female patients: 90.3% accuracy
- **1025 patients** analyzed with 14 clinical features each

## ⚠️ Important Note for Reviewers
**For optimal experience:** Ensure the `heart.csv` file is in the `data/` folder when running the notebook. The analysis uses fallback sample data if the file is missing, but the complete medical insights and 82% accuracy are demonstrated with the full dataset


## 🚀 Quick Start
```bash
git clone https://github.com/Mehak-NazDev/health-risk-screener
cd health-risk-screener
pip install -r requirements.txt
jupyter notebook notebooks/heart_disease_complete_analysis.ipynb
```

## 📁 Project Structure
```
health-risk-screener/
├── notebooks/
│   └── heart_disease_complete_analysis.ipynb
├── data/
│   └── heart.csv
├── assets/
│   └── medical_insights.png
├── requirements.txt
└── README.md
```

##  Medical Insights
- **Chest pain** is the strongest predictor of heart disease
- **Higher max heart rates** found in sick patients (158.6 vs 139.1 bpm)
- **Age categories** and **BP staging** improved model performance
- **Clinical risk scores** (0-4 scale) are highly effective

##  Ethical AI
- Proactively detected and documented gender bias
- Emphasis on model interpretability for clinical use
- Research tool designation - not for diagnostic use
- Continuous bias monitoring recommended

## 🛠 Technical Details
- **Algorithm**: Logistic Regression (interpretable)
- **Feature Engineering**: Age categories, BP stages, risk scores
- **Validation**: 80-20 train-test split
- **Dependencies**: pandas, scikit-learn, matplotlib, seaborn

---

*Building responsible AI for better healthcare outcomes*  
*Project Status: Complete*
