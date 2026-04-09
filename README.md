# Reddit International Payments Tracker

A read-only data monitoring tool that fetches and analyzes Reddit posts and comments related to international payments, fintech, and money transfers.

---

## 📌 Purpose

This tool helps users stay informed about discussions, trends, and news around international payments by aggregating relevant Reddit content in one place. It is built for research and informational purposes only.

---

## 🔍 What It Does

- Fetches public posts and comments from relevant subreddits
- Monitors discussions related to international payments, remittances, forex, and fintech
- Displays aggregated data for analysis and research
- **Does NOT post, vote, comment, or interact with Reddit content in any way**
- Purely a **read-only** application

---

## 📡 Subreddits Monitored

- r/fintech
- r/personalfinance
- r/Forex
- r/banking
- r/CryptoCurrency
- r/digitalnomad
- r/MoneyTransfer
- r/InternationalBanking

---

## 🛠️ Tech Stack

- **Language:** Python
- **API:** Reddit API (via PRAW)
- **Data Storage:** Local / CSV export
- **Frontend:** (Optional) Simple dashboard for visualization

---

## 🔐 API Usage

This project uses the Reddit API in compliance with Reddit's API Terms of Service and Responsible Builder Policy. It uses OAuth2 for authentication and respects all rate limits.

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/sabarirohith/reddit-payments-tracker.git

# Install dependencies
pip install praw pandas

# Add your Reddit API credentials in config.py
CLIENT_ID = "your_client_id"
CLIENT_SECRET = "your_client_secret"
USER_AGENT = "reddit-payments-tracker by u/yourusername"

# Run the app
python main.py
```

---

## 📄 License

MIT License — free to use and modify.

---

## 👤 Author

**Sabari Rohith**
Email: sabari.rohith@piperocket.digital
