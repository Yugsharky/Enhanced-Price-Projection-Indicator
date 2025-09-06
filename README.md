# Enhanced-Price-Projection-Indicator
Advanced Pine Script indicator predicting intraday price ranges using ATR, VWAP analysis, and historical probabilities. Features real-time range projections, breakout signals, accuracy tracking, and customizable visual elements for data-driven trading decisions.
Key Features:
🎯 Predictive Range Calculation:

Uses ATR (Average True Range) with customizable lookback periods
Incorporates volatility multipliers and VWAP standard deviation analysis
Accounts for opening gaps and market overextension conditions
Fixed range projections set at candle open for consistent analysis

📊 VWAP Integration:

Real-time VWAP calculation with standard deviation bands
Overextension detection (when price moves beyond VWAP ± std dev)
Dynamic volatility adjustment based on VWAP distance

🧮 Historical Probability Analysis:

Tracks accuracy of projected highs/lows over configurable periods
Calculates hit rates for both ATR and estimated True Range predictions
Real-time probability percentages displayed in data table
Maintains rolling history for statistical reliability

🎨 Visual Components:

Projected range boxes with customizable transparency
Upper/lower range lines with color coding
Breakout signals with triangle markers
Background highlighting for range breakouts
Comprehensive data table showing metrics and probabilities

⚙️ Customizable Settings:

ATR lookback period (1-100 bars)
Volatility multiplier (0.1-5.0x)
VWAP standard deviation multiplier (1.0-4.0x)
Probability calculation period (20-200 bars)
Visual styling options and color schemes

Use Cases:

Intraday range trading strategies
Breakout confirmation signals
Risk management with probabilistic targets
Market volatility assessment
Entry/exit point identification

Technical Requirements:

TradingView Pine Script v5
Works on all timeframes (optimized for intraday)
Maximum 100 boxes supported by TradingView
