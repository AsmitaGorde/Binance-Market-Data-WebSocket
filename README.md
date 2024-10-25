# Binance-Market-Data-WebSocket
# Binance Market Data WebSocket with Real-time Candlestick Charts
This project demonstrates how to connect to Binance's WebSocket API to display real-time cryptocurrency market data using a candlestick chart. The app provides real-time updates for ETH/USDT, BNB/USDT, and DOT/USDT pairs, with adjustable candlestick timeframes (1m, 3m, and 5m). The project uses Chart.js for visualization and stores historical data in local storage to maintain chart state across coin switches.

# Features
Real-time WebSocket connection to Binance for selected cryptocurrency pairs.
Candlestick chart visualization using Chart.js and the chartjs-chart-financial plugin.
Toggle between ETH/USDT, BNB/USDT, and DOT/USDT pairs.
Choose between 1-minute, 3-minute, and 5-minute candlestick intervals.
Persist chart data using local storage so chart state is maintained even when switching between cryptocurrencies.
Responsive and clean UI for selecting coins and timeframes.
# Technologies Used
HTML5, CSS3 for structure and styling.
JavaScript for logic and WebSocket handling.
Chart.js and chartjs-chart-financial forUsage
Open the page in your browser.
Select a cryptocurrency pair (ETH/USDT, BNB/USDT, or DOT/USDT) from the dropdown.
Select the candlestick timeframe (1 minute, 3 minutes, or 5 minutes).
The chart will update in real-time as new candlestick data arrives via the WebSocket connection.
Historical chart data for each cryptocurrency pair is saved in the browser's local storage, so when you switch between pairs, the previous data will be restored.
# Project Structure
bash
Copy code
binance-market-data-websocket/
├── index.html    # Main HTML file containing the project
└── README.md     # Project readme file
Key Sections in the Code
WebSocket Connection: Connects to Binance's WebSocket API to receive live market data.
Chart.js Initialization: Renders the candlestick chart and updates it dynamically as new data is received.
Event Listeners: Handles user inputs for selecting different coins and timeframes.
Local Storage Handling: Persists candlestick data in local storage for each coin.
Screenshot

# Future Enhancements
Add support for more cryptocurrency pairs.
Add additional chart types (e.g., line chart, OHLC).
Implement more advanced features such as technical indicators (RSI, MACD).
License
This project is open-source and available under the MIT License.

# Contributions
Feel free to open issues or submit pull requests if you find any bugs or want to contribute new features.

# References
Binance WebSocket API
Chart.js Documentation candlestick chart rendering.
Bootstrap 5 for responsive design.
Binance WebSocket API for real-time data streaming.

