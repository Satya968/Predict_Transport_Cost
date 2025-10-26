# Transport Cost Prediction (ML Assignment)

This repository contains a machine learning project that predicts **transport cost** based on shipment and delivery features. The main goal is to build and evaluate regression models that can estimate the cost accurately.

---

##  Repository Structure

| File / Folder | Description |
|----------------|-------------|
| **Model_training.ipynb** | Jupyter Notebook containing data preprocessing, model training, and evaluation. |
| **ML_A1_Report.pdf** | Final report summarizing the project, methods, and results. |
| **Predictions/** | Folder for storing model predictions or output files. |
| **.gitignore** | Specifies files and folders ignored by Git. |
| **README.md** | Project documentation (this file). |

---

##  Project Overview

- **Goal:** Predict transport cost using regression models.  
- **Approach:** Clean the dataset, handle missing values, transform features, and apply multiple regression algorithms.  
- **9 Total models have been tested and evaluated:** Adaboost, Decision Trees, Random Forest, Gradient Boosting, Linear Regression, Elastic net, Bayesian Ridge, Lasso Regression, K-nearest neighbours.  
- **Evaluation Metrics:** R² score and RMSE.

---

##  Tools and Libraries

- Python  
- Pandas, NumPy, Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook

---

##  How to Run

1. Open `Model_training.ipynb` in Jupyter Notebook.  
2. Run all cells step-by-step to train and evaluate models.
3. According to the model u want to test, comment/uncomment the model and definition and its parameters in the jupyter code.
4. Generated predictions will be saved as "submission.csv" (Rename it as you like). 

---

##  Author

**Satyaram Mangena**  
For academic submission — Machine Learning Assignment 1.
