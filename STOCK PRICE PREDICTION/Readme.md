# 📈 Stock Buy/Sell Classification using Tata Global Stock Data

This project focuses on building a simple **binary classification model** to predict stock trading signals (Buy or Sell) based on historical data from **Tata Global (Tata Consumer Products)**, using features derived from open, close, high, and low prices.

---

## 📂 Dataset

- **Source:** [Kaggle - NSE TATAGLOBAL Stock Data](https://www.kaggle.com/datasets/akshaydattatraykhare/nsetataglobal)
- **File:** `NSE-TATAGLOBAL11.csv`
- **Features:**
  - `Open`, `High`, `Low`, `Close`, `Volume`
  - Derived features: `Open - Close`, `High - Low`

---

## 🎯 Problem Statement

The goal is to predict whether a trader should:
- **Buy (+1)** or
- **Sell (-1)**  
a stock at any given day using technical indicators as features.

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib
- Scikit-learn (for model training)

---

## 🧠 Model Approach

1. **Feature Engineering**:
   - `Open - Close`
   - `High - Low`

2. **Target Variable (Y)**:
   - `+1`: Buy Signal
   - `-1`: Sell Signal

3. **Model Training**:
   - A binary classification model is trained (e.g., Logistic Regression or any classifier).

4. **Evaluation**:
   - Accuracy score and visual performance evaluation

---

## 📊 Visualization

A plot is generated showing the **closing prices** over time to help visualize trends before modeling.

---

## 🚀 How to Run

1. Clone the repository  
git clone https://github.com/yourusername/stock-buy-sell-classification.git
cd stock-buy-sell-classification

2. Install required libraries  
pip install -r requirements.txt

3. Run the notebook  
Open `stock_classification.ipynb` in Jupyter Notebook or VS Code

---

## 📌 Future Improvements

- Incorporate more technical indicators (e.g., RSI, MACD)
- Use time-series models like LSTM
- Add backtesting to simulate real trading performance

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙋‍♂️ Author

**Sajeesh K Mohanan**  
🔗 [LinkedIn](https://www.linkedin.com/in/sajeesh-k-mohanan-7a437218b/)  
💻 [GitHub](https://github.com/Sajeesh-mohanan)
