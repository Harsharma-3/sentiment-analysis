# 📊 Sentiment Analysis using Machine Learning

## 🚀 Overview
This project is an end-to-end **Sentiment Analysis system** built using **Natural Language Processing (NLP)** and **Machine Learning** techniques.

It analyzes textual data (social media posts/tweets) and classifies sentiments into different categories such as positive, negative, or neutral.

---

## 🎯 Features

- 🔹 Data Cleaning & Text Preprocessing
- 🔹 Exploratory Data Analysis (EDA)
- 🔹 Word Frequency Analysis
- 🔹 WordCloud Visualization
- 🔹 TF-IDF Feature Extraction
- 🔹 Multiple ML Models Comparison
- 🔹 Best Model Selection
- 🔹 Model Saving using Joblib
- 🔹 Real-time Sentiment Prediction

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries Used:**
  - pandas, numpy
  - matplotlib, seaborn
  - nltk
  - scikit-learn
  - wordcloud
  - joblib

---

## 📂 Project Structure
sentiment-analysis/
│
├── sentimentdataset.csv
├── notebook.ipynb
├── best_sentiment_model.pkl
├── tfidf_vectorizer.pkl
├── cleaned_sentiment_dataset.csv
├── README.md
└── requirements.txt

---



## 📊 Workflow

1. **Data Loading**
2. **Data Cleaning**
   - Remove URLs, mentions, hashtags
   - Remove stopwords
3. **Exploratory Data Analysis**
   - Sentiment distribution
   - Platform-wise and country-wise analysis
4. **Text Processing**
   - TF-IDF Vectorization
5. **Model Training**
   - Logistic Regression
   - Naive Bayes
   - Linear SVM
   - Random Forest
6. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
7. **Model Saving**
8. **Prediction System**

---

## 📈 Model Performance

| Model | Accuracy |
|------|--------|
| Logistic Regression | ⭐ Best |
| Naive Bayes | Good |
| Linear SVM | Competitive |
| Random Forest | Moderate |

> Best model is automatically selected based on accuracy.

---

## 📊 Visualizations

- Sentiment Distribution
- Platform-wise Analysis
- Country-wise Analysis
- Likes vs Retweets Scatter Plot
- WordClouds for Top Sentiments

---

## 🔧 Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/Harsharma-3/sentiment-analysis.git
cd sentiment-analysis
