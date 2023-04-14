# Portfolio-projects
Hello there, this is a collection of data science and data analytics projects created! 

1. COVID Data Analysis: The analysis was performed using SQL queries and the following skills were employed: Joins, CTE's, Temp Tables, Windows Functions, Aggregate Functions, and Creating Views.

The analysis focused on exploring various aspects of the COVID pandemic, including the percentage of population that contracted COVID, percentage death rate, countries with the highest infection rates, countries with the highest percentage of deaths and highest death counts, and grouping data by continents with the highest death counts and global numbers. In addition, a rolling count was created that adds up the total number of people vaccinated daily, and the total percentage of population vaccinated was calculated.

Data visualization was done on Tableau: https://public.tableau.com/app/profile/lena.chen2238/viz/CovidData_16743832113750/Dashboard1?publish=yes


The data used in the analysis is available from www.ourworldindata.org/covid-deaths. To reproduce the analysis or explore the data further, you can use the SQL queries provided in the repository. 

--------------------------------------------------------------------------------------------------------------------------------------
2. SQL Data Cleaning: The objective was to clean and standardize a dataset using SQL queries. Skills employed: CONVERT, SELF JOIN, COALESCE, ALTER TABLE, SUBSTRING, SPLIT_PART, CASE, and CTE with ROW_NUMBER().

The first step was to convert the date format to ensure consistency. Next, the data columns with NULL values were populated using a self join and the COALESCE function was used to replace any remaining NULL values. The table was then updated with new columns containing the desired data, which involved breaking strings up with delimiters using SUBSTRING and SPLIT_PART functions, and standardizing data abbreviations/entries with CASE. Finally, duplicates were removed with the help of Common Table Expressions (CTE) and ROW_NUMBER() function. Overall, these steps helped to ensure the data was accurate, consistent, and ready for analysis.

--------------------------------------------------------------------------------------------------------------------------------------
3. Excel Project Dataset: This project involves the analysis of bike purchases based on several factors such as income, age category, and commute distance. The project includes data cleaning and the use of pivot tables for analysis.
- Data cleaning: Removed duplicates, spelling correction, standardisation of data, created age groups using NESTED IF statements.
- Pivot tables: To identify trends and patterns in bike purchases based on the various factors.

--------------------------------------------------------------------------------------------------------------------------------------

Contact Information:
If you have any questions or feedback about the analysis, you can contact me at chenyy025@gmail.com

Contribution:
If you would like to contribute to the analysis or suggest improvements, feel free to submit a pull request or open an issue. All contributions are welcome.
