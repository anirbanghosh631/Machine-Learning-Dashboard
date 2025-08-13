## Project Objective
The project aims to develop a reliable method for forecasting meteorological drought in Bankura district, West Bengal, using the Standardized Precipitation Index (SPI) and Long Short-Term Memory (LSTM) deep learning model. The goal is to improve drought prediction accuracy to aid in agricultural planning and water resource management.Project Description
The study focuses on identifying and forecasting drought conditions using historical precipitation data. SPI is employed to quantify drought severity over different accumulation periods, and LSTM is used to forecast future drought conditions based on SPI time series. The approach emphasizes short-term prediction (1-month lead time) for timely decision-making.
 
## Project Description
The study focuses on identifying and forecasting drought conditions using historical precipitation data. SPI is employed to quantify drought severity over different accumulation periods, and LSTM is used to forecast future drought conditions based on SPI time series. The approach emphasizes short-term prediction (1-month lead time) for timely decision-making.



## Study Area and Dataset
The study area is Bankura district, West Bengal, India, a drought-prone region despite receiving ~1400 mm annual rainfall due to erratic distribution. Data used includes monthly rainfall from 1981 to 2020, collected at coordinates 23.75°N, 87.75°E from the India Meteorological Department (IMD) website.

## Methodology

1. SPI Calculation: Rainfall series fitted to gamma distribution, cumulative probability calculated, and transformed into SPI for multiple timescales (1, 3, 6, 9, 12 months).

2. Data Preparation: SPI-6 series used for modeling due to effective noise reduction.

3. Modeling: LSTM with 4 hidden layers, dropout regularization, and Adam optimizer trained on 70% of data, tested on 30%.

4. Performance Metrics: RMSE, MSE, NRMSE, R², and Kendall rank correlation used for evaluation.

## Results and Discussion
The LSTM model for SPI-6 achieved RMSE = 0.58112, R² ≈ 65.1%, and Kendall rank correlation = 0.81339 for 1-month lead-time prediction. Forecasted drought patterns closely matched observed data, though minor underestimations occurred in extreme wet conditions. The results confirm that combining SPI with LSTM provides accurate short-term drought forecasts, which can significantly help in proactive drought management.











