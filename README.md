# Home Sales Data Analysis with PySpark

## Overview
In this project, we will be using PySpark to analyze a dataset containing information about home sales. We will perform various SparkSQL operations to answer specific questions related to the dataset and explore its insights.

## Instructions
1. **Rename the Jupyter Notebook file** `Home_Sales_starter_code.ipynb` to `Home_Sales.ipynb` to start working on the project.

2. **Import the necessary PySpark SQL functions** to enable SparkSQL operations for this assignment.

3. **Read the dataset** `home_sales_revised.csv` provided in the starter code into a Spark DataFrame.

4. **Create a temporary table** called `home_sales` using the DataFrame to facilitate easy querying.

5. **Answer the following questions** using SparkSQL:
   - What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
   - What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
   - What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
   - What is the "view" rating for homes costing more than or equal to $350,000? Determine the runtime for this query and round off your answer to two decimal places.

6. **Cache the temporary table** `home_sales` to optimize query performance for subsequent operations.

7. **Check if the temporary table** `home_sales` **is successfully cached**.

8. **Using the cached data, run the query** that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime for this query and compare it to the uncached runtime from step 5d.

9. **Partition the formatted Parquet home sales data by the** "date_built" **field**.

10. **Create a temporary table for the Parquet data**.

11. **Using SparkSQL, run the query** that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime for this query and compare it to the uncached runtime from step 5d.

12. **Uncache the** `home_sales` **temporary table** to release memory resources.

13. **Verify that the** `home_sales` **temporary table is successfully uncached** using PySpark.

## Conclusion
By completing the tasks above, we will gain valuable insights into the home sales data using PySpark and SparkSQL operations. We'll be able to answer important questions related to the dataset and make data-driven decisions based on our analysis. Remember to run each task step-by-step to ensure accurate results and efficient data processing.
