## 📈 F&O Stock Price Alert System

**Tools:** Google Sheets, Telegram Bot API  
**Type:** Market Monitoring | Automation  

### What this does
A live stock monitoring system that tracks 220 NSE 
F&O stocks and sends automatic Telegram alerts when 
any stock falls below its January 1st 2026 price.

### Features
- Tracks 220 NSE F&O stocks
- Historical price data — Jan 1st, Apr 1st, May 2nd
- % price change calculated between key dates
- Automated Telegram bot notifications on drawdowns
- Real-time market monitoring

### How it works
1. Google Sheet pulls and stores stock price data
2. Formula calculates % change from Jan 1st baseline
3. Telegram bot triggers alert when stock crosses 
   below Jan 1st price

### Skills used
Google Sheets, data tracking, automation, 
Telegram Bot API, F&O market knowledge
