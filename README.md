
# Zerodha MCP Integration

![GitHub repo size](https://img.shields.io/github/repo-size/rushiavhad/Zerodha-McP)
![GitHub stars](https://img.shields.io/github/stars/rushiavhad/Zerodha-McP?style=social)
![GitHub forks](https://img.shields.io/github/forks/rushiavhad/Zerodha-McP?style=social)
![GitHub issues](https://img.shields.io/github/issues/rushiavhad/Zerodha-McP)
![GitHub license](https://img.shields.io/github/license/rushiavhad/Zerodha-McP)

---

🚀 Integrate Zerodha trading with Claude AI using MCP (Multi-Cloud Plugin).

---

## 🧩 Architecture

![Architecture Diagram](./assets/architecture.png)

---

## 🖼 Demo / Preview

![Demo](./assets/demo.gif)

---

## ⚙️ Tech Stack

* Python (FastAPI)
* MCP Framework
* Zerodha Kite Connect API
* Claude Desktop

---

## 🚀 Setup Instructions

### 1. Install via Smithery

```bash
npx -y @smithery/cli install @aptro/zerodha-mcp --client claude
```

---

### 2. Create Zerodha Developer Account

https://developers.kite.trade

---

### 3. Create App

* Redirect URL:
  `http://127.0.0.1:5000/zerodha/auth/redirect`

---

### 4. Add Environment Variables

Create `.env` file:

```bash
KITE_API_KEY=your_api_key_here
KITE_API_SECRET=your_api_secret_here
```

---

### 5. Install Dependencies

```bash
uv pip install kiteconnect fastapi uvicorn python-dotenv httpx
```

---

### 6. Install MCP Config

```bash
mcp install main.py
```

---

## 📌 Features

### 🔐 Authentication

* Auto login handling

### 📈 Trading

* Holdings
* Positions
* Margins
* Place Orders
* Get Quotes

### 💰 Mutual Funds

* SIP Management
* Orders
* Holdings

---

## 🔄 Authentication Flow

1. Start local server
2. Open Zerodha login
3. Store access token

---

## 🛠 MCP Tools

* Trading APIs
* Mutual Fund APIs
* Authentication APIs

---

## ⚠️ Troubleshooting

* Remove `.tokens` if auth fails
* Check `.env` values
* Ensure port 5000 is free

---

## 🔐 Security

* Local credential storage
* No third-party sharing

---

## 👨‍💻 Author

**Rushikesh Avhad**
GitHub: https://github.com/rushiavhad

---

## ⭐ Support

If you like this project:

* Star ⭐ the repo
* Fork 🍴 it
* Share 🚀

---
