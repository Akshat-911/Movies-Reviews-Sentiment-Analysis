# Movies-Reviews-Sentiment-Analysis
# Sentiment Analysis of Restaurant Reviews

This project performs sentiment analysis on restaurant reviews using Natural Language Processing (NLP) techniques and a Naive Bayes classifier.

It demonstrates how to:
- Clean and preprocess textual data
- Build a Bag-of-Words model
- Train a machine learning classifier
- Predict sentiments (positive or negative)

---

## 📂 Dataset

- **File:** `Restaurant_Reviews.tsv`
- **Source:** [Machine Learning A-Z™: Hands-On Python & R In Data Science](https://www.udemy.com/course/machinelearning/)
- Contains 1000 restaurant reviews labeled as:
  - **1** → Positive review
  - **0** → Negative review

---

## 💻 Libraries Used

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- NLTK
- scikit-learn

---

## ⚙️ How It Works

### 1. Data Preprocessing

- Remove all non-letter characters from the reviews
- Convert text to lowercase
- Remove stop words (e.g. “the”, “is”)
- Apply stemming to reduce words to their root form
- Build a **Bag-of-Words model** using `CountVectorizer`

### 2. Feature Extraction

- Convert the cleaned reviews into numeric feature vectors
- Limit to the **top 1500 features**

### 3. Model Training

- Split data into training and test sets (80%/20%)
- Train a **Naive Bayes classifier**

### 4. Model Evaluation

- Predict sentiments for the test set
- Evaluate using a confusion matrix

---
