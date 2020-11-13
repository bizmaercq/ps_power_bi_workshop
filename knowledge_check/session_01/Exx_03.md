# Knowledge Check
*Answer the following questions to see what you've learned.*


1. What type of expression do you use to extract data from Microsoft SQL Server?
    * DAX
    * **T-SQL**
    * MDX
    >T-SQL is the query language that you would use for SQL Server.

2. You're creating a Power BI report with data from an Azure Analysis Services Cube. When the data refreshes in the cube, you would like to see it immediately in the Power BI report. How should you connect?
    * Import
    * **Connect live**
    * Direct Query
    >This will reflect cube changes immediately.

3. What can you do to improve performance when you are getting data in Power BI?
    * **Do some calculations in the original data source**
    * Only pull data into the Power BI service, not Power BI Desktop
    * Use the Select SQL statement in your SQL queries when you are pulling data from a relational database.
    * Combine date and time columns into a single column
    >Power Query and Power Query Editor are built to allow you to process the data, however, the processing power required to do this may lower performance in other areas of your reports. It is good practice to process as much as possible in the native data source.