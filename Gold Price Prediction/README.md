# **Gold Price Prediction Model**  
This repository contains a gold price prediction model that uses various features such as SPX, USO, SLV, EUR/USD to predict the price of gold (GLD). The model is built using Active Learning techniques and can be used for investment purposes or for academic research.  
    
# **Active Learning**  
Active Learning is a machine learning technique that focuses on actively selecting the most informative samples for labeling in order to improve model performance. In traditional supervised learning, all of the samples in the training data are labeled and used to train the model. However, in Active Learning, the model is trained on a smaller set of samples that are selected based on their uncertainty or informativeness.  
  
By actively selecting the most informative samples for labeling, Active Learning can reduce the labeling effort required to train the model, while still achieving good performance. This can be particularly useful in situations where labeling data is time-consuming or expensive.  
  
In this repository, Active Learning is used to select the most informative samples for labeling and training the gold price prediction model. The model selects the samples that are most uncertain in its predictions and adds them to the training data for labeling. This process is repeated until the desired performance is achieved.  
  
# **Requirements**
In order to run the code in this repository, you will need the following:  
  
*Python 3.x  
Numpy  
Pandas  
Scikit-learn  
Data*  
The data used in this model was obtained from a financial data provider and covers the period from 2021 and 2008. The data includes daily values for the **SPX, USO, SLV, EUR/USD and GLD.**  
  
# **Model**  
The model is built using a Random Forest Regressor and employs Active Learning techniques to select the most informative samples for labeling. The model is trained on a dataset of 2290 samples and can be used to make predictions on new data.  
  
# **Usage**  
To use the model, simply run the gold_price_prediction.py file using a Python 3.x interpreter. The script will load the data, train the model, and make predictions on the test data.  
  
# **Contributions**  
Contributions to this repository are welcome. If you find any bugs or would like to suggest improvements, please open an issue or create a pull request.
