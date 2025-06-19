# 💳 Credit Card Fraud Detection

A machine learning project to detect fraudulent credit card transactions using supervised learning algorithms and oversampling techniques.

## 📊 Features
- Built with **Random Forest** and **Decision Tree** classifiers
- Applied **SMOTE** to solve class imbalance
- Evaluation using **F1-score**, **precision**, **recall**
- Visualized confusion matrix, feature correlation, and ROC curve
- Used **PCA** and cross-validation for deeper insights
- Model saved with `joblib` for easy reuse

## 📁 Dataset
- [Kaggle Dataset: Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Contains anonymized features (V1–V28), `Time`, `Amount`, and binary `Class` label

## 🧪 Results
- Achieved an **F1-score of 99.98%** using Random Forest + SMOTE
- Cross-validated results show stable performance across folds

## 🔧 Technologies Used
- Python, Scikit-learn, Pandas, Matplotlib, Seaborn
- Imbalanced-learn (SMOTE)
- Google Colab / Jupyter Notebook

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook credit_card_fraud_enhanced.ipynb
```

## 🧠 Author
Ishan Mistri



