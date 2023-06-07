# Air Quality Index Prediction 
A Prediction Model to Predict Air Quality across different countries of the World


Pollutants of major public health concern include particulate matter, carbon monoxide, ozone, nitrogen dioxide and sulfur dioxide. Outdoor and indoor air pollution cause respiratory and other diseases and are important sources of morbidity and mortality. Hence, the essence of this study.

This project is aimed at building a prediction model for the prediction of Air Quality Index (AQI) for over 175 countries across the world. The project began with importing necessary libraries which would be applied throughout the project. Next was loading the data and looking at the features. Descriptive statistics was closely followed by checking out for missing data and filling them up.

Data visualization was next followed up with feature engineering and data splitting ready for the machine learning building process. Although Linear, TheilSen, Huber, Tweedie and KNearestNeighbor Regressions were applied, ensembling techniques such as RandomForest, Bagging, GradientBoosting, AdaBoost and ExtraTrees were also applied towards achieving a more effective prediction model. 

Behind the training process, the ExtraTree and RandomForest ensembling techniques were seen to produce the most effective models given their relatively low Root Mean Squared Error (RMSE). Hence, the ExtraTree Regression model was eventually adopted as the model for the final prediction of the global Air Quality Index (AQI) given Country name, City, CO, NO, O3 and PM2.5

This underscores the need to understand air quality index across various cities and put efforts in place towards lowering these index in order to address health-related conditions from air pollution, improve climate mitigation and help foster digital environmental sustainability.





