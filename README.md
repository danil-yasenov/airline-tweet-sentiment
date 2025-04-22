# Airline Tweet Sentiment Classifier

This project is a machine learning model that classifies tweets about airlines into three sentiment classes: **positive**, **neutral**, or **negative**.

It was built as part of my application to the SMILES 2025 summer program, and focuses on practical application of classical ML tools to real-world social media data.

---

## 🔧 Tools & Stack
- Python
- scikit-learn
- pandas / numpy
- TfidfVectorizer
- LinearSVC
- WordCloud / seaborn for visualization

---

## 📂 Dataset

- Twitter Airline Sentiment dataset from [Kaggle](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)
- Preprocessed to remove links, stopwords, and noise
- Applied downsampling to balance classes

---

## 📊 Results

- Accuracy: ~75%
- Best performance on `negative`, improving recall on `positive` and `neutral` through:
  - `TfidfVectorizer` with bigrams/trigrams
  - Class weighting
  - Feature tuning

---

## 📁 Files

- `airline_sentiment_analysis.ipynb` — main notebook with full pipeline
- `requirements.txt` — install dependencies (optional)
- `README.md` — you're reading it

---

## 🙋‍♂️ Author

Danil Yasenov  
