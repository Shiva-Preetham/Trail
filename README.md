# ML vs Technical Indicators: Stock Prediction Strategy

This project compares a traditional RSI + Moving Average crossover strategy against a machine learning model (XGBoost) trained on multiple technical indicators. It uses historical stock price data and visualizes the feature importance and accuracy comparison.

## 🔍 Features Used
- RSI, ATR
- Moving Averages (MA40, MA80, MA160)
- Slope features: slopeMA40, slopeMA160
- Custom features: Average, AverageSlope, RSISlope

## 🤖 ML Model
- Model: XGBoostClassifier
- Evaluation: Accuracy Score
- Feature Importance plotted

## 📊 Strategy Comparison
- Traditional TA: RSI + MA Crossover
- ML Strategy: XGBoost on all indicators
- Accuracy comparison bar chart

