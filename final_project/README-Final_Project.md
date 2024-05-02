# Final Project: Predicting Property Damage in California with Historical Storm Data

<i>
Dani Le, Efren Lopez, Luis Otero
<br>
BSAN 6070
<br>
April 30, 2024
<br>
</i>
<br>

GitHub Links:
*   Dani: https://github.com/ledani-bu/ml
*   Efren: https://github.com/efrenlop01/
*   Luis: https://github.com/otero106/BSAN6070

## Description

The profound impact of the increased meteorological events, worsened by global climate change, emphasizes the need to effectively prepare for the financial repercussions of severe weather at an infrastructure level. In this case study, we focused on utilizing historic California storm data, provided by the National Center for Environmental Information, to predict the amount of future property damage. We looked specifically at severe weather episodes occurring in the inland counties and public forecast zones of California, as defined by the National Weather Service. This project entails: data exploration, data cleaning, visualizations, building three models with Random Forest Regression, Gradient Boosting Regression, and XGBoost Regression, and testing the final model with a new record.

<br> <br>
<img src = "https://s.abcnews.com/images/US/california2-gty-ml-240206_1707222412591_hpMain_16x9_992.jpg" alt = "image" width = 300 height = "auto">

## Python Libraries Needed

* Pandas
* NumPy
* Matplotlib
* Plotly
* os
* glob
* Seaborn
* Scikit-Learn
* Scipy
* Meteostat
* Datetime

## Software

* Python
    * Version 3.9.13
* MS Visual Studio Code

## Data Sources

* [National Center for Environmental Information: Storm Events Database](https://www.ncdc.noaa.gov/stormevents/)
* [CA Dept. of Finance](https://dof.ca.gov/forecasting/demographics/estimates-e1/)
* [US Census Bureau](https://www2.census.gov/programs-surveys/popest/datasets/)
* [usa.com](http://www.usa.com/rank/california-state--land-area--city-rank.htm#google_vignette)
* [National Weather Service](https://www.weather.gov/gis/ZoneCounty)
* [Open Data Soft: US County Boundaries](https://public.opendatasoft.com/explore/dataset/us-county-boundaries/table/?flg=en-us&disjunctive.statefp&disjunctive.countyfp&disjunctive.name&disjunctive.namelsad&disjunctive.stusab&disjunctive.state_name)

## Installation and Executing Program

1. Download the Python Notebook that is located in the same folder as this README
2. Use the following URL to access the folder containing the storm data
    * https://lmu.box.com/s/00yi35oapc75aoc900c05evifyli5imh
3. Download other data from data sources folder in repository
4. Open the notebook in MS Visual Studio Code
5. Make sure to have all data files in the same folder as the Jupyter Notebook
6. Replace the file paths with the pathnames of the files in your folder
7. Select "Run All" at top

## Acknowledgments/References

* Professor Brahma(https://github.com/ArinB)
* [How to Combine Multiple CSV Files Using Python for Your Analysis](https://medium.com/@stella96joshua/how-to-combine-multiple-csv-files-using-python-for-your-analysis-a88017c6ff9e)
* [EDA | Exploratory Data Analysis in Python](https://www.geeksforgeeks.org/exploratory-data-analysis-in-python/)
* [Encoding Cyclical Features for Deep Learning](https://www.kaggle.com/code/avanwyk/encoding-cyclical-features-for-deep-learning)
* [ML One Hot Encoding](https://www.geeksforgeeks.org/ml-one-hot-encoding/)
* [scipy.stats.zscore](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.zscore.html)
* [US County Boundaries](https://public.opendatasoft.com/explore/dataset/us-county-boundaries/export/?flg=en-us&disjunctive.statefp&disjunctive.countyfp&disjunctive.name&disjunctive.namelsad&disjunctive.stusab&disjunctive.state_name&sort=stusab&refine.statefp=06)
* [Get Temperature Data by Location with Python](https://towardsdatascience.com/get-temperature-data-by-location-with-python-52ed872dd621)
* [Regression Metrics for Machine Learning](https://machinelearningmastery.com/regression-metrics-for-machine-learning/)
* [The Most Common Machine Learning Regression Algorithms for Data Science](https://readmedium.com/en/https:/medium.com/swlh/types-of-regression-algorithms-eb792039a554)
* [Random Forest Regression](https://towardsdatascience.com/random-forest-regression-5f605132d19d)
* [Feature Selection with Random Forest](https://www.yourdatateacher.com/2021/10/11/feature-selection-with-random-forest/)
* [Regression Metrics for Machine Learning](https://machinelearningmastery.com/regression-metrics-for-machine-learning/)
* [Hyperparameter Tuning Random Forest in Python](https://readmedium.com/en/https:/towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74)
* [How, When, and Why Should You Normalize / Standardize / Rescale Your Data?](https://towardsai.net/p/data-science/how-when-and-why-should-you-normalize-standardize-rescale-your-data-3f083def38ff)
* [sklearn.ensemble.GradientBoostingRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html)
* [XGBoost for Regression](https://www.geeksforgeeks.org/xgboost-for-regression/)
