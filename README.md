# Movie-review-analysis
![output](https://github.com/user-attachments/assets/82416eba-dbe3-4561-8582-fd987efebe28)
![output negative](https://github.com/user-attachments/assets/48711213-cda1-4067-9721-be9917719edc)

## Wordcloud of positive reviews:

![output +ve wordcloud](https://github.com/user-attachments/assets/519117bb-ef9d-4d20-b47e-c61123c65598)

## Wordcloud of negative reviews:

![output -ve wordcloud](https://github.com/user-attachments/assets/10ab552a-4bb0-46b8-a761-b75e39f1d901)


![Screenshot 2025-02-18 165436](https://github.com/user-attachments/assets/d6f0d268-dfed-45b1-872e-4aee0587715b)

![confusion matrix](https://github.com/user-attachments/assets/6e9097b4-ca6a-4440-829a-d5526a297a77)

## Model accuracy:

![Screenshot 2025-02-18 165453](https://github.com/user-attachments/assets/0900a9d8-b5f2-471b-98b2-aad73b57dcca)

## Predict review:

![Screenshot 2025-02-18 165418](https://github.com/user-attachments/assets/5d986eb7-dce8-425c-bcf1-c0f8c43b1ce6)


---

## 🎬 Movie Review Sentiment Analysis

### 📌 Overview

This project implements a **Movie Review Sentiment Analysis** pipeline that uses **natural language processing (NLP)** and **machine learning** to classify movie reviews as either **positive** or **negative**. It aims to explore how text preprocessing and different models affect sentiment classification accuracy.

---

## 🧠 What I Did

* Collected and cleaned a dataset of movie reviews.
* Performed **text preprocessing** using NLTK (tokenization, stopword removal, lemmatization).
* Transformed text data into numerical format using **TF-IDF vectorization**.
* Trained and evaluated three different classification models:

  * **Logistic Regression**
  * **Random Forest Classifier**
  * **Naive Bayes**
* Compared model performance using **accuracy**, **confusion matrix**, and **classification report**.
* Identified the **best performing model** based on evaluation metrics.

---

## 🏗️ Architecture

1. **Data Loading & Exploration**

   * Load dataset of labeled movie reviews.
   * Inspect review distribution and length.

2. **Text Preprocessing**

   * Lowercasing
   * Tokenization using NLTK
   * Stopword removal
   * Lemmatization
   * Reconstructed cleaned reviews

3. **Feature Extraction**

   * Applied **TF-IDF Vectorizer** to convert text into numerical feature vectors.

4. **Model Training & Evaluation**

   * Split dataset into training and test sets.
   * Trained three models:

     * **Logistic Regression**
     * **Random Forest**
     * **Naive Bayes**
   * Evaluated using:

     * Accuracy Score
     * Confusion Matrix
     * Precision, Recall, F1-Score

---

## 🔍 Key Features & Insights

* **Text Normalization**: Cleaned and lemmatized raw user reviews for improved input quality.
* **TF-IDF Vectorization**: Captured important words without relying on word order.
* **Model Comparison**: Empirically compared classical ML classifiers to choose the most effective one.
* **Accuracy Results**: Logistic Regression and Naive Bayes both showed strong performance, depending on the metric prioritized.

---

## 🛠️ Technologies Used

* Python (Jupyter Notebook)
* NLTK (Natural Language Toolkit)
* Scikit-learn (Logistic Regression, Naive Bayes, Random Forest, TF-IDF)
* Pandas, NumPy, Matplotlib, Seaborn

---



