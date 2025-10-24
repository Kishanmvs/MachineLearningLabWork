# MachineLearningLabWork
**Lab 1**

**Wine Quality Classification (K-Fold Testing)**

*📂 Dataset*

Red Wine Quality dataset (winequality-red.csv) - 1599 samples, 11 features

Binary target: Good (≥7) vs. Not Good (<7)

*⚙️ Method*

Algorithm: Logistic Regression

Validation: Stratified 5-Fold Cross-Validation

*📊 Results*

Fold Accuracies: [0.875, 0.881, 0.900, 0.856, 0.893]

Mean Accuracy: 0.88

Std Dev: 0.015

*📝 Insight*

Model performs well overall.

Imbalance → lower recall for “Good” wine


**Lab 2**

**Spam Email Classification — Gaussian Naive Bayes**

*📂 Dataset*

UCI Spambase Dataset

Rows: 4601 emails

Features: 57

Target:

  * `1` → Spam
  * `0` → Not Spam

*⚙️ Method*

Approach: Gaussian Naive Bayes

Split: 70% Training / 30% Testing

Metrics: Accuracy + Confusion Matrix

Implementation: From-scratch Bayes + scikit-learn baseline comparison

*📊 Results*

Accuracy: ~0.88

Confusion Matrix:

  ```
  [[ 625  179] 
   [  38 539]]
  ```
Spam Count: 1813

Non-Spam Count: 2788


📝 Insight

Good baseline performance with simple Gaussian NB

Some false positives → misclassification of legitimate emails as spam

Could improve with feature scaling, text preprocessing, or TF-IDF & Multinomial/Bernoulli NB models




