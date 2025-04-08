# 🐧 Penguin Classifier 

## 📌 Overview
This project focuses on classifying penguin species using physical attributes such as beak length, depth, flipper length, and body mass. Leveraging a **Decision Tree Classifier**, the model aims to assist researchers and wildlife enthusiasts in accurately identifying **Adelie**, **Chinstrap**, and **Gentoo** penguins.

---

## 📊 Dataset
The dataset consists of penguin observations with the following features:
- **Species** (Target Variable)
- **Island**
- **Culmen Length (mm)**
- **Culmen Depth (mm)**
- **Flipper Length (mm)**
- **Body Mass (g)**
- **Sex**

---

## 🔍 Objective
To build a robust classification model that predicts a penguin's species based on its physical characteristics. This can aid in biological research, population tracking, and conservation strategies.

---

## 🧠 Model & Evaluation

### ✅ Model Used:
- **DecisionTreeClassifier** (from `sklearn.tree`)
- Hyperparameter tuning with `GridSearchCV`

### 🔧 Best Parameters:
python
{'criterion': 'entropy', 'max_depth': 4}


📈 Performance:
Metric	Score
Train Accuracy	1.000
Test Accuracy	0.971
Cross-Val Score	0.964
📊 Confusion Matrix:

Adelie: 30 correctly classified

Chinstrap: 16 correctly classified

Gentoo: 21 correctly classified

🧰 Tech Stack
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

📌 Conclusion
The decision tree model demonstrated excellent performance with 97.1% accuracy on the test set, proving to be a reliable tool for penguin species classification based on physical features.
