# 🚀 PyQuotex

---
<p align="center">
  <a href="https://github.com/cleitonleonel/pyquotex">
    <img src="pyquotex.png" alt="pyquotex" width="45%" height="auto">
  </a>
</p>
<p align="center">
  <i>Unofficial Quotex Library API Client written in Python!</i>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/python-3.12%20%7C%203.13-green" alt="Python Versions"/>
</p>

---

## 📘 About the Project

**PyQuotex** was created as an open-source library to make communication with the Quotex platform via WebSockets easier. Over time, and due to misuse, a safer and more robust private version was created.

---

## 🎯 Library Goal

Provide tools for developers to integrate their systems with the Quotex platform, allowing automated operations in a safe and efficient way.

> ⚠️ This library **is not a trading bot** and does not make decisions on its own.

---

# 📚 Full Documentation
https://cleitonleonel.github.io/pyquotex/

---

## 🛠 Installation

### 1. Clone the repository:

```bash
git clone https://github.com/cleitonleonel/pyquotex.git
cd pyquotex
poetry install
poetry run python app.py
2. Or install directly in your project with Poetry:
bash
Copy
Edit
poetry add git+https://github.com/cleitonleonel/pyquotex.git
2.1. Install with a single command on Termux (Android):
shell
Copy
Edit
curl -sSL https://raw.githubusercontent.com/cleitonleonel/pyquotex/refs/heads/master/run_in_termux.sh | sh
3. Additional requirements
If you encounter an error related to playwright install when using this library, follow the steps below to fix the issue.

Install Playwright browsers
Make sure Playwright and the compatible browsers are installed.



bash
Copy
Edit
playwright install
🧪 Example Usage
python
Copy
Edit
from pyquotex.stable_api import Quotex

client = Quotex(
  email="your_email",
  password="your_password",
  lang="en"
)

await client.connect()
print(await client.get_balance())
await client.close()
💡 Main Features
Function	Description
connect()	Connects via WebSocket with reconnection
get_balance()	Returns account balance
buy_simple()	Executes a simple buy operation
buy_and_check_win()	Buys and checks the result
get_candle()	Returns historical candles
get_realtime_sentiment()	Real-time sentiment of the asset
balance_refill()	Refills demo account

🔒 Private Version Available
A private version is available with additional features, improved stability, and better support.

👉 Access the private version to unlock the full potential of PyQuotex!

💥 Version Comparison
Feature	Open Source ✅	Private Version ✨
Multi-login Support	❌	✅
Sentiment Monitoring	✅	✅ + advanced detection
Custom Proxy/DNS	❌	✅
Robustness & High Reliability	✅	✨ Enterprise level
Execution Speed	✅	⚡ Ultra fast
Support	❌	✅

🤝 Support this Project


💸 Cryptocurrencies
Dogecoin (DOGE): DMwSPQMk61hq49ChmTMkgyvUGZbVbWZekJ

Bitcoin (BTC): bc1qtea29xkpyx9jxtp2kc74m83rwh93vjp7nhpgkm

Ethereum (ETH): 0x20d1AD19277CaFddeE4B8f276ae9f3E761523223

Solana (SOL): 4wbE2FVU9x4gVErVSsWwhcdXQnDBrBVQFvbMqaaykcqo

📞 Contact
Telegram: @cleitonleonel

GitHub: cleitonleonel

LinkedIn: Cleiton Leonel

