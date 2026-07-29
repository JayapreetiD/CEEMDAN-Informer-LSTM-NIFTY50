# Adaptive Hybrid Deep Learning for Daily Financial Time-Series Forecasting Using CEEMDAN, Informer, and LSTM

## Overview

This repository presents a hybrid deep learning framework for financial time-series forecasting using CEEMDAN, Informer, and LSTM. The project reproduces and evaluates the CEEMDAN–Informer–LSTM architecture on NIFTY 50 historical market data and compares its performance with standalone and hybrid forecasting models.

The framework combines signal decomposition with deep learning to improve forecasting accuracy by modelling high-frequency and low-frequency market dynamics separately.

---

## Objectives

- Preprocess NIFTY 50 historical market data
- Decompose financial time series using CEEMDAN
- Classify Intrinsic Mode Functions (IMFs)
- Forecast high-frequency IMFs using Informer
- Forecast low-frequency IMFs using LSTM
- Reconstruct the final stock price prediction
- Compare standalone and hybrid forecasting models
- Evaluate forecasting performance using multiple regression metrics

---

## Project Structure

```
CEEMDAN-Informer-LSTM-NIFTY50
│
├── data/
├── docs/
├── notebooks/
│   ├── preprocessing/
│   ├── standalone_models/
│   ├── hybrid_models/
│   └── evaluation/
├── results/
│   ├── metrics/
│   └── predictions/
└── README.md
```

---

## Workflow

1. Data Collection
2. Data Preprocessing
3. CEEMDAN Signal Decomposition
4. IMF Classification
5. Informer Prediction for High-Frequency IMFs
6. LSTM Prediction for Low-Frequency IMFs
7. Hybrid Forecast Reconstruction
8. Performance Evaluation

---

## Models Implemented

### Standalone Models

- LSTM
- Informer
- Transformer

### Hybrid Models

- CEEMDAN–LSTM
- CEEMDAN–Transformer
- CEEMDAN–Informer
- CEEMDAN–Informer–LSTM (Hybrid Model)

---

## Dataset

- **Market:** NIFTY 50
- **Target Variable:** Daily Closing Price
- **Frequency:** Daily
- **Data Processing:** Data cleaning, preprocessing, and CEEMDAN decomposition

---

## Evaluation Metrics

The forecasting models are evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)
- Mean Absolute Percentage Error (MAPE)
- Coefficient of Determination (R²)

---

## Technologies Used

- Python
- Pandas
- NumPy
- TensorFlow / Keras
- PyTorch
- Scikit-learn
- PyEMD (CEEMDAN)
- Matplotlib

---

## Repository Contents

- Data preprocessing notebooks
- Standalone forecasting models
- Hybrid forecasting models
- Performance evaluation notebooks
- Experimental results
- Prediction outputs
- Project documentation

---

## Research Contribution

This project investigates the effectiveness of combining CEEMDAN signal decomposition with Informer and LSTM models for forecasting financial time series. The implementation reproduces the hybrid forecasting framework on NIFTY 50 data and provides comparative performance analysis against multiple baseline models.

---

## Future Enhancements

- Adaptive rolling-window forecasting
- Online model updating
- Market regime detection
- Concept drift detection
- Real-time forecasting pipeline
- Explainable AI for financial forecasting

---

## References

This implementation is inspired by recent research on hybrid deep learning methods for financial time-series forecasting using CEEMDAN, Informer, and LSTM architectures. The original research paper provides the theoretical foundation for the hybrid modelling approach implemented in this repository.

---

## Author

**Jayapreeti D**

B.Tech Computer Science and Engineering (Artificial Intelligence & Data Science)

SASTRA Deemed University

GitHub: https://github.com/JayapreetiD

---

## License

This project is licensed under the MIT License.
