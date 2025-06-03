#  Income Prediction using Machine Learning

This project focuses on predicting whether a person earns more than $50,000 per year based on demographic data. It uses several classification models and evaluates their performance using accuracy and F1-score.

---

##  Project Files

- `Income Prediction.ipynb`: Jupyter notebook with data preprocessing, model training, and evaluation
- `SUMMARY REPORT.pdf`: Summary of steps taken, results, and insights

---

##  Machine Learning Models Used

The following classification algorithms were implemented and compared:

- **Naive Bayes**
- **k-Nearest Neighbors (k-NN)**
- **Decision Tree**
- **Random Forest**

The models were evaluated based on accuracy and F1-score.

---

##  Data Preprocessing

- Checked for and handled missing values
- Encoded categorical variables using LabelEncoder
- Scaled numerical features using StandardScaler
- Split dataset into training and testing sets (80% train, 20% test)

---

##  Results Summary

| Model          | Accuracy | F1 Score |
|----------------|----------|----------|
| Naive Bayes    | ~0.799   | ~0.434   |
| k-NN           | ~0.787   | ~0.397   |
| Decision Tree  | ~0.859   | ~0.672   |
| Random Forest  | ~0.866   | ~0.687   |

Random Forest performed best overall.

---

##  How to Run the Notebook

1. Open `Machine Learning Assignment.ipynb` using Jupyter Notebook or VS Code
2. Make sure you have the following libraries installed:
   - `pandas`, `numpy`, `scikit-learn`
3. Run all the cells in order

---

##  About the Project

This assignment was part of a machine learning unit focused on classification problems. It demonstrates data cleaning, encoding, training different models, and comparing their results.

