# 📊 Sentiment Analysis of Product Reviews

This project performs **Sentiment Analysis** on product reviews using **Natural Language Processing (NLP)** and **Machine Learning** techniques. It classifies reviews as **positive** or **negative**, helping businesses understand customer feedback better.

---

## 🔍 Objective

To analyze customer reviews and determine the **sentiment polarity** (Positive or Negative) using a machine learning model (Naive Bayes).

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas, NumPy
- Scikit-learn (CountVectorizer, MultinomialNB)
- NLTK (Natural Language Toolkit)
- Google Colab

---

## 📁 Dataset

The dataset contains product reviews along with their sentiments (positive/negative).  
Example format:

| Review                         | Sentiment |
|-------------------------------|-----------|
| "This product is amazing!"    | Positive  |
| "Worst quality I have seen."  | Negative  |

---

## 🔄 Workflow

1. **Data Collection** – Load the dataset (CSV or Excel).
2. **Data Cleaning** – Remove stopwords, lowercase text, remove punctuation.
3. **Feature Extraction** – Convert text into numerical form using CountVectorizer.
4. **Model Training** – Use Naive Bayes classifier to train the model.
5. **Model Testing** – Predict sentiments of test data.
6. **Accuracy Evaluation** – Use accuracy score and confusion matrix.

---

## 📌 How to Run

```bash
# Step 1: Clone the repository
git clone https://github.com/yourusername/sentiment-analysis-product-reviews.git

# Step 2: Navigate to the project folder
cd sentiment-analysis-product-reviews

# Step 3: Install the required libraries

# Step 4: Run the Google colab
  Sentiment_Analysis.ipynb
