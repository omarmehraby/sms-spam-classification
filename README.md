# 📩 SMS Spam Classification using Machine Learning

## 📌 Overview

This project aims to classify SMS messages as **spam or ham (legitimate)** using machine learning techniques.

Spam detection is widely used in messaging systems to protect users from unwanted or malicious content.

---

## 🧠 Methodology

The project follows a typical NLP pipeline:

* **Text preprocessing**

  * Lowercasing
  * Removing punctuation
  * Tokenization
  * Stopword removal

* **Feature extraction**

  * Bag of Words / TF-IDF

* **Model training**

  * Training machine learning classifiers on labeled SMS data

---

## 🤖 Models Used

* Naive Bayes
* Logistic Regression
  *(add others if you used them)*

---

## 📊 Evaluation Metrics

* Accuracy
* Precision
* Recall
* Confusion Matrix

---

## 🧪 Key Insight

The model successfully distinguishes between spam and legitimate messages by learning patterns in word usage and message structure.

---

## 🛠️ Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK (if used)
* Jupyter Notebook

---

## ▶️ How to Run

```bash
git clone https://github.com/omarmehraby/sms-spam-classification.git
cd sms-spam-classification
pip install -r requirements.txt
jupyter notebook
```

---

## 🚀 Future Improvements

* Deploy as a web app (Streamlit)
* Use deep learning models (LSTM, BERT)
* Real-time spam filtering

---

## 👨‍💻 Author

**Omar Mehraby**
