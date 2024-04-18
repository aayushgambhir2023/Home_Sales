***Module 22 Challenge***
Here's an overview of the tasks completed in the Module 22 Challenge:

1. **Importing Necessary Libraries**: Imported the required PySpark SQL functions for the assignment.
2. **Reading Data**: Read the home sales data from the provided CSV file into a Spark DataFrame.
3. **Creating Temporary Table**: Created a temporary table called "home_sales" using the DataFrame.
4. **Answering Questions with SparkSQL**:
   - Calculated the average price for a four-bedroom house sold for each year.
   - Determined the average price of a home for each year it was built, with three bedrooms and three bathrooms.
   - Found the average price of a home for each year it was built, with specific criteria like bedrooms, bathrooms, floors, and square footage.
   - Calculated the average price of a home per "view" rating having an average home price greater than or equal to $350,000.
5. **Caching Temporary Table**: Cached the temporary table "home_sales" to improve query performance.
6. **Checking Cached Table**: Verified that the temporary table "home_sales" was successfully cached.
7. **Running Query on Cached Table**: Executed the query on the cached temporary table and calculated the runtime.
8. **Partitioning Data**: Partitioned the home sales dataset by the "date_built" field and formatted it as Parquet data.
9. **Creating Temporary Table for Parquet Data**: Created a temporary table for the Parquet data.
10. **Running Query on Parquet Data**: Executed the query on the Parquet temporary table and calculated the runtime.
11. **Uncaching Temporary Table**: Uncached the temporary table "home_sales" and verified the uncaching.
12. **Comparison of Runtimes**: Compared the runtime of the query executed on the Parquet data with the runtime of the same query executed on the cached temporary table "home_sales".

These tasks were completed according to the requirements, ensuring that all queries were executed correctly and the runtime was calculated accurately for comparison.
