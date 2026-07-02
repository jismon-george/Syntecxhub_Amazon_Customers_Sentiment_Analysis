# Amazon Customer Sentiment Analysis — Insights Report

## Dataset Overview
- Total reviews analyzed: **800**
- Products covered: **10**
- Date range: **2025-07-01** to **2026-07-01**

## Sentiment Distribution
| Sentiment | % of Reviews |
|---|---|
| Positive | 59.2% |
| Neutral  | 18.0% |
| Negative | 22.8% |

## Classification Model Performance
A TF-IDF + Logistic Regression classifier was trained on rating-derived
sentiment labels and evaluated on a held-out 25% test split.

- **Accuracy:** 100.0%

```
              precision    recall  f1-score   support

    negative       1.00      1.00      1.00        52
     neutral       1.00      1.00      1.00        38
    positive       1.00      1.00      1.00       110

    accuracy                           1.00       200
   macro avg       1.00      1.00      1.00       200
weighted avg       1.00      1.00      1.00       200

```

## Key Patterns
- **Best-performing product** (highest share of positive reviews): **Non-Stick Frying Pan Set**
- **Product needing attention** (highest share of negative reviews): **Wireless Bluetooth Earbuds**
- **Most common complaint terms:** immediately, buying, packaging, stopped, arrived

## Recommendations for Product Improvement
1. Prioritize a quality review for **Wireless Bluetooth Earbuds**, focusing on the
   recurring complaint themes above (durability, defects, or usability
   issues typically drive negative sentiment).
2. Use **Non-Stick Frying Pan Set**'s positive review language as a template for
   marketing copy and product listing highlights.
3. Monitor the weekly sentiment trend chart for spikes in negative
   sentiment following shipments — this often correlates with a bad batch
   or packaging issue.
4. Since neutral reviews (18.0%) often signal room for
   improvement without outright dissatisfaction, consider proactive
   customer outreach or feedback surveys targeted at 3-star reviewers.

## Files Generated
- `outputs/sentiment_results.csv` — per-review sentiment results
- `outputs/visualizations/01_sentiment_distribution.png`
- `outputs/visualizations/02_sentiment_by_rating.png`
- `outputs/visualizations/03_sentiment_trend.png`
- `outputs/visualizations/04_sentiment_by_product.png`
- `outputs/visualizations/05_top_words.png`
- `outputs/visualizations/06_confusion_matrix.png`
