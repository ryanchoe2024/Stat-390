# Stat-390: Time Series modeling with Group 5
For the Fall 2023 capstone COVID-19 group project

Contributors: Sid Taneja & Ryan Choe

# Data
In the 'Data by Country' folder, you can find the original dataset labeled as "owid-covid-data.csv.zip." Also located in this folder are the "Data Preparation and Imputation" ipynb file and 12 csv files for the six countries our group focused on: USA, Brazil, Germany, China, Nigeria and Australia. The Data Preparation and Imputation file outlines our group's work when identifying each of the six countries, handling missing values and executing imputation methods. In this file, there is also work which manually split each country into a train (2020-2021) and test (2022) split in order to avoid data leakage.

# Other Folders
In the 'After Midterm Report' folder, you can find all of our preliminary Data Prepration steps, chronologically by week. Many of the steps attempted or covered are also included in each person's respective folders, explained later below. The 'EDA' folder contains our initial exploratory data analysis. You can find our Weekly Reports in our 'Weekly Reports' Folder.

# Inidividual Models
In order to run our code, you must run each individual .ipynb file for each person. Each person made 6 different models: ARIMA, Auto-ARIMA, Prophet Single, Propher Multiple, XGBoost and Keras LSTM in order to predict the target variable 'new_cases' for each country mentioned earlier. 

In the folder, 'Sid_Models', this contains all the models created by Sid Taneja. The file 'Data Preparation & PreProcessing' must be run first (this produces that data .csv files). In order to run each model, each .ipynb file named after each model can be run individually, and the results can be reproduced. In the folder, 'Ryan_Models', this contains all the models created by Ryan Choe. The file 'Data Preparation and Imputation' must be run first, which then produces all of the files in the 'Data' subfolder. Due to some technical difficulties, Ryan produced his LSTM model using Google Colab and then dowloaded and uploaded it as an .ipynb file to the repository. In order to run each model, each .ipynb file named after each model can be run individually, and the results can be reproduced. The folder, 'Rakin_Models' can be disregarded, as Rakin has withdrawn from the class.

# Cavetas and Remarks
Due to the announcement from Professor Shi, Sid and Ryan were not able to compare their model results with one another. Had there been more time, some further collaboration may have allowed for better optimal hyperparamter tuning and overall better accuracy.
