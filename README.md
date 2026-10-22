# Daily Rainfall Prediction Using LSTM

## Project Overview
This project predicts daily rainfall using an LSTM (Long Short-Term Memory) neural network and the IMD rainfall dataset for 2022.

## Dataset
- Source: Kaggle — IMD Rainfall Dataset 2022
- Selected district: Coimbatore, Tamil Nadu
- Data: Daily rainfall measurements

## Methodology
1. Load and preprocess rainfall data.
2. Handle missing values and normalize rainfall measurements.
3. Create input sequences using the previous 7 days.
4. Train an LSTM model.
5. Evaluate the model using MAE and RMSE.
6. Plot actual versus predicted rainfall.
7. Predict rainfall for an unseen date.

## Model Evaluation
- MAE: 3.7543 mm
- RMSE: 5.8159 mm

## Tools and Technologies
Python, Google Colab, Pandas, NumPy, Scikit-learn, Matplotlib, TensorFlow/Keras.

## Note
The prediction for January 1, 2023, is a model-generated estimate, not an actual recorded rainfall measurement.
