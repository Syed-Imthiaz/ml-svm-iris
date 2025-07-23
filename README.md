# 🌸 SVM Classifier on Iris Dataset

This project implements a **Support Vector Machine (SVM)** classifier using Scikit-learn to classify species in the **Iris flower dataset**.

---

## 🔍 About the Dataset

The Iris dataset consists of **150 samples** of iris flowers from three different species (*Setosa, Versicolor, Virginica*) with 4 features:
- Sepal length
- Sepal width
- Petal length
- Petal width

---

## 🧠 ML Model: SVM (Support Vector Machine)

This project:
- Uses a **linear kernel** SVM for multi-class classification
- Applies **feature scaling** with `StandardScaler`
- Evaluates model performance using a **confusion matrix** and **classification report**

---

## ⚙️ Tech Stack
- Python
- Scikit-learn
- NumPy

---

## 📈 Model Evaluation (Sample Output)

Confusion Matrix:
[[19  0  0]
 [ 0 12  1]
 [ 0  0 13]]

Classification Report:
              precision    recall  f1-score   support

           0       1.00      1.00      1.00        19
           1       1.00      0.92      0.96        13
           2       0.93      1.00      0.96        13

    accuracy                           0.98        45
   macro avg                 0.98             0.97            0.97              45
   
weighted avg                 0.98             0.98            0.98              45

✅ **Accuracy: 98%** on test data!

---

## 🚫 License & Disclaimer

This project is protected under **"All Rights Reserved"**.  
No part of this code may be copied, reused, or modified without explicit written permission from the author.

For inquiries: syedimthiaz2006@gmail.com

---
