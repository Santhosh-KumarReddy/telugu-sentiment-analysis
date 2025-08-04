# Multilingual Transformer Evaluation for Telugu Sentiment Analysis: From Corpus Construction to Classification

## Abstract

Sentiment analysis in low-resource languages such as Telugu presents notable challenges due to the scarcity of annotated data and the linguistic complexity of the language. In this work, we introduce a sentiment classification pipeline using user-generated Telugu YouTube comments, along with their English translations. We manually curated and annotated a dataset of 1,287 comments with the help of native speakers.

We evaluated five state-of-the-art multilingual transformer models—**LaBSE**, **XLM-RoBERTa**, **mBERT**, **MuRIL**, and **IndicBERT**—under two strategies:
1. Direct fine-tuning using in-built classifiers
2. Feature extraction using embeddings followed by traditional ML classifiers (e.g., SVM, Logistic Regression)

Among these models, **LaBSE** achieved the best performance, with F1-scores of 0.78 on native Telugu comments and 0.80 on their English translations. These results highlight the potential of translation-based approaches and multilingual transformers for sentiment analysis in low-resource languages.

---

## 📁 Dataset

The annotated dataset of 1,287 Telugu YouTube comments, along with their English translations and sentiment labels, is available at the following link:

🔗 [https://github.com/Santhosh-KumarReddy/telugu-sentiment-dataset](https://github.com/Santhosh-KumarReddy/telugu-sentiment-dataset)

---

## 🧪 Models Evaluated

- LaBSE
- XLM-RoBERTa
- mBERT
- MuRIL
- IndicBERT

Two classification strategies were used:
- **In-built classification** using transformer model heads
- **Traditional ML classifiers** trained on extracted embeddings

---


