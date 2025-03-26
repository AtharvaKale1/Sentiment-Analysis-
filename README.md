# 📌 Company Reviews Sentiment Analysis

## 📖 Project Overview
This project implements **sentiment analysis** on company reviews using **NLP and Deep Learning** techniques. The goal is to classify reviews as **Positive, Negative, or Neutral** using a TensorFlow-based model.

## 🚀 Features
- **Text Preprocessing:** Lowercasing, Tokenization, Stopword Removal
- **Sentiment Classification:** Predicts sentiment using a trained model
- **Deep Learning Model:** Utilizes TensorFlow Hub embeddings
- **Performance Metrics:** Accuracy, F1-score, Confusion Matrix
- **Visualization:** Sentiment distribution charts

## 🛠 Tech Stack
- **Language:** Python
- **Libraries:** TensorFlow, Pandas, Scikit-learn, TensorFlow Hub

## 📂 Dataset
The dataset consists of company reviews with sentiment labels:
```
Review 1: "Amazing work environment and culture." (Positive)
Review 2: "Low salary and no career growth." (Negative)
Review 3: "Work-life balance needs improvement." (Neutral)
```

## 📜 Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Company-Reviews-Sentiment-Analysis.git
   cd Company-Reviews-Sentiment-Analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download necessary NLP resources:
   ```python
   import nltk
   nltk.download('stopwords')
   nltk.download('punkt')
   ```
4. Run the sentiment analysis script:
   ```bash
   python sentiment_analysis.py
   ```

## 📊 Output
- **Sentiment Classification:** Positive, Negative, or Neutral
- **Evaluation Metrics:** Accuracy, F1-score, Confusion Matrix
- **Visualization:** Sentiment score distribution

## 🎯 Applications
- **HR Analytics:** Understand employee feedback
- **Business Intelligence:** Analyze customer sentiments
- **Market Research:** Identify brand reputation trends

## 🤝 Contribution
Contributions are welcome! Fork the repo, improve the code, and submit a pull request.

## 📜 License
This project is licensed under the MIT License.
