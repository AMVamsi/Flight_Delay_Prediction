# Flight Delay Prediction

## Objective
The main objective of the project is to predict the arrival delay of the flights using a two-stage model. If a flight is classified a delayed, then it is piplined with the regressor to predict the delay. To predict the flight delay real world weather data is used, as weather has a major impact on the delay.

## Classifers
* Decision Tree
* XG Boost
* Random Forest
* Logistic Regression

## Regressors
* Gradient Boosting
* XG Boost
* Random Forest
* Decision Tree

## Final Score Achieved
* RMSE-18.56
* MAE-14.15
* R2 SCORE-0.94\
*However, the score depends on the split ratio*

## Conclusion
The main objective of the project(to predict the arrival delay) is successfully completed by building a two-stage model. The classification model is used to classify the flights as delayed and not delayed. As the performance of the classifier is observed to be low, sampling techniques(SMOTE) where used to balance the class difference between the non-delayed flights and delayed flights. After using SMOTE the recall value of delayed data points increased. Random forest classifier is chosen for the pipeline as it had the highest recall score. Regression models are used to predict the arrival delay minutes for those flights which are classified as delay by the classifier. XG Boost regressor is chosen for the pipeline model as it had a high R2 Score(0.95), low RMSE (16.42), and low MAE(11.45)values. The pipeline model with the selected classifier and regressor performed with better accuracy.
