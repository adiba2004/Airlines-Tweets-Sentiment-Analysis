# Airlines-Tweets-Sentiment-Analysis
Airline Tweets Sentiment Analysis using DistilBERT to classify passenger tweets into Positive, Neutral, or Negative sentiments. Built with a fine-tuned BERT transformer model for high accuracy.
Built with Hugging Face Transformers, PyTorch, and Focal Loss for handling class imbalance.

🔹 Key Features
Model: distilbert-base-uncased fine-tuned for sentiment analysis

Dataset: Balanced Airline Twitter Sentiment Dataset (~1000 samples, 333/class)

Loss Function: Custom Focal Loss to improve classification on imbalanced data

Metrics: Accuracy, Weighted F1-score

Export: Model & label encoder packaged for Streamlit deployment

🔹 Tech Stack
Python, PyTorch, Transformers (Hugging Face)

Pandas, Scikit-learn, Datasets

🔹 Workflow
Data preprocessing & label encoding

1. Tokenization with DistilBERT tokenizer

2. Fine-tuning with Focal Loss

3. Evaluation using Accuracy & F1-score

4. Export model as deployment-ready .zip package



