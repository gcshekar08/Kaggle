# Santander Value Prediction

### Project Overview

According to Epsilon research, 80% of customers are more likely to do business with you if you provide personalized service. Banking is no exception.

The digitalization of everyday lives means that customers expect services to be delivered in a personalized and timely manner… and often before they´ve even realized they need the service. Santander Group aims to go a step beyond recognizing that there is a need to provide a customer a financial service and intends to determine the amount or value of the customer&#39;s transaction. This means anticipating customer needs in a more concrete, but also simple and personal way. With so many choices for financial services, this need is greater now than ever before.

In this project, Santander Group is asking to help them identify the value of transactions for each potential customer. This is a first step that Santander needs to nail in order to personalize their services at scale.

### Install

This project requires  **Python 2.7**  and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

### Code

Template code is provided in the notebook ```santander_value_project.ipynb``` notebook file.

### Run

In a terminal or command window, navigate to the top-level project directory ```Kaggle/Santander Value Prediction/``` (that contains this README) and run one of the following commands:

```ipython notebook santander_value_project.ipynb```
```jupyter notebook santander_value_project.ipynb```

This will open the iPython Notebook software and project file in your browser.

##
## Data

The dataset used in this project is train.csv which is downloaded from link (https://www.kaggle.com/c/santander-value-prediction-challenge/data) unzip the file to get dataset. This dataset has the following attributes:

In this competition, Santander Group is asking us to help them identify the value of transactions for each potential customer. We are provided with an anonymized dataset containing numeric feature variables, the numeric target column, and a string ID column. Our task is to predict the value of target column in the test set.

The evaluation metric for this competition is Root Mean Squared Logarithmic Error. The data set consists of train.csv and test.csv