I used Python Pandas and Python Matplotlib to answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.
I started by cleaning my data. Tasks during this section include:

* Drop NaN values from DataFrame
* Removing rows based on a condition
* Change the type of columns (to_numeric, to_datetime, astype)

Once I had cleaned up my data a bit, I moved to the data exploration section. In this section i explore 5 high level business questions related to our data:

* What was the best month for sales? How much was earned that month?
* What city sold the most products?
* What time should we display advertisements to maximize the likelihood of customer’s buying a product?
* What products are most often sold together?
* What product sold the most? Why do you think it sold the most?
To answer these questions I walked through many different pandas & matplotlib methods. They include:

* Concatenating multiple csvs together to create a new DataFrame (pd.concat)
* Adding columns
* Parsing cells as strings to make new columns (.str)
* Using the .apply() method
* Using groupby to perform aggregate analysis
* Plotting bar charts and lines graphs to visualize my results
* Labeling my graphs
