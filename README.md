# StockPilot AI

StockPilot AI is a personal project I built to explore how AI agents, workflow automation, and financial APIs can work together in a practical real-world system.

The idea behind the project was simple:
instead of building just another chatbot, I wanted to create an assistant that could actually interact with financial data, understand different types of user input, and automate useful workflows.

The system is built using N8N, Google Gemini AI, Telegram Bots, webhooks, and multiple financial APIs.

It can currently understand:

* text queries
* voice messages
* trading chart screenshots
* and real-time stock/crypto related requests

The assistant is available through both:

* Telegram
* and a web-based chat interface built using Bolt AI

Both interfaces are connected to the same backend workflows using webhooks and AI agents.

---

# What the assistant can do

## Technical chart analysis

Users can upload chart screenshots directly from platforms like TradingView, and the assistant analyzes:

* bullish or bearish trends
* support and resistance zones
* momentum
* reversal possibilities
* and overall market structure

---

## Voice interaction

The system can:

* transcribe voice messages
* understand spoken queries
* generate AI-based voice replies

This made the interaction feel much more natural compared to a traditional chatbot.

---

## Real-time financial data

The assistant integrates multiple APIs to provide:

* stock market summaries
* cryptocurrency updates
* currency conversion
* technical indicators like RSI and MACD
* trading volume information
* latest financial news

It supports assets like:

* Bitcoin
* Ethereum
* stocks
* forex pairs
* and other market instruments

---

# Watchlist automation

One of the most interesting workflows I built was the watchlist automation system.

Users can simply send:
watch AAPL

and the system automatically:

* stores the stock inside Google Sheets
* maintains the watchlist
* tracks the asset
* and includes it in scheduled market update workflows

---

# Automated morning updates

I also built a scheduled workflow that runs automatically every morning.

The workflow:

* fetches watchlist assets
* retrieves live market data
* generates AI-based summaries
* and sends updates directly through Telegram

This made the assistant feel more proactive instead of just reactive.

---

# Technologies used

## Workflow & Automation

* N8N
* Webhooks
* AI Agents

## AI & Multi-Modal Processing

* Google Gemini AI
* Image Analysis
* Audio Transcription
* Conversational AI

## APIs & Integrations

* Alpha Vantage API
* Twelve Data API
* NewsAPI
* Telegram Bot API
* Google Sheets API
* CAMB.AI
* Bolt.new AI

---

# What I learned from this project

This project gave me hands-on experience with:

* workflow automation
* agentic AI systems
* multi-modal AI pipelines
* API orchestration
* real-time event-driven workflows
* conversational AI systems

One of the most interesting parts was designing the workflow logic between:

* AI agents
* chart analysis
* image classification
* watchlist management
* voice processing
* and scheduled automation workflows

---

# Future Improvements

Some ideas I plan to explore further:

* advanced portfolio tracking
* smarter AI-based alerts
* deeper market analysis
* better memory/context handling
* improved UI and user experience

---

Built by Tanmay Varshney
