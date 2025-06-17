# 🐦 Twitter Sentiment Analysis using NLP

This project performs **sentiment analysis** on tweets using Natural Language Processing (NLP) techniques and machine learning. It classifies tweets into **positive** or **negative** sentiments using the **Sentiment140 dataset**.

---

## 📦 Dataset

- **Source:** [Sentiment140 - Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140)
- **Content:** 1.6 million tweets labeled as:
  - `0` → Negative sentiment  
  - `4` → Positive sentiment

---

## 🧰 Libraries Used

- `pandas`, `numpy`
- `nltk` for text preprocessing
- `scikit-learn` for model building (Logistic Regression)
- `TfidfVectorizer` for feature extraction

---

## 🚀 Workflow

1. **Install and authenticate Kaggle API**
2. **Download and extract dataset**
3. **Clean and preprocess tweets**:
   - Remove links, punctuation, and stopwords
   - Apply stemming
4. **Convert text to numerical vectors** using TF-IDF
5. **Train a Logistic Regression model**
6. **Evaluate the model** using accuracy score

---

## 🧪 Model Performance

The model is evaluated on a hold-out test set using `accuracy_score` to measure how well it can predict the sentiment of unseen tweets.

---

## 📁 Project Structure

Twitter_Sentiment_Analysis/
│
├── sentiment_analysis.ipynb # Jupyter Notebook
├── kaggle.json # Kaggle API key (not shared publicly)
├── sentiment140.zip # Raw data (from Kaggle)
├── training.1600000.processed.noemoticon.csv # Dataset file
└── README.md # Project documentation


---

## 💡 Future Improvements

- Try advanced models: SVM, Random Forest, or XGBoost
- Use deep learning (LSTM or BERT)
- Visualize word clouds and frequent terms
- Deploy as a web app using Streamlit

---

## 📄 License

This project is open-source under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

**Your Name**  
Feel free to connect or give feedback!