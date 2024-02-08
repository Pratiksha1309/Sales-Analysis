# Sales-Analysis
a Python Project for Exploratory Data Analysis (EDA) of Sales Dataset. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

## Setup

To access all of the files, fork this repo and then clone it locally. 

The other option is to click the green "clone or download" button and then click "Download ZIP". You then should extract all of the files to the location you want to edit your code.

Installing Jupyter Notebook: https://jupyter.readthedocs.io/en/latest/install.html <br/>
Installing Pandas library: https://pandas.pydata.org/pandas-docs/stable/install.html 

## Background Information:

In this project, Python Pandas & Python Matplotlib is used to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc. 

Task1: cleaning the data. Tasks during this section include:
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

Task2: adding the required columns after reading the questions 
-Columns can also be added later.

Task3:
Once the data is cleaned up a bit, the data exploration should be done. In this section there are 5 high level business questions related to the data:
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product sold the most? Why do you think it sold the most?

To answer these questions, many different pandas & matplotlib methods can be used. They include:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize the results
- Labeling the graphs
