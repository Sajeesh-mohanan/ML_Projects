# 🧠 Sentiment Scraper: Real-Time Web Sentiment Analysis with Transformers

This project demonstrates how to build a real-time sentiment analysis pipeline using **Hugging Face Transformers**, **PyTorch**, and **BeautifulSoup**. It scrapes text from websites, cleans it, and uses a pre-trained transformer model to classify sentiment (positive, negative, or neutral).

---

## 📌 Key Features

- 🌐 **Web Scraping**: Extracts raw text from any webpage using BeautifulSoup.
- 🧹 **Text Cleaning**: Cleans HTML tags, symbols, and unwanted content using regex.
- 🤗 **Transformer Model**: Uses Hugging Face’s `distilbert-base-uncased-finetuned-sst-2-english` for sentiment classification.
- 📊 **Sentiment Scoring**: Outputs label with confidence score.
- 🔧 **Fully Customizable**: You can plug in any Hugging Face model for other NLP tasks.

---

## 📦 Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- BeautifulSoup
- Requests
- Pandas, NumPy

---

## 🛠️ Installation

Make sure you have Python 3.7+ installed. Then run:

```bash
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
pip install transformers requests beautifulsoup4 pandas numpy

✅ Future Enhancements
Add multilingual support using models like xlm-roberta.

Build a Streamlit UI for interactive sentiment checking.

Batch analyze multiple URLs or files.

Store results in a database or Google Sheets.

👨‍💻 Author
Sajeesh K Mohanan
📧 sajeesh.mohanan |
🔗 LinkedIn