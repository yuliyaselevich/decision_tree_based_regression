# Joint AMSR-E/CloudSat analysis and extrapolation of curtain-like swath of the CloudSat radar (~ 1.3 km wide)
CloudSat is a satellite mission operated by NASA's Jet Propulsion Laboratory, designed to study cloud and precipitation properties using its Cloud Profiling Radar.
AMSR-E (Advanced Microwave Scanning Radiometer for EOS) is an instrument onboard NASA's Aqua satellite, designed to measure global precipitation, water vapor, sea surface temperature, sea ice, and snow cover.
Both satellites play a crucial role in Satellite Meteorology, detecting and tracking tropical cyclones on Earth, enabling better understanding and prediction of these dangerous storms.
## Overview
The project focuses on correlating AMSR-E 36-GHz and 89-GHz brightness temperature (sensitive to ice particles lofted by convection) with CloudSat Cloud Profiling Radar (CPR) echo characteristics as well as predicting Echo Top Height.
## Research Goals
* Correlate AMSR-E 89-GHz brightness temperature with CloudSat radar echo top height for tropical cyclones.
* Investigate other AMSR-E channels (e.g., 37 GHz sensitive to liquid particles) and their relationship with CloudSat data for additional information on hurricane structures.
* Utilize statistical analysis, such as multiple linear regression and decision tree based regression, to quantify the relationships and extend the reach of CloudSat radar beyond its narrow swath.
## Findings
1. The combination of AMSR-E brightness temperatures and CloudSat radar echo top height provides a viable tool for extrapolating CloudSat information beyond its narrow swath.
2. Multiple regression of 89 GHz & 37 GHz channels shows promising results, indicating the potential to include more channels at lower frequencies.
## Model Evaluation
The model that showed the best results for hurricane characterization was the XGBoost regressor. The model was evaluated with the following performance metrics:
* Root Mean Squared Error (RMSE): 1158.62
* Mean Absolute Error (MAE): 738.45
* R-squared (R2): 0.8989
These evaluation metrics indicate that the XGBoost regressor provided a highly accurate and robust prediction of Echo Top Height using the combined CloudSat and AMSR-E data.
![Alt XGB Regressor Performance](https://github.com/yuliyaselevich/decision_tree_based_regression/blob/main/images/xgb.png)
### Methods Used
* Descriptive and inferential statistics
* EDA
* Data Visualization
* Predictive Modeling
* Machine Learning
* Decision Trees
* Gradient Boosting
### Technologies
* Python
* Pandas
* Seaborn
* Matplotlib
* Scipy.stats
* Numpy
* Scikit-learn
* XGBoost Regressor
* Random Forest Regressor
* LightGBM Regressor
## Featured Notebooks/Reports
* [Exploratory Data Analysis/ Preprocessing](https://github.com/yuliyaselevich/decision_tree_based_regression/blob/main/notebooks/preprocessing_eda.ipynb)
* [Modeling](https://github.com/yuliyaselevich/decision_tree_based_regression/blob/main/notebooks/modeling.ipynb)
## Contact
* [LinkedIn](https://www.linkedin.com/in/yuliyaselevich/)
