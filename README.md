# Amazon-Stock-Price-Prediction-using-LSTM-and-Bidirectional-RNN_Deep-Learning

This project focused on forecasting Amazon’s stock price using deep learning models on historical data from 2006 to 2018. The dataset included daily open, high, low, close, and volume values. The objective was to predict the next day’s closing price and evaluate how well RNN-based models can capture stock market patterns.

**Tools**: Python, TensorFlow, Keras, NumPy, Scikit-learn, Matplotlib

**Approach**: Built and compared LSTM and Bidirectional RNN models for time series prediction. Data was normalized, sequenced, and evaluated using RMSE, MAE, and R².

**Results**: The LSTM achieved strong fit (R² ≈ 0.95 on test data) but showed overfitting with higher test errors. The Bidirectional RNN slightly improved generalization and captured temporal patterns more effectively.

**Key Insight**: Incorporating bidirectional context helps reduce overfitting and improves forecasting stability compared to a standard LSTM.
