# Home_Sales
Data
The analysis is performed on the "home_sales_revised.csv" dataset. This dataset contains information about various aspects of home sales, including sale price, number of bedrooms, bathrooms, floors, square footage, view rating, and more.

Analysis
The analysis is carried out in multiple steps using SparkSQL queries:

Calculate the average price for four-bedroom houses sold each year.
Determine the average price of homes with three bedrooms and three bathrooms for each year they were built.
Find the average price of homes with three bedrooms, three bathrooms, two floors, and a minimum size of 2,000 square feet for each year they were built.
Compute the average "view" rating for homes costing $350,000 or more.
Cache the home sales data and analyze the query runtime difference.
Store the data in a partitioned Parquet format and analyze query runtime on the Parquet data.
Results
The results of the analysis are obtained by running SparkSQL queries on the home sales data. The insights gained from these queries provide information about average prices, view ratings, and other relevant metrics for different subsets of homes.

Usage
Clone this repository to your local machine.
Replace "path_to_your_home_sales_revised.csv" and "path_to_store_formatted_parquet_data" with actual paths in the provided code.
Run the code in a PySpark environment, such as Jupyter Notebook.
Review the outputs of the SparkSQL queries to see the results of the analysis.