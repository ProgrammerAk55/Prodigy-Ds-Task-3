# PRODIGY_DS_03

<p align="center">
  <img src="https://github.com/ProgrammerAk55/Prodigy-Ds-Task-3/blob/main/Task-3.png" alt="Task 1 Banner" width="800" />
</p>

---
## 📊 Decision Tree Classification — Prodigy InfoTech Internship (Task 3)

This repository presents my solution for a real-world client churn prediction problem, completed during my **Data Science Internship at Prodigy InfoTech**. Here, I leverage **Decision Tree Classification** using Python, pandas, scikit-learn, and data visualization tools to transform client banking data into actionable business insight.

---

## ✨ Problem Statement

Given a dataset containing various features about bank clients (demographic and transaction data), **predict whether a client will subscribe to a term deposit** using a Decision Tree Classification model.

---

## 🛠️ Technologies & Libraries

- **Python** (Jupyter Notebook)
- **Pandas** and **NumPy** (data wrangling)
- **scikit-learn** (machine learning and decision tree algorithms)
- **Matplotlib** and **Seaborn** (visualization)

---

## 📂 Dataset Features

The dataset provides both **numerical** and **categorical** columns, including:

- **Numerical:** `age`, `balance`, `duration`, `campaign`, `previous`, etc.
- **Categorical:** `job`, `marital`, `education`, `contact`, `month`, `poutcome`  
- **Target:** `y` — indicates if a client subscribed to a term deposit (`yes`, `no`)
- 📂 [Dataset(https://raw.githubusercontent.com/ProgrammerAk55/Prodigy-Ds-Task-3/refs/heads/main/bank.csv)]
  
---

## 🔑 Approach

- **1. Data Preprocessing**
  - Cleaned and standardized column names
  - Encoded categorical variables for model compatibility
- **2. Model Building**
  - Trained a Decision Tree Classifier (`sklearn.tree.DecisionTreeClassifier`)
  - Tuned max depth for interpretability and generalization
- **3. Evaluation**
  - Assessed model using accuracy, precision, recall, F1 score
  - Analyzed feature importance and model splits
- **4. Visualization**
  - Visualized the tree to understand decision paths and feature splits (see output below)

---

## 🧠 Key Learnings

- Practical encoding and preprocessing of mixed-type tabular data
- How to interpret decisions and importance in tree-based models
- Gained insight into which features most affect banking term deposit subscription (e.g., `duration`, `poutcome`, `month`)

---

## 📊 Results & Output

- **Tree Visualization:**  
  [DT_PLOT(https://github.com/ProgrammerAk55/Prodigy-Ds-Task-3/blob/main/Dt_plot.png)]
- **Sample Performance Metrics:**  
  - Accuracy, precision, recall, F1-score reported in the notebook

---

## 🚀 How to Run

1. Clone this repository
2. Open the notebook in Jupyter or Google Colab
3. Run all cells sequentially to preprocess data, train the classifier, and visualize the results

---

## 🤝 About Me

👋 I’m an aspiring Data Analyst passionate about business intelligence, predictive analytics, and meaningful visualizations.  
Connect with me on [Linkedin(https://www.linkedin.com/in/y-anilkumar/)] for discussion or collaboration!
