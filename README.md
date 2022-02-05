# Amazon reviews analysis

## Requirements:
Version Python - from 3.6.х

## Functional:
This project includes **sentiment analysis** and **classification of reviews by product category.**

Sentiment analysis in issentiment_analysis.ipynb contains the **following points:**

1. Сreating classes.
2. Load data.
3. Splitting the dataset into data for training and testing.
4. Сonverting a text dataset into numeric feature vectors.
5. Classification (linear svm, decision tree, logistic regression).
6. Evalution.
7. F1 scores.
8. Tuning model.
9. Saving model.

Calssification of reviews in category_analysis.ipynb contains the **following points:**

### To run the script:
```
git clone https://github.com/i11exx/amazon_reviews_analysis.git
cd amazon_reviews_analysis
jupyter-notebook sentiment_analysis.ipynb
jupyter-notebook category_analysis.ipynb
