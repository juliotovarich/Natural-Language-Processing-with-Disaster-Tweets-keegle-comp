# NLP with Disaster Tweets Mini-Project

This repository contains my submission for the Kaggle "Natural Language Processing with Disaster Tweets" competition. I used TF-IDF for embedding, a Dense baseline, and LSTM for sequence modeling.

## Overview
- **Problem**: Binary classification of tweets to detect real disasters (target=1) vs non-disasters (target=0).
- **Dataset**: 7,613 train tweets, 3,263 test. Unbalanced (~57% target=0).
- **Approach**: EDA (length distribution, cleaning), TF-IDF + Dense baseline (~0.78 val acc), Tokenizer + LSTM (~0.80 val acc).
- **Results**: LSTM slightly outperformed Dense; submission score [tu score, e.g., 0.78].
- **Learnings**: Sequence embeddings (Tokenizer) improve RNNs over bag-of-words (TF-IDF).


GitHub Repo: https: https://github.com/juliotovarich/Natural-Language-Processing-with-Disaster-Tweets-keegle-comp
