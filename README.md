# RNN vs LSTM: Google Stock Price Prediction

## 🎯 Overview
Comparing **RNN** and **LSTM** neural networks for predicting Google stock prices to demonstrate why LSTMs handle sequential data better than traditional RNNs.

## 🧠 Key Concepts

### RNN (Recurrent Neural Network)
- Processes sequential data with memory
- **Problem**: Vanishing gradients → forgets long-term patterns
- Good for short sequences only

### LSTM (Long Short-Term Memory)
- Advanced RNN with gating mechanisms
- **Solution**: Gates control information flow → remembers long-term dependencies
- Better for complex time series

## 📊 Why Stock Prediction?
Perfect test case because:
- Sequential time-series data
- Long-term market trends matter
- Real-world application

## 🛠️ Implementation
- **Data**: Google stock prices (Open, High, Low, Close, Volume)
- **Goal**: Predict next day's closing price
- **Models**: Simple RNN vs LSTM comparison
- **Preprocessing**: Normalization, 60-day sequences

## 📈 Expected Results
- **LSTM**: Better accuracy, smoother predictions
- **RNN**: More volatile, struggles with long-term trends
- **30-Day Forecast**: Extended prediction capability with opening price adjustments

## 🚀 Getting Started
1. Open in Google Colab
2. Run all cells sequentially
3. Compare model performances
4. Visualize prediction results

*This project demonstrates why LSTMs revolutionized sequence modeling and became the foundation for modern NLP and time-series applications.*
