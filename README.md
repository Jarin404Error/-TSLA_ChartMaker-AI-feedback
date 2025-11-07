TSLA INTRADAY LEVELS DASHBOARD
A live, interactive dashboard built with Streamlit to automatically track and plot key intraday levels for TSLA

**CHECK OUT THE LIVE APP!**
https://tsla-intradaydashboard.streamlit.app/

**Why I Built This**

As a CS student who's also has interest in STOCK Trading, I got fascinated by day trading, especially with volatile stocks like TSLA. I kept hearing traders talk about "key levels"—like the pre-market high/low or the "Opening Range Breakout" (ORB)—and how they act as support or resistance.
My problem? It was a pain to find and plot these manually every single morning. I'd be trying to draw lines on my chart while also watching lectures.
So, I did what any CS student would do: I decided to automate it.
This project is the result. It's a simple, clean web app that does all the annoying work for me. It fetches the latest data from yfinance, calculates all the important levels in real-time, and plots them on an interactive chart I can open on my phone or laptop. It even has logic to merge the 5-min and 15-min ORB levels if they're the same, which cleans up the chart.
What started as a personal tool to save me 10 minutes every morning turned into a really fun project for learning Streamlit, Plotly, and how to build a live, data-driven app.

**TECH USED**
🐍 Python: The core language for all the logic.
⚡ Streamlit: For building the interactive web app (it's amazing, way faster than learning a full-stack framework).
📈 Plotly: To create the beautiful, interactive candlestick charts.
yfinance: For pulling near-real-time stock data from Yahoo! Finance.
🐼 Pandas & NumPy: For all the data manipulation, time-crunching, and level calculations.






  💡Future Plans

This as a ton of fun, but I'm already thinking about what's next:
Integrate a Gemini AI model: I want to add a new "AI Analysis" section to the sidebar. It would take the current price, all the calculated levels, and provide a simple, neutral summary (e.g., "Price is currently testing the Pre-Market High. The next level of support is the 15-min ORB Low...").

Add More Tickers: Let the user enter any stock ticker most likely SPY, not just TSLA.

Historical Level Testing: Let the user go back in time and see how these levels performed on any given day.
