# AI Market-Research-Assistant
Automated market news and price alert pipeline built with Zapier.
The problem is that staying on top of market moves for a watchlist ticker means manually checking multiple news sites and price charts every day, which doesn't scale. My approach was building a two-part automation using Zapier. One flow watches a financial news feed and logs every new headline into a Google Sheet automatically. A second flow runs hourly, pulls the live price and percent change for a chosen ETF, and emails a formatted update. Tools used are Zapier, Google Sheets, Gmail, and an RSS feed. The result is a pipeline that runs with no manual checking needed. Next steps are combining both streams into one AI-generated brief, adding more tickers, and adding a significance threshold for alerts.

Screenshot, the two step Zap pulling live stock price data
<img width="1575" height="697" alt="Automated market news and price alert pipeline built with Zapier" src="https://github.com/user-attachments/assets/7b9c9dfb-21a4-469a-bf1a-8f3aa5d5edfe" />

Screenshot, the Google Sheet automatically logging live headlines and price data.
<img width="1807" height="853" alt="Google Sheet Automated market news and price alert pipeline built with Zapier" src="https://github.com/user-attachments/assets/000788ff-5973-4084-b457-22173889b26d" />

Screenshot, the hourly email delivering the live stock price update.
<img width="1353" height="430" alt="Email Automated market news and price alert pipeline built with Zapier" src="https://github.com/user-attachments/assets/8f3c3052-f858-4ad9-95df-55215dcf284c" />

