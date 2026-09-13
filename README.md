# 🔤 NLP Fundamentals Lab

Welcome to the **NLP Fundamentals Lab** repository! This project serves as a comprehensive hands-on guide and reference for foundational Natural Language Processing (NLP) techniques, text preprocessing strategies, and data vectorization pipelines.

---

## 📌 Project Overview

Before feeding text data into machine learning or deep learning models, raw unstructured text must undergo cleaning, normalization, and mathematical encoding. This laboratory repository demonstrates core NLP workflows step-by-step:

1. **Text Preprocessing & Cleansing**: Standardizing unstructured text data.
2. **Feature Extraction & Vectorization**: Converting textual tokens into numerical matrix representations.
3. **Data Pipeline Integration**: Structuring text representation workflows for downstream tasks (classification, clustering, or sentiment analysis).

---

## 🚀 Key Topics & Workflows

### 🛠️ 1. Text Preprocessing & Cleaning
- **Tokenization**: Breaking down text into words, subwords, or character-level tokens.
- **Normalization**: Lowercasing, removing punctuation, HTML tags, special characters, and digits.
- **Stop Words Removal**: Filtering out non-informative, high-frequency functional words.
- **Stemming & Lemmatization**: Reducing words to their base or dictionary forms (e.g., using NLTK / spaCy).

### 📊 2. Text Representation & Vectorization
- **Bag-of-Words (BoW)**: Counting word occurrences across document collections (`CountVectorizer`).
- **TF-IDF (Term Frequency-Inverse Document Frequency)**: Weighting words based on global document rarity (`TfidfVectorizer`).
- **N-gram Modeling**: Capturing local phrase context through unigrams, bigrams, and trigrams.
- **Dense Word Embeddings**: Exploring distributional semantic representations (e.g., Word2Vec, GloVe, FastText).

### 🤖 3. Downstream Preparation
- Converting vectorized features into standard array formats (`NumPy`, `Pandas`).
- Splitting processed text data into training and testing partitions for Machine Learning models.

---

## 🛠️ Prerequisites & Setup

### Requirements
- **Python 3.8+**
- Recommended virtual environment (`venv` or `conda`)

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/MchirguiS/NLP-Fundamentals-Lab.git](https://github.com/MchirguiS/NLP-Fundamentals-Lab.git)
   cd NLP-Fundamentals-Lab
