# Estimation-of-C02-Emission-by-vehicles
Deploy a ML model to calculate the CO2 Emission by vehicles

Dataset:
It is almost a cleaned dataset with no missing values
This dataset is taken From kaggle which is issued by a Cannda Government.
This dataset contains 7385 rows and 12 columns.
The detailed description along with a link to download it is given below:
https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles


ML model:
The code provided has a detailed analysis using matplotlib and seaborn libraries.
Some of the attributes for which the target has very less dependency has been removed to
avoid unnecessary complications.
First the model is evaluated with a linear regression model but the model overfits the data with
the accuracy of 99%.
Hence the overcome the overfitting issues Lasso model has been used with the accuracy of 93%
and resolving the overfitting issue.
The detailed explanation is provided in the code section.

Libraries:
pandas, matplotlib, seaborn,opendatasets,sklearn and numpy

