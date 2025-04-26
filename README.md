# Sentiment-Classification-using-BERT

This project applies **BERT (Bidirectional Encoder Representations from Transformers)** to perform **binary sentiment classification** on IMDB movie reviews. The model is fine-tuned to distinguish between positive and negative sentiments based on natural language reviews.

## About the Project
Sentiment classification is a core task in Natural Language Processing (NLP) that involves identifying the emotional tone behind text. This project utilizes the power of pre-trained BERT to understand and classify the sentiment of user reviews more accurately than traditional models.

## Dataset
- **Source**: [IMDB Movie Review Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)
- **Size**: 50,000 labeled reviews (25,000 training, 25,000 testing)
- **Labels**: 
  - 1: Positive review
  - 0: Negative review

## Features
- Preprocessing of raw text data: lowercase, remove HTML tags, strip special characters.
- Tokenization using BERT's WordPiece tokenizer with special tokens.
- Fine-tuning BERT with a classification head for binary classification.
- Real-time sentiment prediction support.
- Evaluation and visualization tools for performance metrics.

## Setup Instructions
1. **Clone the repository**  
   ```bash
   git clone https://github.com/urmimirani/Sentiment-Classification-using-BERT.git
   cd Sentiment-Classification-using-BERT
2. **Clone the repository**
   ```bash
   python train.py
