<h2> Improving Solar Radiance Data Resolution with Convolutional Neural Nets </h2>

This repository contains my submission for the course EAEE4000ML Machine Learning for Environmental Engineering and Science. This study investigates the capacity for machine learning techniques to accurately model on-site pyranometers with low resolution public weather data. In particular, this project evaluates the performance of conventional and long short-term memory neural network models across four different solar PV sites in New Jersey and New York.

Data is downloaded and processed through the data_downloads.ipynb, data_downloads_2.ipynb, and data_processing.ipynb. The resulting NetCDF datasets then saved in the data folder. The original data used An additional layer of processing occurs in the utils.py file to prepare predictors and predictants. The data has not been included by request from their sources.

The four models can be located in the following notebooks:

- Artificial Neural Network with Mean Squared Error Loss Function
    - model_ann_mse.ipynb 
- Artificial Neural Network with Quantile Loss Function
    - model_ann_ql.ipynb
- Long Short-Term Memory Model with Mean Squared Error Loss Function
    - model_lstm_mse.ipynb
- Long Short-Term Memory Model with Quantile Loss Function
    - model_lste_ql.ipynb
