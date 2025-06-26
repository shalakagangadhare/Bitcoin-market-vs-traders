# Bitcoin-market-vs-traders

# 🧠 Bitcoin Market Sentiment vs Trader Performance

## 🎯 Objective

This project explores the relationship between market sentiment—classified as **"Fear"** or **"Greed"**—and trader performance. By integrating historical trading data with the Bitcoin Fear & Greed Index, we aim to uncover behavioral patterns and performance trends that can inform smarter trading strategies.

---

## 📁 Datasets Used

### 1. 📊 Bitcoin Market Sentiment Dataset
- **Columns**:
  - `timestamp`
  - `value`
  - `date`
  - `classification` (values: "Fear", "Greed")

### 2. 📈 Hyperliquid Trader Dataset
- **Columns**:
  - `Account`, `Coin`, `Execution Price`, `Size Tokens`, `Size USD`, `Side`
  - `Timestamp IST`, `Start Position`, `Direction`, `Closed PnL`
  - `Transaction Hash`, `Order ID`, `Crossed`, `Fee`, `Trade ID`
  - `Timestamp`, `date`

---

## 🔍 Key Goals

- 📌 Analyze the **distribution of trades** under different sentiment conditions.
- 💰 Compare **average PnL** and **win rates** during "Fear" vs "Greed" days.
- 📈 Measure **correlation** between `leverage`, `position`, and `PnL`.
- ⚠️ Detect **trading risks or opportunities** based on emotional market states.

---

## 📊 Analysis Features

- Merging sentiment data with trader logs on the `date` column.
- Visualizing trends in `Closed PnL` by sentiment category.
- Rolling average plots to smooth volatility and analyze sentiment over time.
- Heatmaps to show correlations between numeric trading metrics.
- Sentiment-based filters to evaluate trading outcomes in different conditions.

---

## ✅ Tools Used

- Python, Pandas, NumPy for data wrangling
- Matplotlib, Seaborn for visualizations
- Google Colab for interactive development

---

## 🧠 Insights

- Greed days show [higher/lower] average PnL compared to fear days.
- Win rates tend to [increase/decrease] under [Greed/Fear] sentiment.
- High leverage during fear days often correlates with greater loss volatility.

---

## 🚀 Future Work

- Add predictive modeling using sentiment to classify trade profitability.
- Integrate more granular market data (e.g., BTC/USD price movements).
- Extend to other assets or exchanges for broader insight.

---

## 👤 Author

**Shalaka Gangadhare**  
_Data Science Intern at HH Tech Company_

Connect with me on [LinkedIn](https://www.linkedin.com)


