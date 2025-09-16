# 🌱 Habit Prediction Project  

[![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)](https://www.python.org/)  
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)  
[![scikit-learn](https://img.shields.io/badge/ML-scikit--learn-green?logo=scikit-learn)](https://scikit-learn.org/stable/)  
[![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)]()  

Can machine learning predict if someone will **stick with a habit** or drop it?  
This project explores that question by modeling streaks, timing, and personal history to forecast behavior.  

---

## 📂 Project Files  

- 📘 **`habbit_prediction.ipynb`** → Code for preprocessing, modeling, and evaluation  
- 📊 **`habbit_data_1500.xlsx`** → Synthetic dataset of user habits   

---

## 📊 Dataset  

> Since real-world data is scarce, we built a **synthetic yet realistic dataset** representing a virtual community of users.

**Features simulated:**  
- 🟢 **Streak Length** → Consecutive days a habit was followed  
- ⏰ **Day of Week & Time of Day** → Contextual factors  
- 📈 **Past Success Rate** → Consistency history  
- 🏃 **Habit Category** → Exercise, study, health  
- 👥 **Age Group** → Teen, Adult, Senior  

**Target:**  
- `1` → Continued habit  
- `0` → Dropped habit  

---

## 🔎 Workflow  

<details>
<summary>📌 Click to expand</summary>

1. **EDA** → Missing values, distributions, correlations  
2. **Preprocessing** → One-hot encoding, scaling, 80/20 split  
3. **Modeling** → Logistic Regression (baseline)  
4. **Evaluation** → Accuracy, Precision, Recall, F1, Specificity  
5. **Visualization** → Confusion matrix heatmaps, metric bar charts  

</details>  

---

## 📈 Results  

- ✅ Initial accuracy: **~92.3%**  
- 🔑 Key insights:  
  - Longer streaks = higher continuation  
  - Time of day influences success  
  - Some habit types are easier to maintain  

---

## 🚀 Future Work  

- Add weekend patterns & consistency scores  
- Test advanced models: Decision Trees, Random Forests  
- Hyperparameter tuning for stronger accuracy  
- Real-world integrations:  
  - Fitness apps 🏋️  
  - Study platforms 📚  
  - Health apps 🥗  

---

## 🛠️ Tech Stack  

- **Python** → pandas, numpy, scikit-learn, matplotlib, seaborn  
- **Jupyter Notebook/Google Collab** → experimentation  
- **Excel/CSV** → dataset management  

---

## 📌 Summary  

This is the **Day 1 foundation**:  
A working ML pipeline with valuable insights into habit continuation.  
Next steps: boost accuracy and build real-world applications.  

---
