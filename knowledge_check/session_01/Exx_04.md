# Knowledge Check
*Answer the following questions to see what you've learned.*


1. What is a risk of having null values in a numeric column?
    * DAX expressions that SUM data will be incorrect.
    * DAX expressions that MAX data will be incorrect.
    * **DAX expressions that AVERAGE data will be incorrect.**
    >AVERAGE takes the total and divides by the number of non-null values. If NULL is synonymous with zero in the data, the average will be higher than the accurate average.

2. If you have two queries that have different data, but you want to concatenate the results into one query with all the combined rows, which operation should you perform?
    * **Append**
    * Merge
    * Combine Column
    >Append will take two tables and combine it into one query. The combined query will have more rows while keeping the same number of columns.

3. Which of the following selections are not best practices for naming conventions in Power BI?
    * Rename columns to have spaces in them.
    * **Abbreviate column names.**
    * Replace values that have integers with human readable results.
    >Abbreviations lead to confusion because they are often overused or not universally agreed on.