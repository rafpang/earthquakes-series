## Earthquake magnitude prediction

This was an attempt to predict the magnitude of an earthquake by its timestamp, latitude and longitude. Model is an XGBoost regressor tuned using Optuna.

Interesting Findings:

1. Magnitude and depth of earthquakes have decreased over the years
2. Magnitude follows a normal-like distribution, and baseline used is the mean magnitude
3. Lagging or differencing the features did not manage to increase model performance, may need to try other features


Source of data: https://www.kaggle.com/datasets/greegtitan/indonesia-earthquake-data
