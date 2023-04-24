# Sales-Analysis-Using-Python
To analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

Questions ---
1)What was the best month for sales? How much was earned that month?
2)What city sold the most product?
3)What time should we display advertisemens to maximize the likelihood of customer’s buying product?

Approach-----
1) Data cleaning 
-Drop NaN values from DataFrame
-Removing rows based on a condition
-Change the type of columns (to_numeric, to_datetime, astype)

2) Analyis
-Concatenating multiple csvs together to create a new DataFrame (pd.concat)
-Adding columns
-Parsing cells as strings to make new columns (.str)
-Using the .apply() method
-Using groupby to perform aggregate analysis
-Plotting bar charts and lines graphs to visualize our results
-Labeling our graphs
