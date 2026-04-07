Machine Learning Experiments: Logistic Regression, Perceptron, and SVM
## Overview

This project implements several fundamental machine learning algorithms and experiments using Python:

1. **Logistic Regression Optimization**

   * Implemented using a custom **random coordinate descent** algorithm.
   * Compared against the optimal logistic regression solution from scikit-learn.

2. **Perceptron Algorithm**

   * Implemented from scratch.
   * Trained on a binary subset of the Iris dataset.
   * Visualizes the learned decision boundary.
   * Measures convergence behavior via number of updates.

3. **Support Vector Machine (SVM)**

   * Linear SVM trained on Iris dataset classes.
   * Examines effect of regularization parameter **C**.
   * Reports training error and number of support vectors.
   * Visualizes the learned decision boundary.

---

Features include:

* age
* sex
* chest pain type (cp)
* resting blood pressure (trestbps)
* cholesterol
* fasting blood sugar
* resting ECG
* maximum heart rate (thalach)
* exercise induced angina
* oldpeak
* slope
* ca
* thal

Target variable:

```
target = 1 → heart disease present
target = 0 → no heart disease
```

---

# Files in Repository

```
heart.csv
heart.ipynb
README.md
```

---

# Author

Kishan Patel
UC San Diego
