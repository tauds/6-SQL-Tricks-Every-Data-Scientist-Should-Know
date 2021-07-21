# 6-SQL-Tricks-Every-Data-Scientist-Should-Know
Part 1 of SQL Tricks to Make Your Analytics Work More Efficient
Data scientists/analysts should know SQL. In fact, all professionals working with data and analytics should know SQL. To some extent, SQL is an underrated skill for data science because it has been taken for granted as a necessary yet uncool way of extracting data out from the database to feed into pandas and {tidyverse}—fancier ways to wrangle your data.

SQL_R_Python.PNG

However, with massive data being collected and churned out every day in the industries, as long as the data resides in a SQL-compliant database, SQL is still the most proficient tool to help you investigate, filter, and aggregate to get a thorough understanding of your data. By slicing and dicing with SQL, analysts are allowed to possibly identify patterns that are worth further looking into, which oftentimes leads to redefining the analysis population and variables to be considerably smaller (than the initial scope).

Hence, rather than transferring huge datasets into Python or R, the first step of analytics should be using SQL to gain informative insights from our data.

Working in real-world relational databases, SQL is way more than just SELECT, JOIN, and ORDER BY statements. In this blog, I will discuss 6 tips (and one bonus tip) to make your analytics work more efficient with SQL and its integration with other programming languages like Python and R.

For this exercise, we will work with Oracle SQL on the toy data table below, which consists of multiple types of data elements.
