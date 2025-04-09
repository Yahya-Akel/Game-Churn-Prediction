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
3. **Label Encoding of Categorical Features and Target**
4. **Train-Test Split with Stratification**
5. **Class Imbalance Handling using SMOTE**
6. **Model Training using XGBoost**
7. **Model Evaluation**  
   - Accuracy  
   - Precision, Recall, F1-Score  
   - Confusion Matrix
8. **Hyperparameter Tuning** using RandomizedSearchCV
9. **Feature Importance Visualization**

---

## 📈 Model Performance

- Multiple performance metrics (before and after tuning) were used to evaluate the model.
- SMOTE significantly improved performance on underrepresented classes.
- The final XGBoost model demonstrated strong generalization with balanced accuracy across classes.

---

## 💻 Run the Notebook

To run this project in Google Colab:

🔗 [Open Notebook in Colab](https://colab.research.google.com/drive/1uu1niunRRD7SEQUflz6Bon-B73ehhVD4?usp=sharing)

---

## 📄 License

This project is for educational purposes as part of **CMPS 261 – Spring 2025**. All rights reserved to the authors.
