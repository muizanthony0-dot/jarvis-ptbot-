# ⚡ Jarvis - Telegram Trading Signal Bot

Jarvis is a Python bot that analyzes crypto markets and sends trading signals to Telegram. Built for learning APIs + algorithmic trading.

> ⚠️ Educational only. Not financial advice. Trade at your own risk.

### What Jarvis does right now:
- Signal Generation: SHORT/LONG signals for BTC/USDT pairs
- Entry + Targets: Calculates Entry price, Take Profit, Stop Loss, Invalid level
- Indicators: ADX for trend strength, RSI, 4H + 15M timeframe analysis  
- Risk Management: Auto-calculates leverage, account risk %, R/R ratio
- Telegram Alerts: Sends formatted signals to Telegram channel
<img width="576" height="1280" alt="image" src="https://github.com/user-attachments/assets/03959585-8d5b-4ce8-86c4-55e30a0101ff" />

### How to run:
1. pip install ccxt pandas ta 
2. Create .env file with your API keys
3. python bot.py

### Project Structure:
bot.py - Main bot code

Built by @muzanthony0-dot
