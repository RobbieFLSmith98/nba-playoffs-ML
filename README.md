# XGBoost Regression with Jupyter Notebook

This project demonstrates how I used an XGBoost Regressor on advanced NBA statistics for predicting NBA playoff wins using Python in a Jupyter Notebook environment. It uses the [nba_api](https://github.com/swar/nba_api) client to extract the data needed for this project
##  Overview

The notebook walks through the end-to-end process of:
- Extracting dataframes from the nba website using the nba api client
- Loading and preprocessing data
- Visualizing the data
- Splitting data into training and testing sets
- Training an XGBoost regression model
- Evaluating model performance using R² score
- Visualizing predictions and feature importance
- Predicting who is most likely to win 16 games

##  Technologies & Libraries

-[nba api](https://github.com/swar/nba_api)
-  Python 3.9.19
- Jupyter Notebook
- [XGBoost](https://xgboost.readthedocs.io/en/latest/)
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn (for visualization)

## Project Structure

### Install Dependencies
```bash
pip install nba_api
pip install xgboost pandas numpy seaborn matplotlib scikit-learn
```
