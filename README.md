🌿 Smart Climate Controller: Deep Learning Meets Fuzzy Logic

📌 Overview
This project presents a hybrid intelligent system that forecasts greenhouse climate variables using an LSTM-based neural network and applies fuzzy logic to make human-like control decisions. The goal is to emulate real-world greenhouse automation by combining the predictive power of deep learning with the interpretability of fuzzy reasoning.


🎯 Objective
To design and implement a lightweight yet professional-grade system that can:

- Forecast greenhouse temperature and humidity values 30–60 minutes into the future using time-series deep learning.

- Use those forecasts in a fuzzy inference system to simulate climate control actions (e.g., adjusting fans, lights, humidifiers).

- Provide clear, interactive visualizations of environmental conditions, model behavior, and control logic decisions.


🧪 Dataset
We use the publicly available Greenhouse Sensor Dataset, which contains environmental sensor data collected at 10-minute intervals, including:

- Greenhouse temperature (°C)

- Humidity (%)

- Illuminance (lux)

- VOCs and eCO₂ (optional for expansion)


🧠 Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)

- Keras (LSTM model for multivariate time series forecasting)

- Scikit-Fuzzy (fuzzy logic control system)

- Streamlit (Future update: live dashboard interface)


🚀 Project Highlights
- Fully modular codebase with components for preprocessing, forecasting, fuzzy reasoning, and visualization.

- Intelligent decision-making under uncertainty using linguistic fuzzy rules.

- Clean user interface for understanding climate trends and system behavior.

- Foundation for real-time greenhouse automation systems or IoT extensions.