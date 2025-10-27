# Sentiment Analysis on Tweets

This project explores linguistic patterns and sentiment polarity in short text messages using a Kaggle sentiment dataset. It is developed for educational and research purposes.

---

## 📘 Dataset

**Source:** [Kaggle - Sentiment Analysis Dataset](https://www.kaggle.com/datasets/abhi8923shriv/sentiment-analysis-dataset)
**Uploader:** *abhi8923shriv*
**Description:**
The dataset contains text samples (tweets) labeled with sentiment polarity — either *positive* or *negative*.
Used here for text cleaning, feature extraction, and exploratory sentiment analysis.

---

## 🎯 Research Questions

1. **RQ1:** What are the most common linguistic features (words) that distinguish between positive and negative tweets? 
2. **RQ2:** Can we build a simple model to classify tweet sentiment?

---

## 🧠 Methods

### Data Preprocessing

* Text cleaning: lowercasing, removing URLs, mentions, hashtags, special characters.
* Tokenization and stopword removal using `nltk`.
* Representing text using **TF-IDF** features with `scikit-learn`.

### Analysis & Visualization

* Compute average TF-IDF scores for positive and negative sentiments.
* Display top keywords for each sentiment.
* Generate **WordClouds** for visual comparison.

---

## 🧰 Libraries Used

* `pandas`
* `nltk`
* `scikit-learn`
* `matplotlib`
* `wordcloud`
* `numpy`

All dependencies are listed in `requirements.txt`.

---

## 📊 Results

* The most frequent words differ significantly between positive and negative sentiments.
* TF-IDF-based word clouds highlight strong linguistic patterns (e.g., “love”, “great” for positive vs. “bad”, “worst” for negative).
* Visualizations are saved under `/results`.

Example plots:

```
results/
├── positive_wordcloud.png
├── negative_wordcloud.png
```

---


