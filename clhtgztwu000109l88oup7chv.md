---
title: "Project Number #12 :Medical Insurance Cost Prediction"
seoTitle: "Machine Learning Projects"
seoDescription: "Learn how to predict medical insurance costs using machine learning. Explore the code implementation, dataset analysis, and model training."
datePublished: Thu May 18 2023 18:33:30 GMT+0000 (Coordinated Universal Time)
cuid: clhtgztwu000109l88oup7chv
slug: medical-insurance-cost-prediction
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/NFvdKIhxYlU/upload/183ed6e0533e45a4f7beb5d75d653189.jpeg
tags: python, machine-learning, model

---

## Introduction

In the realm of medical insurance, accurately predicting insurance costs plays a vital role for both individuals and insurance companies. In this blog post, we will walk through a code implementation using Python and sci-kit-learn that demonstrates how to train a linear regression model to predict the cost of medical insurance based on various factors such as age, sex, BMI, number of children, smoker status, and region.

## Data Collection and Analysis:

The first step is to collect and analyze the insurance dataset. The code snippet imports necessary libraries such as NumPy, Pandas, Matplotlib, and Seaborn. It then reads the insurance dataset from a CSV file using the Pandas library. The dataset consists of columns like age, sex, BMI, children, smoker, region, and charges, which represent different attributes related to medical insurance.

## Data Preprocessing:

To prepare the data for training the model, some preprocessing steps are performed. The code snippet includes visualizations using Seaborn to analyze the distribution and relationships between the variables in the dataset. Histograms and count plots are used to explore variables like age, sex, BMI, children, smoking, region, and charges. These visualizations provide insights into the data distribution and help in understanding any patterns or trends

## Encoding Categorical Variables:

Since the linear regression model requires numerical inputs, the categorical variables (sex, smoker, and region) are encoded using numerical representations. The code replaces the categorical values with corresponding numerical values, allowing the model to process the data correctly.

## Splitting the Data:

To evaluate the model's performance, the dataset is split into training and testing sets using the train\_test\_split function from sci-kit-learn. The X variable contains the features (age, sex, BMI, children, smoker, region), and the Y variable contains the target variable (charges). The split is done with a test size of 20% of the total data.

## Model Training and Evaluation:

The code creates a Linear Regression object and fits the training data to the model using the fit method. After training, the model predicts the insurance charges for both the training and testing datasets. The R-squared metric is used to evaluate the model's performance. R-squared measures how well the model fits the data, with values closer to 1 indicating a better fit.

## Building a Predictive System:

Finally, the code demonstrates how to use the trained model to make predictions on new data. An example input\_data consisting of age, sex, BMI, children, smoker, and region is provided. The input data is converted into a numpy array, reshaped, and fed into the model's prediction method. The predicted insurance cost is then displayed.

## Conclusion:

In this blog post, we explored how to train a linear regression model to predict the cost of medical insurance based on various factors. By understanding the dataset, performing data preprocessing, encoding categorical variables, splitting the data, and evaluating the model, we gained insights into the insurance cost prediction process. With this knowledge, you can now apply similar techniques to your medical insurance datasets and leverage machine learning to make accurate predictions in the field of healthcare insurance.

To access the complete code implementation and further explore the project, you can visit my GitHub repository: [**GitHub**](https://github.com/AyeshaIrshad1337). The specific notebook for this project can be found here: [**Medical Insurance Cost Prediction Notebook**](https://github.com/AyeshaIrshad1337/ActIve_Learning_Projects/blob/main/medical-insurance-cost-prediction.ipynb).

You can also find this project on Kaggle, along with the dataset and additional resources. Check it out here: [**Kaggle**](https://www.kaggle.com/code/ayeshairshadcoder/medical-insurance-cost-prediction). Feel free to explore my Kaggle profile for more data science projects: [**Kaggle Profile**](https://www.kaggle.com/ayeshairshadcoder).

Happy learning and predicting medical insurance costs!