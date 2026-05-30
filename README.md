Apex Intelligence — Personal Financial Monitor
A comprehensive single-file financial intelligence platform built for day traders, long-term investors, and financial planners. No installation required — just open the HTML file in any browser.

Features
40 tabs organized across 6 groups:

Portfolio — Dashboard, Positions, Watchlist, Alerts, Top Grades, Dividends, Portfolio Analytics, Tax Lots, Paper Trading, Net Worth, Stress Test
Markets — Macro Dashboard, Economic Calendar, Earnings Calendar, Rates, Crypto, Funds & ETFs, Bonds & Fixed Income, News Sentiment
Research — Stock Screener, Stock Comparison, Fundamentals, Congress & World Watch, Wall St Firms, Valuation & Targets, Short Interest & Options Flow
Trading — Fast Money, Options, Analysis & Backtest, Stock Advisor, Alert Triggers, Position Sizing, DCA Simulator, Trade Journal
Planning — Life Insurance, Retirement Planner, Credit & Debt Management
More — Event Plays, Settings


Getting Started

Download apex_intelligence.html
Open it in Chrome or Edge (recommended)
Go to Settings to add your API keys:

AI Analysis — OpenAI, Gemini (free), or Grok
Live Prices — Alpha Vantage, Finnhub, FMP, or Tiingo (all have free tiers)


Add your positions in My Positions
Add stocks to track in Watchlist


API Keys (all optional, all free tiers available)
FeatureProviderFree TierAI AnalysisGoogle GeminiFreeAI AnalysisOpenAIPay per useLive PricesAlpha Vantage25 req/dayLive PricesFinnhub60 req/minLive PricesFMP250 req/day
Gemini is recommended for AI — it's free and works well for all analysis features.

Privacy
All personal data (positions, API keys, watchlist, journal, debts, net worth) is stored locally in your browser's localStorage. Nothing is transmitted to any server. API keys are only sent directly to the respective API provider when you request analysis or live prices.

How to Use

Live Prices — click the refresh button in the header to fetch current prices for all stocks in the app
AI Analysis — any tab with a brain icon button will generate AI analysis using your configured provider
Alert Triggers — set price, P&L, and grade alerts in the Alert Triggers tab; they fire automatically when prices are refreshed
Data Backup — use Settings → Export All Data to save a JSON backup of everything; Import to restore


Architecture
Single self-contained HTML file (~830KB). No framework installation, no build step, no server required. React 18 loaded from CDN. All 40 tabs, CSS, and JavaScript compiled into one file for maximum portability.

Disclaimer
This tool is for informational and educational purposes only. Nothing in this application constitutes financial advice. Always consult a licensed financial professional before making investment decisions. Congressional trade data and institutional ownership data shown is seed/example data — use the linked live sources for current filings.
