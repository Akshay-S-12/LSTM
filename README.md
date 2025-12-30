🥛 Milk Production Forecasting Using LSTM


This project implements a Milk Production Forecasting system using a Long Short-Term Memory (LSTM) neural network.
The model predicts future milk production values based on historical monthly production data.

The goal is to demonstrate how LSTM networks can effectively learn temporal and seasonal patterns in time-series data.

📌 Features
🧠 Uses LSTM for time-series forecasting
🔁 Sequence learning with sliding window approach
📈 Monthly milk production prediction
📊 Training loss visualization
💾 Trained model saved for reuse
🔍 Supports forecasting on unseen future data

🛠️ Technologies Used
Python  
TensorFlow / Keras  
LSTM (Deep Learning)  
Pandas, NumPy  
Matplotlib, Seaborn  
Scikit-learn  

📂 Project Structure
Milk-Production-LSTM/  
│  
├── lstm_milk_production.ipynb  
├── README.md  
├── dataset/  
│   └── monthly_milk_production.csv  

⚙️ Model Architecture
LSTM Layer: 100 units (ReLU activation)  
Dense Output Layer: 1 neuron  
Optimizer: Adam  
Loss Function: Mean Squared Error (MSE)  
