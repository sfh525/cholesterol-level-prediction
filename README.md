# Cholesterol Level Prediction

## Credits
Credits goes to my teammates for contributing to this project: 
1. Hafid Sasayuda Ambardi
2. Nabila Yumna Naafi'a
   
## Intro
The competition presents a problem from medical data, where teams' compete to accurately predict the exact a patient's level of cholesterol. This was part of a national competition hosted by Bandung Institute of Technology.

## Dataset
The dataset provided contained the following features: 
* Unhealthy lifestyle (like consuming foods with saturated fat)
* Age
* Sex/Gender
* Family or Lineage
* Comorbidity
* Medication for other disease.
* And other factors such as obesity, diabetes, or other complications.
There were 2 given dataset, data1, and data2. In the report, it can be seen that the data2 yields better metrics due to more complete information contained within the data. 


## Approach
After the data has been cleaned and preprocessed with various methods, we tried both regression and classification approach, using XGBoost regressor and XGBoost classifier repesctively. 

## Result and Potential Improvements
* The regression approach the best score of RMSE 11.88, while the F1 score was around 65%.
  
## Runnning the Notebook
This notebook can be run in any environment you would like. Make sure to match the directory of the dataset and install all the necessary dependencies. 
