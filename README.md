# Trading Risk Management & Position Sizer

A lightweight, browser-based position sizing tool designed for traders who follow strict risk management rules. This calculator helps you determine exactly how much capital to allocate to a trade based on your total net worth and a fixed percentage of risk.

## 🚀 Live Demo

You can access the live tool here: **[Trading Calculator](https://hossam96.github.io/trading-calculator/)**

## ✨ Features

* **Fixed Risk Modeling**: Calculates position sizes based on a specific percentage of your net worth (e.g., the "3% Rule").
* **Dynamic Matrix**: View a breakdown of recommended position sizes across various stop-loss levels (1% to 30%).
* **Quick Trade Calculator**: Input entry and stop-loss prices for specific assets to get the exact share/contract count.
* **Responsive Design**: Optimized for desktop and mobile use, allowing you to calculate sizes on the go.
* **Privacy First**: No data is sent to a server. All calculations happen locally in your browser.

## 📈 How It Works

The tool uses the standard risk management formula:
`Position Size = (Total Net Worth * Risk %) / Stop Loss %`

By keeping the "Risk Amount" constant, the tool automatically scales your position size up for tighter stops and down for wider stops, ensuring you never lose more than your predefined limit.

## 🛠️ Usage

1. **Global Parameters**: Set your current Net Worth and the maximum % you are willing to lose on a single trade.
2. **Quick Calculator**: Enter the price of the asset you want to trade and where your technical stop-loss is located.
3. **The Matrix**: Reference the table to see how different stop-loss percentages affect your buying power.

## 💻 Local Development

Since this is a single-file application, there is no installation required.

1. Clone the repository:
   ```bash
   git clone https://github.com/hossam-96/trading-calculator.git
2. Open `index.html` in any modern web browser.

## 📄 License
This project is licensed under the MIT License.

*Disclaimer: This tool is for educational and informational purposes only. Trading involves significant risk. Always perform your own due diligence.*
