# 🧠 NLP Text Classification Project

This project implements a **Natural Language Processing (NLP)** pipeline for text classification using **Naive Bayes (MultinomialNB)**.

---

## 🚀 Features

* Text preprocessing (cleaning, punctuation removal)
* Feature extraction using:

  * Bag of Words (CountVectorizer)
  * TF-IDF Vectorizer
* Model training using Multinomial Naive Bayes
* Model evaluation:

  * Accuracy Score
  * Classification Report
  * Confusion Matrix (Heatmap)

---

## 🛠️ Tech Stack

* Python
* Scikit-learn
* Pandas
* NumPy
* Matplotlib / Seaborn

---

## 📂 Project Workflow

```text
Raw Text Data
     ↓
Text Cleaning & Preprocessing
     ↓
Vectorization (BoW / TF-IDF)
     ↓
Model Training (MultinomialNB)
     ↓
Prediction & Evaluation
```

---

## ⚙️ Installation

```bash
git clone https://github.com/shivamparihari-46/NLP.git
cd NLP
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open the `.ipynb` file and execute cells step by step.

---

## 📊 Model Details

* Algorithm: Multinomial Naive Bayes
* Input: Text data converted into numerical vectors
* Output: Predicted class labels

---

## 📈 Evaluation Metrics

* Accuracy Score
* Precision, Recall, F1-score
* Confusion Matrix Visualization

---

## 🔥 Key Learnings

* Machine learning models cannot understand raw text → requires vectorization
* TF-IDF often performs better than Bag of Words
* Proper preprocessing improves model accuracy

---

## 📌 Future Improvements

* Try advanced models (Logistic Regression, SVM)
* Use deep learning (LSTM / Transformers)
* Hyperparameter tuning
* Deploy as a web app

---

## 👨‍💻 Author

**Shivam Parihari**
GitHub: https://github.com/shivamparihari-46

---


