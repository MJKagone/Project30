# Technical Debt Detection from Source Code Comments  

## Overview  
This project applies natural language processing (NLP) and machine learning to detect self-admitted technical debt (SATD) in source code comments. By leveraging sentiment analysis, TF-IDF vectorization, and supervised classification models, this work demonstrates effective techniques for automated SATD detection.  

## Key Results  
- High accuracy in SATD detection: Achieved an accuracy of 0.93 and an F1 score of 0.90 in binary classification using XGBoost with sentiment-enhanced features.  
- Sentiment-aware classification: Integrating sentiment scores improved detection performance, confirming their relevance in SATD identification.  

## Other Achievements  
- Comprehensive NLP analysis: Used Latent Dirichlet Allocation (LDA), FuzzyWuzzy, Empath and SentiStrength to investigate different NLP approaches to SATD detection, as well as NLTK for basic preprocessing tasks.
- Explored deep learning approaches: Evaluated BERT for classification, gaining hands-on experience with transformer-based deep learning models.  

## Tech Stack  
- **Languages**: Python  
- **Libraries**: scikit-learn, XGBoost, Transformers (BERT), NLTK, Empath, SentiStrength  

See [report.pdf](./report.pdf) for further details and [techinal_dept_sentiment.ipynb](./techinal_dept_sentiment.ipynb) for the implementation.
