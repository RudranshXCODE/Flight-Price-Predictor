
# ✈️ Flight Price Predictor for FlyIndia Airways

This project uses an Artificial Neural Network (ANN) regression model to predict flight ticket prices for FlyIndia Airways, a budget airline. The model is trained using historical data including city pairs, class, booking time, duration, and airline.

## 📊 Dataset
The dataset was sourced from Kaggle: [Flight Price Prediction Dataset](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)

We used `Clean_Dataset.csv`, which includes:
- Airline, Source & Destination Cities
- Departure & Arrival Time Blocks
- Number of Stops, Travel Class
- Flight Duration, Days Left for Travel
- Target Variable: Ticket Price (INR)

## ⚙️ Model Architecture
- Type: ANN Regression using TensorFlow/Keras
- Layers: 64 → 32 → 1 (ReLU activations)
- Loss: Mean Squared Error (MSE)
- Optimizer: Adam

## 📈 Results
- RMSE: ~5422  
- MAE: ~3283  
The model shows reasonable accuracy for price prediction and supports dynamic pricing strategy analysis.

## 🧪 Sample Predictions
```
Predicted: [4579.59, 61846.0, 6188.13, 56609.36, 5530.49]  
Actual:    [7366, 64831, 6195, 60160, 6578]
```

## 🧠 Libraries Used
- Python 3, Pandas, NumPy, Scikit-learn
- TensorFlow / Keras

## 📦 How to Run
1. Clone this repo or open in Google Colab
2. Upload `Clean_Dataset.csv` or use the Kaggle link
3. Run the notebook end to end

## 🏁 Outcome
This project was created as part of an internship with **YBI Foundation** and demonstrates a basic implementation of ANN for real-world pricing prediction in aviation.
