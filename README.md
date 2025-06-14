
# 📧 Spam Email Detection using Machine Learning

This project is a simple implementation of a **spam detector** using machine learning. It classifies text messages as either **spam** or **not spam (ham)** using Natural Language Processing (NLP) and scikit-learn.

---

## 🔍 Project Overview

- ✅ Load and clean SMS spam data
- 🧠 Use **TF-IDF Vectorizer** to convert text to numerical features
- 🧪 Train a machine learning model (**Multinomial Naive Bayes** or similar)
- 📈 Evaluate with accuracy, classification report, and confusion matrix
- 📊 Visualize model performance using Seaborn heatmap

---

## 🗂️ Dataset

- Source: [Kaggle - SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- File: `spam.csv`
- Columns:
  - `v1`: Label (`ham` or `spam`)
  - `v2`: The actual message text

If you clone this repository, make sure `spam.csv` is in the project folder.
---

## ⚙️ Technologies Used

- Python
- Jupyter Notebook
- pandas, NumPy
- scikit-learn
- Seaborn, Matplotlib
- NLP (TF-IDF Vectorization)

---
📊 Sample Output
Accuracy: 96–98%
Confusion matrix heatmap
Classification report with precision, recall, and F1-score
-----

📌Future Improvements
Try more ML algorithms (Logistic Regression, SVM, etc.)
Use GridSearch for hyperparameter tuning
Build a Streamlit or Flask web app interface
---

