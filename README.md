# 📧 Email Spam Classifier

![Spam Classifier Banner](images/spam_classifier_banner.png)

A machine learning project to detect and classify email messages as spam or not spam using natural language processing techniques.

---

## 🚀 Features
- Text preprocessing (stopwords removal, stemming)
- TF-IDF vectorization
- Naive Bayes classifier
- Accuracy & performance evaluation

---

## 📊 Demo Screenshot
![Prediction Screenshot](images/prediction_ui.png)

---

## 🛠️ Technologies Used
- Python
- Scikit-learn
- Pandas
- Streamlit (for UI, if applicable)

---

## 🧠 How It Works
1. Preprocess the email text.
2. Vectorize the input using TF-IDF.
3. Predict with trained model.
4. Return label: **Spam** or **Not Spam**.

---

## 📎 Sample Usage
```python
predict_spam("Congratulations! You've won a free iPhone.")
