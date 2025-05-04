# crypto-bot-using-python-binance

# README.md

## 📊 Crypto Trading Bot with Live Dashboard (Binance API, Python)

This is an intelligent, real-time cryptocurrency trading bot built in Python using the Binance API (Testnet). It automatically monitors selected trading pairs like **BTCUSDT** and **ETHUSDT**, and places buy/sell orders based on:

- 📈 **RSI indicators**
- 📉 **Moving Averages**
- 🔁 **Trailing Stop Loss**
- ✅ **Double Confirmation Strategy**

It also features a **live dashboard**, **animated profit graph**, **trade log**, and **final session summary** with profit analysis.

---

### 🔧 Features

- ✅ Real-time price fetching from Binance Testnet
- ✅ Multi-symbol trading support (BTC, ETH, etc.)
- ✅ RSI + Moving Average strategy with confirmation
- ✅ Trailing Stop Loss for intelligent exits
- ✅ Automatic order size validation (`NOTIONAL`, `LOT_SIZE`)
- ✅ Live console dashboard and profit chart
- ✅ Trade logging (`.csv`) and profit/sell tracking
- ✅ Final session summary with pie chart (Buy vs Sell)
- ✅ Clean `.gitignore`, `LICENSE`, and deployable design

---

### 📁 File Structure

```
├── trading_bot.py              # Main bot script
├── trade_log.csv               # Log of all executed trades
├── session_profit_graph.png    # Profit over time
├── trade_distribution_pie_chart.png  # Buy vs Sell breakdown
├── .gitignore                  # Ignore compiled, log, secrets
├── LICENSE                     # MIT License
└── README.md                   # Project overview
```

---

### 🛠 Setup

```bash
git clone https://github.com/yourusername/crypto-trading-bot.git
cd crypto-trading-bot
pip install -r requirements.txt
```

Add your API credentials in `trading_bot.py`:
```python
API_Key = 'your_api_key'
Secret_Key = 'your_secret_key'
```

Then run:
```bash
python trading_bot.py
```

---


# .gitignore

### Byte-compiled / cache files
__pycache__/
*.py[cod]
*.so
*.egg
*.egg-info/

### Logs and database
*.log
*.csv
*.sqlite

### Environments
.env
.venv/
env/
venv/
ENV/

### Jupyter/Colab/Notebook junk
.ipynb_checkpoints/

### System files
.DS_Store
Thumbs.db

### Token files or credentials (manually added if needed)
secrets.json
*.pem

### Ignore saved figures
*.png
*.jpg
*.jpeg


## LICENSE (MIT License)

This project is licensed under the [MIT License](LICENSE).

Copyright (c) 2025 Vinay Jain

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
