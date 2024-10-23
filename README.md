# **Gold Percentage Change Forecast**

**Description:**

Gold price prediction using various preprocessing techniques and models, including XGBoost, Prophet, VAR, and SARIMAX, for a Beltone competition focused on forecasting percent changes in gold prices.

**INTRODUCTION:**

This notebook showcases my approach to a gold price prediction competition hosted by Beltone, where the task is to forecast the percent change in gold prices for the next day. To achieve this, I explored multiple preprocessing techniques, such as Recursive Feature Elimination (RFE), Sequential Feature Selection (SFS), Principal Component Analysis (PCA), and multicollinearity reduction.

For modeling, I used the XGBoost regressor with different boosters, including a Grid Search and a Dart booster. Additionally, I experimented with residual forecasting to optimize my metrics, using both XGBoost and Prophet. I also applied the VAR model, initially for price prediction, then for percent change. Finally, I incorporated the SARIMAX model to forecast the percent change in gold prices.
