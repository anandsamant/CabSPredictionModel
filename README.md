# CabSPredictionModel
This Repository have Machine Learning project in which I had make a model to predict the Cabs weekly ride for the cab driver to fulfills its needs. DataSet is taken from internet. 

I also combine this model to an HTML page using pickle and flask module/libraries of Python.

# MLR.py
It is machine learning model file (Uses Linear Regression)
# app.py
It uses flask and pickle modules to connect Index.html to MLR.py

# Model Limitation : According to taxi.csv
It asks four things from user and predict number of weekly rides to driver.
1. PricePerWeek : ranges from (( 10 to 110 ))
2. Population : ranges from (( 1500000  to 1850000 ))
3. Monthlyincome : ranges from (( 5500 to 17000 ))
4. Averageparkingpermonth : ranges from (( 50 to 200 ))

For starting the file:-  Use (( python app.py ))  in terminal in that folder.

Requirements :
Python , Flask , Numpy , Scipy , Scikit-learn , Pandas.
