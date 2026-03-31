#  Sentiment Analysis Web App

##  Project Overview

This project is a **Sentiment Analysis System** that classifies text input as **Positive** ,**Neutral** or **Negative**.
It uses Natural Language Processing (NLP) techniques and a Machine Learning model, deployed via an API and integrated with a frontend for real-time predictions.

---

##  How It Works

1. **Text Preprocessing**

   * Lowercasing
   * Tokenization
   * Stopword removal

2. **Feature Extraction**

   * Converted text into numerical form using **TF-IDF Vectorization**
   * Captures importance of words in the dataset

3. **Model Training**

   * Used **Random Forest Classifier**
   * Applied **GridSearchCV** for hyperparameter tuning

4. **Model Evaluation**

   * Accuracy
   * Precision
   * Recall
   * F1 Score

---

##  Tech Stack

* **Python**
* **Scikit-learn**
* **NLTK**
* **Pickle (Model Serialization)**



---

##  Key Highlights

* End-to-end NLP pipeline
* Hyperparameter tuning using GridSearchCV
* Real-time prediction


---

##  Future Improvements

* Use Logistic Regression / SVM for better NLP performance
* Add model accuracy improvements
* Deploy on cloud (AWS / Render)
* Enhance UI/UX

---

##  Author

**Parth Sethi**

---
