# NB Sentiment Baseline  

This project reproduces the results from **Danyal et al. (2024)**  
*Sentiment Analysis of Movie Reviews based on Naive Bayes using TF–IDF and Count Vectorizer.*

---

## Overview  
This work aims to replicate the methodology and results from the parent paper by using **Naive Bayes classifiers** with both **TF–IDF** and **Count Vectorizer** features.  
The implementation is modular so that each part — including feature extraction, model selection, and evaluation — can be adjusted or replaced for further testing.

---

## How to Run  

```bash
# Install dependencies
pip install -r requirements.txt

# Run the baseline experiment
python src/run_experiment.py --data data/imdb_sample.csv
