# Wine Quality Classification & Predictive Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)

## 🍷 Project Overview
This repository contains a comprehensive machine learning project focused on predicting the quality of red and white wines based on their chemical properties. The goal was to move beyond simple analysis and build a robust classification system that can distinguish wine quality levels using objective physicochemical data.



## 📝 About the Project
In the wine industry, quality assessment is often subjective. This project explores how well **Machine Learning** can automate this process. 

Key highlights of the workflow include:
* **Data Cleaning:** Handled missing values and removed over **1,000 duplicate rows** to prevent model bias.
* **Feature Engineering:** Encoded categorical wine types and performed feature scaling (Standardization) to normalize numerical ranges.
* **Exploratory Data Analysis (EDA):** Leveraged histograms, scatter plots, and correlation heatmaps to identify which chemical traits (like acidity or alcohol content) influence quality the most.

---

## 🚀 Machine Learning Models
I implemented and compared five distinct algorithms to identify the best-performing model:

1.  **Logistic Regression** (Baseline model)
2.  **K-Nearest Neighbors (KNN)**
3.  **Decision Tree**
4.  **Random Forest** (Ensemble learning)
5.  **Support Vector Machine (SVM)**

### Evaluation Metrics
To ensure the models were reliable and not just "lucky," I evaluated them using:
* **Accuracy & Precision/Recall**
* **Confusion Matrices** (to see where the model misclassified)
* **ROC/AUC Curves**
* **Learning Curves** (to check for overfitting vs. underfitting)



---

## 📂 File Structure
* `Wine Dataset.csv`: The raw dataset containing chemical attributes.
* `LAB_Assignment_Wine.ipynb`: The main Jupyter Notebook with all code, visualizations, and model training.
* `LAB_Assignment.ipynb - Colab.pdf`: A exported PDF version of the analysis for quick documentation review.
* `README.md`: Project documentation.

---

## 🛠️ Installation & Usage
To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/hossain-2002/Wine-Quality-Classification-ML.git](https://github.com/hossain-2002/Wine-Quality-Classification-ML.git)
