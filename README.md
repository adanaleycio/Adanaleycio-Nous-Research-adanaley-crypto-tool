# 🚀 Hermes Agent - Advanced Crypto Price Skill

This repository contains a high-performance cryptocurrency data tracking module specifically developed for the **Hermes Agent** ecosystem. 🛠️

## 🧠 About My Implementation

The core philosophy behind this project is **modularity** and **system stability**. Instead of modifying the core files of the Hermes Agent (such as `__init__.py`), I implemented this as a standalone, plug-and-playable module that utilizes the agent's terminal execution capabilities.

* **Clean Architecture:** Designed with functional programming principles, avoiding unnecessary complexity.
* **Robust Error Handling:** Features a secure architecture that catches API connection timeouts and invalid user inputs.
* **Seamless Integration:** Built to be easily dropped into any existing Hermes installation without breaking core functionalities.

## 💸 Developed Bitcoin & Altcoin Skill

This skill leverages the **CoinGecko API** to bring real-time market intelligence directly to your terminal. It supports Bitcoin and thousands of other altcoins. 📊

### ✨ Key Features:
* **Live Prices:** Instant market data retrieval using the `price get` command. ⚡
* **Historical Data:** Deep-dive analysis capabilities with the `price history` feature. 📈
* **Multi-Currency Support:** Fetching data in various parities like USD or EUR. 🌍

## 🛠️ Installation & Usage

1. **Install Dependencies:**
   ```bash
   pip install requests
