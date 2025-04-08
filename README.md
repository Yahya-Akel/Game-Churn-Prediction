# 🎮 Game Churn Prediction using Machine Learning

A CMPS 261 – Machine Learning project that aims to predict player engagement levels in online games using supervised learning techniques. The project focuses on preprocessing, handling class imbalance, and building an interpretable and high-performing model using XGBoost.

---

## 📁 Project Overview

This project predicts the **Engagement Level** of players (e.g., Low, Medium, High) based on their in-game behavior. Identifying churn-prone players allows game developers to take proactive steps to retain users through rewards, promotions, or personalized engagement strategies.

---

## 👨‍💻 Team Members

- Wajed Rashed  
- Yahya Akl  
- Jean Elhowayek

---

## 📊 Dataset

The dataset includes 40,000+ player records with features such as:

- Age, Gender, Location  
- Game Genre and Difficulty  
- Play Time (Hours), Sessions per Week  
- In-Game Purchases, Player Level  
- Achievements Unlocked  
- Target: **Engagement Level** (Low, Medium, High)

🔗 Dataset Source: [Predict Online Gaming Behavior Dataset – Kaggle](https://www.kaggle.com/datasets/rabieelkharoua/predict-online-gaming-behavior-dataset)

---

## 🔧 Tools & Technologies

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Scikit-learn
- XGBoost
- Imbalanced-learn (SMOTE)
- Google Colab

---

## 🧪 Project Pipeline

1. **Data Loading and Exploration**
2. **Visualization of Class Distribution**
3. **One-Hot Encoding of Categorical Features**
4. **Label Encoding for Target Variable**
5. **Train-Test Split with Stratification**
6. **Class Imbalance Handling using SMOTE**
7. **Model Training using XGBoost**
8. **Model Evaluation**  
   - Accuracy  
   - Precision, Recall, F1-Score  
   - Confusion Matrix
9. **Hyperparameter Tuning** using RandomizedSearchCV
10. **Feature Importance Visualization**

---

## 📈 Model Performance

- Multiple performance metrics (pre and post tuning) were used to evaluate the model.
- SMOTE significantly improved minority class recall.
- One-Hot Encoding yielded more interpretable features compared to Label Encoding.

---

## 💻 Run the Notebook

To run this project in Google Colab:

🔗 [Open Notebook in Colab](https://colab.research.google.com/drive/11c7r2ylSnreD39wyTKcnPkyVjf3jDauc?usp=sharing)

---

## 📄 License

This project is for educational purposes as part of **CMPS 261 – Spring 2025**. All rights reserved to the authors.
