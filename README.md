# 🤖 The ML Grind: Hands-On Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![Status](https://img.shields.io/badge/Status-Active%20Development-green?style=for-the-badge)

> *"Learning Machine Learning is not about memorizing syntax. It's about understanding the math behind the magic."*

## 🚀 About The Repo

Welcome to my code garden! 🌱

This repository is where I document my implementation of concepts from the **Hands-On Machine Learning** book. I am building these models from the ground up to understand not just *how* to use the libraries, but *why* they work.

Currently, I have implemented foundational models for **Regression** and **Classification**, solving real-world data problems.

---

## 📂 Current Builds

Here is what is currently live in the repo. I've broken down the problem statements and the tech used.

| Project | Type | The Mission | Key Tech Stack | Status |
| :--- | :--- | :--- | :--- | :---: |
| **01. Housing Price Predictor** | Regression | Predict district housing prices based on median income, location, and population density. | `LinearRegression`, `Pipelines`, `OneHotEncoder`, `RMSE` | ✅ |
| **02. Binary Classifier** | Classification | Distinguish between classes (e.g., "5" vs "Not 5" in MNIST) with high precision. | `SGDClassifier`, `Cross-Validation`, `Confusion Matrix`, `ROC Curves` | ✅ |

### 🔍 Deep Dive: What I Learned

#### 1. Linear Regression (The Foundation)
It wasn't just about `model.fit()`. The real challenge was data preprocessing.
* **Learnings:** Handling missing data with Imputers, feature scaling (Standardization vs Normalization), and building transformation pipelines.
* **Result:** Achieved a baseline RMSE that I am now working to improve with ensemble methods.

#### 2. Classification (The Decision Maker)
Moved from predicting values to predicting categories.
* **Learnings:** Accuracy is a lie! I learned why we need **Precision, Recall, and F1 Scores**—especially for skewed datasets.
* **Visuals:** heavily utilized `Matplotlib` to plot Precision-Recall trade-offs.

---

## 🔮 Upcoming Modules

I am currently studying and coding the following algorithms. Watch this space!

* [ ] **Support Vector Machines (SVM):** Understanding Kernels and Margins.
* [ ] **Decision Trees:** Visualizing splits and Gini impurity.
* [ ] **Random Forests:** The power of Ensemble learning.

---

## 🛠️ How to Run This

Want to test the models yourself?

1.  **Clone the repo:**
    ```bash
    git clone [https://github.com/yourusername/ml-journey.git](https://github.com/yourusername/ml-journey.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy scikit-learn matplotlib jupyter
    ```
3.  **Fire up the notebook:**
    ```bash
    jupyter notebook
    ```

---

## 📬 Let's Connect!

I am an aspiring ML Engineer always looking for feedback on my code or a good chat about the latest in AI.

* **LinkedIn:** [LinkedIn Profile](linkedin.com/in/harsh-prajapati-393759296)


---

<p align="center">
  <i>Built with 💻 and ☕ by Harsh Prajapati</i>
</p>

