# Sales_Data_Analysis_Pandas
Set of real world data science tasks completed using the Python Pandas library.

## How to Use the Notebook
To access all of the files I recommend you fork this repo and then clone it locally. Instructions on how to do this can be found here: https://help.github.com/en/github/getting-started-with-github/fork-a-repo

The other option is to click the green "clone or download" button and then click "Download ZIP". You then should extract all of the files to the location you want to edit your code.

## Backgroud Information: 
Used Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

## Data Cleaning
Tasks during this section include:
- Dropping NaN values from DataFrame
- Removing rows based on a condition
- Changing the type of columns (to_numeric, to_datetime, astype)

## Data Exploration
After cleaning up the data, data exploration is done. In this section I explored 5 high level business questions related to the data:
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product sold the most? Why it was sold the most?

To answer these questions I walked through many different pandas & matplotlib methods. They include:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs
