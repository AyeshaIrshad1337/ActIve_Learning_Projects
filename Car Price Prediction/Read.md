Active Learning for Car Prediction Model This project implements active learning using linear regression on a car prediction model. The aim is to improve the accuracy of the model by actively selecting the most uncertain samples and adding them to the training data.

Data The data used in this project contains information about cars and their selling price. The data has 301 rows and 9 columns, including the following features:

Age Present_Price Kms_Driven Owner Fuel_Type_Diesel Fuel_Type_Petrol Seller_Type_Individual Transmission_Manual The target variable is the selling price of the cars.

Algorithm The initial model is a linear regression model. The model is fit on the data and its score is calculated. In each iteration of the active learning loop, the model is updated by adding the most uncertain samples identified by a random forest model. The loop runs for 10 iterations and the model score is printed after each iteration.

Result The result of the active learning process shows that the accuracy of the model improves after each iteration as the most uncertain samples are added to the training data.

Usage To run this project, you will need to install the following packages:

pandas numpy scikit-learn You will also need to provide the data files car_data from kaggle.

Conclusion This project demonstrates the effectiveness of active learning in improving the accuracy of a linear regression model for car prediction. By actively selecting the most uncertain samples and adding them to the training data, the model can continuously improve its accuracy
