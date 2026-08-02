# Module 5 – Data Splitting

## Objective

The aim of this exercise was to explore how different train, validation and test splits affect the performance of a machine learning model.

I compared two different data splitting strategies using the Wine dataset from scikit-learn and trained a Logistic Regression classifier.

---

## Dataset

- Wine dataset (scikit-learn)
- 178 samples
- 13 numerical features
- 3 wine classes

---

## Methods

I compared two different train/validation/test splits:

- 70% / 15% / 15%
- 60% / 20% / 20%

The model was evaluated using:

- Validation accuracy
- Test accuracy
- Classification report (precision, recall and F1-score)

---

## Results

### 70 : 15 : 15

- Validation accuracy: **1.000**
- Test accuracy: **0.963**

### 60 : 20 : 20

- Validation accuracy: **0.944**
- Test accuracy: **0.944**

The larger training set (70%) produced slightly better performance, suggesting that providing more training examples helped the model generalise better.

---

## What I learned

This exercise helped me understand why splitting the data correctly is important.

A validation set allows model selection without using the test data, helping to avoid overfitting. I also observed that changing the amount of training data can have a noticeable impact on model performance.

---

## Files

- `module5_data_splitting.ipynb`
