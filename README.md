# Tamil Thirukkural Sentiment App

This app takes a Tamil sentence as input, detects the emotion (positive, negative, neutral), and recommends a relevant Thirukkural couplet with English translation.

## 🛠 Features
- Sentiment detection in Tamil
- Thirukkural suggestion based on mood
- Simple and efficient CLI-based interface

## 🧠 Tech Stack
- Python
- Scikit-learn
- Pandas
- Tamil NLP preprocessing
- Pickle for model storage

## 📂 Files
- `create_dataset.py`: Builds the dataset
- `model_trainer.py`: Trains the sentiment model
- `predict_and_suggest.py`: Predicts emotion and suggests Kural
- `tamil_sentiment_model.pkl`: Trained model

## ▶️ How to Run
```bash
python predict_and_suggest.py
