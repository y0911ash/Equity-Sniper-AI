Equity-Sniper-AI: 5-Day Directional Predictor

Overview > This project implements a high-conviction trading strategy for NSE stocks (Tata Elxsi & Persistent Systems) using a dual-model approach: Lasso Regression and XGBoost.

Key Results > * Tata Elxsi: Achieved 100% Precision on out-of-sample test data by implementing a conservative 0.55 confidence threshold.

    Persistent Systems: Utilized an XGBoost "Sniper" logic to filter out noise in volatile market regimes.

Technical Stack > * Models: Lasso (L1 Regularization), XGBoost (Gradient Boosting).

    Data: Yahoo Finance API (Post-2021 Regime).

    Logic: 70:30 Chronological Split, ATR-based Volatility Filters, RSI Momentum.
