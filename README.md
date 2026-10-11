# 📈 Algorithmic Trading Strategy

### Pine Script · TradingView · Algorithmic Trading · Technical Analysis · Backtesting

This repository presents an algorithmic trading strategy developed in **Pine Script v5 for TradingView**.

The project combines software development, AI-assisted development and technical market analysis to translate trading rules into programmable and testable strategy logic.

My work in algorithmic trading is not limited to this specific strategy. I can take a defined trading methodology or a client's strategy and work on translating its rules, conditions and risk-management criteria into Pine Script, adapting the implementation through an iterative development and testing process.

---

## 🎯 Project Objective

The objective of this project was to transform a technical trading methodology into a systematic strategy that can be executed and evaluated through TradingView's Strategy Tester.

The strategy combines trend, momentum, volatility and time-based conditions while incorporating several layers of risk management.

---

## ⚙️ Strategy Components

The current implementation includes:

- Fast and slow Exponential Moving Averages (EMA)
- Pre-crossover detection logic
- Long and Short signals
- ADX / DMI trend-strength filtering
- ATR-based volatility filtering
- Configurable trading-session filter
- Confirmed-bar signal validation
- ATR-based dynamic Stop Loss
- Configurable maximum-loss Hard Stop
- Trailing Stop with configurable activation and offset
- Configurable strategy parameters
- Visual representation of indicators and stop levels
- Historical backtesting through TradingView Strategy Tester

---

## 🧠 Signal Logic

The strategy analyzes the relationship between a fast EMA and a slow EMA.

Instead of relying exclusively on the completed crossover, the system evaluates the distance and movement between both averages to identify potential pre-crossover conditions.

Signals are then filtered using additional market conditions such as:

- Trend strength
- Volatility
- Trading session
- Confirmed candle data

This creates a multi-condition decision system rather than relying on a single technical indicator.

---

## 🛡️ Risk Management

Risk management is an important part of the strategy architecture.

The system incorporates:

**Dynamic ATR Stop Loss**  
Stop levels adapt to current market volatility.

**Maximum Loss Hard Stop**  
A configurable percentage-based limit provides an additional protection layer.

**Trailing Stop**  
Once configured conditions are reached, the trailing mechanism follows favorable price movement according to defined activation and offset parameters.

---

## 📊 Backtesting

The strategy is evaluated using **TradingView Strategy Tester**.

Backtesting allows the logic to be analyzed across historical market data and helps identify:

- Number of trades
- Winning and losing trades
- Profit factor
- Maximum drawdown
- Strategy behavior under different market conditions
- Effects of parameter adjustments

Backtesting results represent historical simulations and do not guarantee future performance.

---

## 🤖 AI-Assisted Strategy Development

Artificial intelligence is incorporated into my development workflow as a programming and problem-solving tool.

My workflow can include:

1. Understanding the trading strategy and its rules
2. Translating discretionary conditions into explicit logical rules
3. Structuring the strategy in Pine Script
4. Implementing indicators and filters
5. Developing entry and exit conditions
6. Implementing risk-management logic
7. Running historical backtests
8. Identifying logical or technical issues
9. Adjusting and refining the implementation

My knowledge of **technical market analysis** helps me understand the trading concepts behind a strategy rather than treating the requirements only as programming instructions.

---

## 💻 Technologies & Concepts

- Pine Script v5
- TradingView
- Algorithmic Trading
- Technical Analysis
- Strategy Development
- Backtesting
- Risk Management
- EMA
- ADX / DMI
- ATR
- Long / Short Logic
- Trailing Stops
- AI-Assisted Development

---

## 🔒 Source Code

The complete strategy source code is kept private.

This public repository is intended as a technical portfolio showcase demonstrating the architecture, logic and development process behind the project without exposing the proprietary strategy implementation.

---

## ⚠️ Disclaimer

This project is presented for software development, technical demonstration and educational purposes.

Historical backtesting results do not guarantee future performance and should not be interpreted as financial advice or as a promise of profitability.

---

## 👨‍💻 Developer

**Fernando Álvarez**  
Full Stack Developer | AI-Assisted Software Development  
Algorithmic Trading & Pine Script Development


---

---

## 📸 Strategy in Action

### TradingView Chart & Trade Signals

The strategy identifies potential long and short opportunities using EMA behavior, trend strength, volatility filters and risk-management rules.

![TradingView Strategy](./estrategia_comercial_1.png)

### Trade Execution History

TradingView's Strategy Tester allows the system to be evaluated through historical trades, including long and short positions.

![Trade History](./estrategia_de_comercio_2.png)

### Backtesting Performance

Historical backtesting is used to analyze strategy behavior, profitability, drawdown, win rate and profit factor under the tested configuration.

![Backtesting Performance](./estrategia_de_comercio_3.png)

> **Disclaimer:** Backtesting results are historical simulations and do not guarantee future performance.
