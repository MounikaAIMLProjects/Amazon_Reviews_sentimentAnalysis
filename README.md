# Amazon Reviews Sentiment Analysis

**Author:** Mounika Thumma  
**Project Type:** Natural Language Processing (NLP), Machine Learning  
**Language/Frameworks:** Python, Pandas, NLTK, Scikit-learn, Matplotlib, Seaborn  

---

## ⭐ Project Overview
This project performs sentiment analysis on Amazon product reviews.  
It classifies reviews as **Positive** or **Negative** using classical NLP techniques and a Logistic Regression classifier.

The project pipeline includes:
1. Data loading and preprocessing  
2. Text cleaning, stemming, and stopword removal  
3. Visualization using WordClouds  
4. Feature extraction with TF-IDF  
5. Machine learning model training (Logistic Regression)  
6. Model evaluation using accuracy, classification report, and confusion matrix  

---

## 📂 Dataset
- The dataset should be a CSV file named `amazon_reviews.csv` with at least two columns:
  - `Review` → Text of the review  
  - `Sentiment` → Label (`Positive` or `Negative`)  
- Missing values are dropped automatically during preprocessing.

> **Note:** You can use your own dataset or sample Amazon reviews dataset for testing.

---

## 🛠 Project Setup

1. Clone the repository:
```bash
git clone <your-github-repo-url>
cd Amazon-Reviews-Sentiment-Analysis
