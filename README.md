# 💹 CryptoView – Live Cryptocurrency Info Site

**CryptoView** is a simple, responsive cryptocurrency information website that displays live INR prices for Bitcoin, Ethereum, and Dogecoin. Built with HTML, CSS, JavaScript, and the CoinGecko API, this project serves as a foundation for learning real-time API integration and dynamic front-end development.

---

## 🧠 Project Description

This project was created as part of a JavaScript learning journey and fellowship activity. It fetches current INR prices of popular cryptocurrencies using [CoinGecko’s public API](https://www.coingecko.com/en/api/documentation) and visually displays them alongside external links for detailed information.

Clicking on each coin image will take users to its corresponding page on CoinGecko for in-depth insights. The site includes a modern UI, a navigational header, and a call-to-action to explore more crypto resources.

---

## 🚀 Features

- ✅ Real-time price display for Bitcoin, Ethereum, and Dogecoin (INR)
- 🔗 External links to CoinGecko for detailed coin pages
- 🧭 Navigation to global charts, comparison, and learning sections
- 🌐 Responsive design with background visuals
- ⚙️ CoinGecko API integration with jQuery AJAX
- 🎨 Clean and stylish interface

---

## 📁 File Structure

cryptoview/
├── index.html
├── style.css
├── index.js
└── images/
├── bitcoin.png
├── ethereum.png
├── dogecoin.png
├── background.jpg
└── logo.png

---

## 🔧 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/cryptoview.git
   
2. **Open the project folder in VS Code or your browser**

3. **Ensure internet access for live API data**

4. **Explore the code and modify as needed**

---

## 🛠 API Reference

**Base URL:**
https://api.coingecko.com/api/v3/simple/price?ids=bitcoin%2Cethereum%2Cdogecoin&vs_currencies=inr

You can modify this API URL to show additional coins or use a different currency (e.g., USD, EUR).

---

## 📌 Customization Ideas

Add more cryptocurrencies or change currency format

Animate price updates or auto-refresh values

Add a dark mode toggle

Implement historical price charts using other CoinGecko endpoints

---

## 📃 License
This project is intended for educational use. You’re welcome to fork, modify, and build upon it for personal or academic projects.
