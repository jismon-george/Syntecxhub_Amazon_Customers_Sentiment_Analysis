# 🛒 Syntecxhub Amazon Customers Sentiment Analysis

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange.svg)
![NLTK](https://img.shields.io/badge/NLTK-NLP-yellow.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red.svg)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)

---

## 📌 Project Overview

**Syntecxhub Amazon Customers Sentiment Analysis** is an NLP and Machine Learning project developed as part of the **Syntecxhub Internship - Project 2**.

The project analyzes Amazon customer reviews to determine customer sentiment using both:

- Lexicon-Based Sentiment Analysis
- Machine Learning Classification (TF-IDF + Logistic Regression)

The pipeline cleans review text, predicts customer sentiment, generates business insights, visualizes trends, and provides recommendations for product improvement.

---

# 🎯 Objectives

- Analyze Amazon customer reviews
- Clean and preprocess textual data
- Perform sentiment classification
- Compare Lexicon and Machine Learning approaches
- Visualize customer feedback trends
- Generate actionable business insights

---

# 🚀 Features

### ✅ Data Preprocessing

- Lowercase conversion
- URL removal
- Punctuation removal
- Stopword removal
- Tokenization
- Text normalization

---

### ✅ Lexicon-Based Sentiment Analysis

Uses manually curated

- Positive Words
- Negative Words

to classify reviews into

- Positive
- Neutral
- Negative

without requiring training data.

---

### ✅ Machine Learning Model

Pipeline:

```
Review
      ↓
Preprocessing
      ↓
TF-IDF Vectorization
      ↓
Logistic Regression
      ↓
Sentiment Prediction
```

Model Features

- TF-IDF Vectorizer
- Unigrams + Bigrams
- Maximum 2000 Features
- Balanced Logistic Regression
- Stratified Train/Test Split

---

# 📂 Project Structure

```
Syntecxhub_Amazon_Customers_Sentiment_Analysis
│
├── data
│   └── amazon_reviews.csv
│
├── src
│   ├── generate_data.py
│   ├── preprocess.py
│   ├── sentiment_model.py
│   └── main.py
│
├── outputs
│   ├── sentiment_results.csv
│   ├── insights_report.md
│   └── visualizations
│       ├── 01_sentiment_distribution.png
│       ├── 02_sentiment_by_rating.png
│       ├── 03_sentiment_trend.png
│       ├── 04_sentiment_by_product.png
│       ├── 05_top_words.png
│       └── 06_confusion_matrix.png
│
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/jismon-george/Syntecxhub_Amazon_Customers_Sentiment_Analysis.git
```

Move into the project

```bash
cd Syntecxhub_Amazon_Customers_Sentiment_Analysis
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Project

```bash
python src/main.py
```

The project automatically generates

- Sentiment Results CSV
- Insights Report
- Visualizations
- Model Evaluation
- Confusion Matrix

inside the **outputs/** folder.

---

# 🧹 Text Preprocessing Pipeline

```
Raw Review
      │
      ▼
Lowercase
      │
      ▼
Remove URLs
      │
      ▼
Remove Punctuation
      │
      ▼
Tokenization
      │
      ▼
Stopword Removal
      │
      ▼
Clean Review
```

---

# 🤖 Machine Learning Workflow

```
Amazon Reviews
        │
        ▼
Text Cleaning
        │
        ▼
TF-IDF Vectorizer
        │
        ▼
Train/Test Split
        │
        ▼
Logistic Regression
        │
        ▼
Prediction
        │
        ▼
Accuracy Evaluation
```

---

# 📊 Dataset Overview

| Metric | Value |
|---------|-------|
| Reviews | **800** |
| Products | **10** |
| Date Range | **2025-07-01 → 2026-07-01** |

---

# 😊 Sentiment Distribution

| Sentiment | Percentage |
|------------|------------|
| Positive | **59.2%** |
| Neutral | **18.0%** |
| Negative | **22.8%** |

---

# 📈 Model Performance

### Logistic Regression

Accuracy

```
100%
```

Classification Report

```
              precision    recall    f1-score

Negative         1.00      1.00       1.00
Neutral          1.00      1.00       1.00
Positive         1.00      1.00       1.00

Overall Accuracy : 100%
```

---

# 📊 Visualizations Generated

The project automatically creates

- Sentiment Distribution
- Sentiment by Rating
- Sentiment Trend Over Time
- Product-wise Sentiment
- Most Frequent Complaint Words
- Confusion Matrix

---

# 🔍 Key Insights

### ⭐ Best Performing Product

**Non-Stick Frying Pan Set**

Highest positive customer satisfaction.

---

### ⚠️ Product Requiring Improvement

**Wireless Bluetooth Earbuds**

Highest percentage of negative reviews.

---

### 📝 Most Common Complaint Keywords

- immediately
- buying
- packaging
- stopped
- arrived

---

# 💡 Business Recommendations

- Improve product quality for Wireless Bluetooth Earbuds.
- Investigate packaging and shipping issues.
- Use successful review language from the Non-Stick Frying Pan Set in marketing.
- Monitor weekly sentiment trends for quality control.
- Follow up with neutral reviewers to improve customer satisfaction.

---

# 📁 Output Files

```
outputs/

│── sentiment_results.csv
│── insights_report.md

└── visualizations/

    ├── 01_sentiment_distribution.png
    ├── 02_sentiment_by_rating.png
    ├── 03_sentiment_trend.png
    ├── 04_sentiment_by_product.png
    ├── 05_top_words.png
    └── 06_confusion_matrix.png
```

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- TF-IDF Vectorizer
- Logistic Regression

---

# 📚 Methodology

### Sentiment Labels

| Rating | Label |
|----------|-------|
| 4–5 ⭐ | Positive |
| 3 ⭐ | Neutral |
| 1–2 ⭐ | Negative |

---

### Lexicon Method

Counts positive and negative words.

```
Positive Words > Negative Words

↓

Positive Review
```

---

### Machine Learning Method

```
Reviews

↓

TF-IDF

↓

Logistic Regression

↓

Predicted Sentiment
```

---

# 🎯 Learning Outcomes

This project demonstrates

- Natural Language Processing
- Text Cleaning
- Sentiment Analysis
- Feature Engineering
- Machine Learning Classification
- Data Visualization
- Business Intelligence
- Customer Analytics

---

# 👨‍💻 Author

**JISMON GEORGE**

BCA Student | AI & Data Science Enthusiast

GitHub:
https://github.com/jismon-george

---

# ⭐ Repository Support

If you found this project useful,

⭐ Star the repository

🍴 Fork it

📢 Share it

---

## 📄 License

This project is developed for educational and internship purposes under the **Syntecxhub Internship Project**.
