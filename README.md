# Project Name    Covid_Cases_Prediction 
> Outline a brief description of your project.
To predict the covid cases.
The r2 score on test data set need to be improved.


## Table of Contents
* [General Info](#general-information)Covid_Cases_Prediction
* [Technologies Used](#technologies-used)CNN,PCA,XGBoost,Random Forest,Linear regression,sklearn
* [Conclusions](#conclusions) Achieved r2 score on test data set is 0.97
* [Acknowledgements](#acknowledgements) By hyper parameter tuning XGBregressor model gave r2 score of 0.97

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?
   
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis  Applied GridSearchCV(xgb_model, param_grid=params,cv=5, verbose=1) got r2 score of 0.97.
- Conclusion 2 from the analysis  RandomForestRegressor(n_estimators= 600, max_depth= 70, max_features= 10, random_state= 42, oob_score=True)
                                    got r2 score of 0.95.

- Conclusion 3 from the analysis  But by using PCA the r2 score in test data set is reduced.
- Conclusion 4 from the analysis  XGBregressor with hyper parameter tuning gave the best result.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@https://github.com/sanghamitraa] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->