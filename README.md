# JCrypto — Automated Crypto Trading On Autopilot

**[jcrypto.net](https://jcrypto.net)**

JCrypto is a crypto trading bot platform that lets you deploy backtested algorithmic strategies in minutes. Paper trade for free, go live when you're ready.

---

## What It Does

- **7 trading strategies** — trend following, grid trading, breakout, mean reversion, and more. Pick what fits your style.
- **2+ years backtested** — every strategy is tested on historical data before you risk a dollar.
- **Live trading** — connect your Bybit account and trade 24/7 on autopilot.
- **Real-time analytics** — live P&L, win rate, drawdown, equity curves, and trade history.
- **Public leaderboard** — see how every bot is performing before you commit. No account required.

## How It Works

1. **Browse the leaderboard** — see real bot performance, cumulative PnL charts, and strategy breakdowns. No signup needed.
2. **Connect your exchange** — link your Bybit account with API keys. Your funds never leave the exchange.
3. **Pick a strategy** — choose from 7 backtested strategies. Configure symbols, leverage, and risk.
4. **Launch and monitor** — your bot trades 24/7 while you track performance from any device.

## Strategies

| Strategy | Style | Description |
|----------|-------|-------------|
| Trend Rider | Trend following | Donchian breakout entry and trailing stops |
| Wave Surfer | Multi-symbol trend | Concurrent breakouts across multiple coins |
| Dual Phase | Grid + trend | Grid during consolidation, trend trading during breakouts |
| Steady Mode | Grid trading | Fixed price range grid with consistent small profits |
| Swing Trader | Mean reversion | RSI-based entries with SMA targets |
| Gap Trader | Pullback | Fair value gap detection with scaled margin |
| Trendline Trader | Breakout + retest | Trendline breaks with higher timeframe trend alignment |
| Range Breakout | New coin breakout | Consolidation breakouts on newly listed coins |

## Pricing

| Plan | Price | Bots |
|------|-------|------|
| Free | $0 forever | 1 live + 5 paper |
| Premium | $100/mo | 5 live + 5 paper |
| Custom | Contact us | Unlimited |

All plans include all strategies, real-time monitoring, and the public leaderboard.

## Security & API Key Safety

Your API keys are **encrypted at rest** using AES-256-GCM encryption before being stored. They are only decrypted server-side when the bot needs to place a trade.

- **We never request or use withdrawal permissions.** Your API keys should only have trade permissions enabled. We cannot move funds out of your exchange account.
- **Your funds stay in your exchange at all times.** JCrypto connects via API to place trades — it never holds, transfers, or has custody of your funds.
- **You can revoke access anytime.** Delete your API key from your exchange account and the bot immediately loses access.
- **Paper trading requires no API keys at all.** Test strategies risk-free without connecting an exchange.

We recommend restricting your API key to our server IP and enabling only the minimum required permissions (Contract > Order on Bybit).

## Disclaimer

JCrypto is a trading tool, not financial advice. Cryptocurrency trading involves substantial risk of loss. Past backtest performance does not guarantee future results. You are solely responsible for your trading decisions and any losses incurred. Use at your own risk.

## Links

- **Website**: [jcrypto.net](https://jcrypto.net)
- **Leaderboard**: [View live bot performance](https://jcrypto.net/leaderboard)
