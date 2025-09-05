# Task 5 - Topic Modeling on News Articles

## 📌 Description
Discover hidden themes in a collection of news articles using unsupervised NLP.  
We apply **Latent Dirichlet Allocation (LDA)** and compare with **NMF**.

## 🔧 Steps
1. Load BBC News Dataset (from Kaggle).
2. Preprocess text (lowercasing, stopwords, tokenization).
3. Apply LDA with Gensim.
4. Visualize topics with pyLDAvis.

## 📂 Project Structure
Task5_TopicModeling/
│── topic_modeling.ipynb
│── requirements.txt
│── README.md
│── data/
│ └── bbc_articles.csv (optional)
│── outputs/
│ └── lda_topics.html