# Trading Risk Management & Position Sizer

A lightweight, browser-based position sizing tool designed for traders who follow strict risk management rules. This calculator helps you determine exactly how much capital to allocate to a trade based on your total net worth and a fixed percentage of risk.

## 🚀 Live Demo

You can access the live tool here: **[Trading Calculator](https://hossam-96.github.io/trading-calculator/)**

## ✨ Features

* **Risk-Based Position Sizing**: Calculates position sizes based on different maximum risk percentages of your net worth (0.1% to 3%).
* **Dynamic Matrix**: View a breakdown of recommended position sizes across various maximum risk-per-trade levels using your stop-loss from the Quick Calculator.
* **Quick Trade Calculator**: Input entry and stop-loss prices for specific assets to get the exact share/contract count.
* **Responsive Design**: Optimized for desktop and mobile use, allowing you to calculate sizes on the go.
* **Privacy First**: No data is sent to a server. All calculations happen locally in your browser.

## 📈 How It Works

The tool uses the standard risk management formula:
`Position Size = (Total Net Worth * Maximum Risk %) / Stop Loss %`

The Position Sizing Matrix displays different maximum risk percentages (0.1%, 0.2%, 0.3%, 0.4%, 0.5%, 1%, 1.5%, 2%, 2.5%, 3%) and calculates the corresponding position size based on the stop-loss percentage from your Quick Trade Calculator entry (defaults to 5% if not specified).

## 🛠️ Usage

1. **Global Parameters**: Set your current Net Worth and your preferred maximum risk percentage per trade.
2. **Quick Calculator**: Enter the price of the asset you want to trade and where your technical stop-loss is located.
3. **The Matrix**: Reference the table to see how different maximum risk percentages affect your position sizes based on your stop-loss level.

## 💻 Local Development

Since this is a single-file application, there is no installation required.

1. Clone the repository:
   ```bash
   git clone https://github.com/hossam-96/trading-calculator.git
2. Open `index.html` in any modern web browser.

## 📄 License
This project is licensed under the MIT License.

*Disclaimer: This tool is for educational and informational purposes only. Trading involves significant risk. Always perform your own due diligence.*
