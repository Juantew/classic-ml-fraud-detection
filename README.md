# classic-ml-fraud-detection
# 🛡️ Credit Card Fraud Detection — Machine Learning Project

A complete end-to-end machine learning workflow for detecting fraudulent credit
card transactions using Logistic Regression and XGBoost. This project demonstrates
data preprocessing, feature engineering, imbalanced classification techniques, model
evaluation, threshold tuning, and model comparison — all critical skills for an
entry-level Machine Learning Engineer.

---

## 📂 Project Structure
├── data/
│ ├── raw/
│ └── processed/
├── notebooks/
│ ├── 01_exploration.ipynb
│ └── 02_modeling.ipynb
├── models/
│ └── (optional saved models)
├── requirements.txt
└── README.md


---

## 🚀 Features

- End-to-end ML pipeline  
- Feature engineering (log-transformation)  
- Class imbalance handling  
- Train/test stratified split  
- Baseline model: Logistic Regression  
- Advanced model: XGBoost  
- ROC & PR curves  
- Confusion matrices  
- Threshold tuning  
- Full markdown explanations  
- Business context for fraud detection  
- Professional structure suitable for portfolio use  

---

## 📊 Model Performance

| Metric | Logistic Regression | XGBoost |
|--------|----------------------|---------|
| ROC AUC | ~0.96 | 0.9824 |
| PR AUC | ~0.60 | 0.8764 |
| Recall (Fraud) | Lower | Higher |
| Precision (Fraud) | Lower | Higher |
| F1 (Fraud) | Lower | Higher |

XGBoost clearly outperforms Logistic Regression across all fraud-centric metrics.

---

## 🔍 Evaluation Highlights

- **PR AUC is the most important metric** due to class imbalance  
- **XGBoost detects more fraud with fewer false negatives**  
- **Threshold tuning** demonstrates real-world decision boundaries  
- **Confusion matrices** show each model’s strengths and weaknesses  
- **ROC comparison** shows improved class separation by XGBoost  

---

## 🧭 Next Steps

- Hyperparameter tuning  
- Additional models (LightGBM, CatBoost, Autoencoders)  
- Cost-based evaluation  
- Real-time prediction API  
- Deployment via AWS SageMaker or FastAPI  
- Monitoring for data drift  

---

## 📁 How to Run

1. Clone this repo  
2. Create a virtual environment  
3. Install dependencies:  
   ```bash
   pip install -r requirements.txt
4. Run the notebooks in order:
   - `notebooks/01_exploration.ipynb`
   - `notebooks/02_modeling.ipynb`

5. Make sure the following directories exist:
    data/raw/
    data/processed/

6. Place `creditcard.csv` inside the directory:

   data/raw/

   ---

## 🏁 Conclusion

This project demonstrates the full lifecycle of a fraud detection machine learning
pipeline, including data preprocessing, modeling, evaluation, and threshold tuning.
It is designed as a professional, beginner-friendly portfolio project showcasing
strong understanding of imbalanced classification and real-world ML considerations.


    