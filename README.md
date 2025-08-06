# ecommerce-review-ner-sentiment
Performs Named Entity Recognition and Sentiment Analysis on women’s clothing reviews using spaCy and NLTK.
# E-commerce Review NER & Sentiment Analysis

This project performs **Named Entity Recognition (NER)** and **Sentiment Analysis** on women's clothing e-commerce reviews using `spaCy` and `NLTK`. The goal is to extract entities and understand customer sentiment from product reviews.

## 📂 Dataset
The dataset used is *Women's Clothing E-Commerce Reviews*, containing customer feedback on products, ratings, and other metadata.

## 🔧 Features
- Named Entity Recognition using `spaCy` (`en_core_web_sm` model)
- Sentiment Analysis using `NLTK`'s `SentimentIntensityAnalyzer`
- Entity extraction from customer review texts
- Basic visualization and result interpretation

## 🛠️ Libraries Used
- Python
- pandas
- spaCy
- NLTK

## 🚀 How to Run
1. Clone the repository.
2. Install the required libraries:
   ```bash
   pip install pandas spacy nltk
   python -m spacy download en_core_web_sm

