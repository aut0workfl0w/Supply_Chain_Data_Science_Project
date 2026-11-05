# Loan Dataset

The public dataset chosen for this Data Science Project is a Loans Dataset from kaggle:
https://www.kaggle.com/datasets/itssuru/loan-data


To start off the data will need to go through the process of ETL so it becomes prepared for analysis. The first step in ETL is Extract which involves pulling data from a variety of data sources and may be in various forms such as structured (databases), semi-structured (JSON) or unstructured (emails) data. In this scenario, the public dataset from Kaggle is in CSV format and has been saved locally.

For this project I will be coding in python because that's primarily the coding language used at my Organisation. I'll be using Google Colab, because it provides the python environment along with the datascience libraries which will be using in this project. Also, there is no set required and can be used directly in the browser. We start off by importing pandas and data science library primarily used for data preprocessing (McKinney, 2011). For this project we'll be using it to manipulate, clean and analyse the data.

import pandas as pd 
df = pd.read_csv("sales_orders.csv")

1) Extract: The above code imports Pandas library to read the CSV file and name the dataframe to df. This is the Extract part of the ETL.
