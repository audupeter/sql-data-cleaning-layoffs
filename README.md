# sql-data-cleaning-layoffs
MySQL Data Cleaning Project - Layoffs Dataset  
Overview 
in this project, i cleaned a real world layoffs dataset using SQL to prepare it for analysis.

Data Cleaning Process
. Created a staging table to preserve the original dataset 
. Identified duplicated using ROW_NUMBER() with PARTITION BY 
. Used a CTE to isolate and remove duplicate rows 
. Standerdized inconsisted values across columns 
. Converted blank values to NULL 
. Removed temporary columns after cleaning

SQL Skills Demonstrated
. Windows Functions (ROW_NUMBER())
. Common Table Expressions (CTEs)
. Data Cleaning (UPDATE, DELETE)
. Table Modifications (ALTER, TABLE)

Results 
The dataset was transformed into a clean and analysis-ready format

Key Learning 
This project strengthened my understanding of handling messy real-world data and writing structured SQL queries. 

Files
. data_cleaning.sql
