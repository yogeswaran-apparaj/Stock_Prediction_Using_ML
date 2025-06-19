# Stock_Prediction_Using_ML
Predict future stock prices using machine learning techniques like LSTM and technical indicators.
🔍 Project Overview

- ✅ Collected historical stock data for Apple Inc. (AAPL)
- ✅ Added **technical indicators** such as:
  - Simple Moving Average (SMA-20)
  - Relative Strength Index (RSI)
- ✅ Used **LSTM (Long Short-Term Memory)** neural networks to learn trends
- ✅ Evaluated model using **RMSE (Root Mean Squared Error)**
- ✅ Visualized predicted vs. actual prices

---

## 💻 Tech Stack

| Component          | Tool/Library       |
|--------------------|--------------------|
| Language           | Python             |
| Data Handling      | Pandas             |
| ML / Deep Learning | Scikit-learn, TensorFlow / Keras |
| Visualization      | Matplotlib         |
| Financial Indicators | `ta` (Technical Analysis library) |
| Data Source        | Yahoo Finance (via `yfinance`) |
| IDE / Notebook     | Google Colab       |

---

## 🧠 Model Architecture

- 2 stacked **LSTM layers**
- 1 **Dense layer** for output
- Optimizer: `adam`
- Loss: `mean_squared_error`
- Sequence window: 60 days

---

## 📂 Project Structure

📁 Stock_Prediction_Using_ML/
│
├── AAPL.csv                   # Raw stock data (downloaded)
├── AAPL_with_indicators.csv  # Processed data with SMA and RSI
├── data_downloader.ipynb     # Script to download stock data from Yahoo Finance
├── feature_engineering.ipynb # Adds technical indicators (SMA, RSI)
├── lstm_model.ipynb          # LSTM model training, evaluation, and visualization
└── README.md                 # Project documentation (this file)


---

## 🛠️ How to Run (in Google Colab)

1. Upload this folder to your **Google Drive**
2. Open `lstm_model.ipynb` in **Google Colab**
3. Run the cells step by step
4. Model will train and plot predictions vs actual

---

## 📊 Sample Output

*LSTM Prediction vs. Actual Closing Price:*

![image](https://github.com/user-attachments/assets/9697a175-03e2-45fe-8e2e-5f4f0ec4eace)


---

## 📦 Requirements

Install required packages (in Colab or local):

```python
!pip install ta yfinance scikit-learn matplotlib pandas tensorflow




## 👨‍💻 Author

**Yogeswaran Apparaj**  
B.Tech Artificial Intelligence and Data Science  
GitHub: [@yogeswaran-apparaj](https://github.com/yogeswaran-apparaj)
📧 Email: yogeswaranapparaj834@gmail.com  
🔗 LinkedIn: [linkedin.com/in/yogeswaran-apparaj](https://www.linkedin.com/in/yogeswaran-apparaj-637a4536b/)
