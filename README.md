# BA820-Unsupervised-and-Unstructured-Machine-Learning-Project

# Unsupervised & Unstructured Machine Learning Portfolio

This repository showcases applied analytics work in **unsupervised machine learning**, **dimensionality reduction**, and **text mining**. The goal is to turn messy, high-dimensional, and unstructured data into interpretable business insights.

## Highlights

- Applied PCA to reduce redundant social media engagement metrics
- Built text preprocessing and vectorization workflows for user comments
- Compared Bag-of-Words, similarity metrics, and neural embeddings
- Used sentence embeddings for unsupervised sentiment scoring
- Connected technical results to business use cases such as content analysis, engagement evaluation, spam detection, and review monitoring

## Main Notebooks

### 1. Facebook Metrics Analysis

**File:** `Facebook_Metrics_Analysis_Dimensionality_Reduction.ipynb`

Analyzes Facebook post engagement data and uses **PCA** to summarize overlapping metrics such as reach, impressions, likes, shares, comments, and total interactions.

**Skills demonstrated:**

- Data cleaning and preprocessing
- Feature scaling
- Correlation analysis
- Principal Component Analysis
- Explained variance interpretation
- Business interpretation of engagement patterns

### 2. Text Analysis Basics

**File:** `Text_Analysis_Basics_(edited).ipynb`

Processes YouTube comment text and demonstrates how raw text can be converted into numerical representations for similarity analysis and spam-related workflows.

**Skills demonstrated:**

- Regex-based text cleaning
- Tokenization
- Bag-of-Words vectorization
- Cosine similarity
- Word embeddings
- SentenceTransformer embeddings

### 3. Text Mining Applications

**File:** `Text_Mining_Applications_Basic_(edited).ipynb`

Applies embedding-based sentiment analysis to Goodreads reviews by comparing review text against positive and negative semantic anchors.

**Skills demonstrated:**

- Hugging Face dataset usage
- Sentence embeddings
- Cosine similarity scoring
- Unsupervised sentiment scoring
- Rating-versus-review sentiment comparison

## Technical Stack

- **Languages:** Python
- **Core libraries:** pandas, NumPy, scikit-learn, matplotlib, seaborn
- **NLP tools:** NLTK, gensim, sentence-transformers, Hugging Face datasets
- **Methods:** PCA, text vectorization, cosine similarity, embeddings, unsupervised sentiment scoring

## How to Run

```bash
git clone https://github.com/Nanase1994/Unsupervised-and-Unstructured-Machine-Learning-Project.git
cd Unsupervised-and-Unstructured-Machine-Learning-Project

python -m venv .venv
source .venv/bin/activate      # macOS/Linux
# .venv\Scripts\activate     # Windows

pip install pandas numpy matplotlib seaborn scikit-learn jupyter
pip install ucimlrepo nltk gensim sentence-transformers datasets

jupyter notebook
```

Some notebooks download datasets or pretrained models at runtime, so an internet connection may be required.

## Business Relevance

This project demonstrates the ability to:

- Analyze structured and unstructured data
- Reduce noisy feature spaces into interpretable components
- Build machine-readable representations from text
- Measure similarity across documents or comments
- Translate machine learning outputs into business-facing insights
- Communicate technical findings clearly to non-technical stakeholders

## Author

**Kaixin Gao**  
Finance & Business Analytics / Data Analytics Background  



