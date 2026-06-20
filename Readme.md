# Breast Cancer Classification using Machine Learning

# Project Overview

This project is my first end-to-end Machine Learning project. The objective is to build a classification model that predicts whether a breast tumor is **Malignant** or **Benign** using the Breast Cancer Wisconsin dataset available in Scikit-learn.

Through this project, I learned the complete machine learning workflow, including data exploration, preprocessing, model training, evaluation, and building a prediction system.

---

#  Dataset

 **Dataset:** Breast Cancer Wisconsin Dataset
 **Source:** Scikit-learn (`sklearn.datasets.load_breast_cancer()`)
 **Number of Samples:** 569
 **Number of Features:** 30
 **Target Classes:**

   Malignant
   Benign

---

# Technologies Used

 Python
 NumPy
 Pandas
 Scikit-learn
 Jupyter Notebook

---

# Project Workflow

1. Imported the required libraries.
2. Loaded the Breast Cancer dataset.
3. Converted the dataset into a Pandas DataFrame.
4. Explored the dataset using:

    `head()`
    `shape`
    `info()`
    `describe()`
    `value_counts()`
5. Separated features (`X`) and target (`y`).
6. Split the dataset into training and testing sets.
7. Trained a Logistic Regression model.
8. Evaluated the model on both training and test data.
9. Built a prediction system for predicting new patient data.

---

# Machine Learning Algorithm

* Logistic Regression

---

# Model Evaluation

The model was evaluated using the accuracy score on both the training and testing datasets to measure its performance.

---

# What I Learned

During this project I learned:

* The complete machine learning workflow.
* Why we split data into training and testing sets.
* How a Logistic Regression model is trained.
* How to evaluate a machine learning model.
* How to make predictions on new data.
* How to reshape input data before prediction.
* Basic data exploration using Pandas.

---

# Future Improvements

In future versions of this project, I plan to:

* Compare Logistic Regression with Decision Tree and Random Forest.
* Add Confusion Matrix and Classification Report.
* Perform feature scaling experiments.
* Visualize the dataset using graphs.
* Tune hyperparameters to improve performance.

---

# Project Structure

```text
Breast_Cancer_Classification/
│
├── breast_cancer_classifi.ipynb
├── README.md
```

---

# Author

Devansh Jain

This project marks the beginning of my Machine Learning journey. More advanced projects involving Decision Trees, Random Forests, Neural Networks, and Deep Learning will be added as I continue learning.
