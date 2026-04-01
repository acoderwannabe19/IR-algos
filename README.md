# Information Retrieval Notebooks

This repository contains a collection of Jupyter notebooks developed as part of the **Information Retrieval** course at University of Geneva. The notebooks combine theoretical concepts with practical implementations, exploring classical and modern techniques for retrieving, analyzing, and representing text data.

Across the notebooks, I implemented some information retrieval models, conducted experiments on text corpora, and analyzed the behavior and performance of different approaches.

## 1. intro.ipynb
**Introduction to Information Retrieval and Jupyter Notebooks**

- Overview of the course structure and workflow.
- Setup and usage of Jupyter notebooks for assignments.
- Introduction to **NLTK** and basic text processing tools.

## 2. text_ir.ipynb
**Text Retrieval: Boolean and Vector Space Models**

- Implemented **Boolean Retrieval** and **Vector Space Models** for document search.
- Represented documents and queries as vectors.
- Applied **Porter stemming**, tag cloud visualization, and **tf-idf weighting**.
- Predicted document relevance to user queries using both retrieval models.

## 3. bir_lsi.ipynb
**Binary Independence Retrieval & Latent Semantic Indexing**

- Implemented the **Binary Independence Retrieval (BIR)** model.
- Explored **Latent Semantic Indexing (LSI)** for capturing semantic relationships in text.
- Extracted discriminative keywords using **Porter stemming** and **tf-idf**.
- Compared probabilistic and latent semantic approaches for ranking relevant documents.

## 4. zipf_law_pr.ipynb
**Zipf's Law and Precision/Recall Evaluation**

- Analyzed word frequency distributions in text corpora using **Zipf’s Law**.
- Visualized frequency patterns and linguistic distributions.
- Evaluated retrieval system performance using **precision** and **recall** metrics.

## 5. word_embeddings.ipynb
**Word Embeddings and Word2Vec**

- Implemented the fundamentals of **Word2Vec**.
- Explored **one-hot encoding**, **context windows**, and the **skip-gram model**.
- Trained neural networks to learn semantic vector representations of words.
- Investigated how embeddings capture semantic similarity between words.

## 6. page_rank.ipynb
**PageRank and Graph-Based Ranking**

- Modeled web pages and hyperlinks as a **graph structure**.
- Implemented the **PageRank algorithm** and **random walk simulations**.
- Analyzed how link structures influence ranking scores.
- Explored the applications of graph-based ranking in web search.

---

## Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-9CFF00?style=for-the-badge&logo=&logoColor=black)
![WordCloud](https://img.shields.io/badge/WordCloud-FFB300?style=for-the-badge&logo=&logoColor=black)
![NetworkX](https://img.shields.io/badge/NetworkX-00BFFF?style=for-the-badge&logo=&logoColor=black)