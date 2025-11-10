# NB Sentiment Baseline

This project reproduces the results from **Danyal et al. (2024)**  
*Sentiment Analysis of Movie Reviews based on Naive Bayes using TF–IDF and Count Vectorizer.*

---

## Overview
This work replicates the methodology and findings of the parent paper by applying **Naive Bayes classifiers** with both **TF–IDF** and **Count Vectorizer** features on the IMDb movie review dataset.  
The code is implemented in a modular way so that each part — including feature extraction, model selection, and evaluation — can be easily modified for further testing or extensions.

---

## How to Run

```bash
# Install dependencies
pip install -r requirements.txt

# Run the baseline experiments
python src/run_experiment.py --data data/imdb_full.csv --model mnb --vectorizer tfidf --ngram_max 1 --alpha 1.0 --max_features 50000
python src/run_experiment.py --data data/imdb_full.csv --model bnb --vectorizer count --ngram_max 1 --alpha 1.0 --max_features 50000

