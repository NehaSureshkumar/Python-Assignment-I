# Python-Assignment-I

Assignment 1: Compare APXENRICHED.FUND with CS_FUND_Extract excel file

STEP 1: Analyze the file APXENRICHED.FUND using python and its libraries and store the data in a table
•	Find out statistics of all the fields in the file using python library
•	Suggest the best datatype of the field
•	Create a table structure on the fly in SQL Server using the analysis
•	If a field has null / blank across all the rows, then ignore those columns while inserting in a table
•	Store the data in a table called APXENRICHED_FUND
•	Suggest an index for the table and create the index

STEP 2: Analyze the file CS_FUND using python and its libraries and store the data in a table
•	Find out statistics of all the fields in the file using python library
•	Suggest the best datatype of the field
•	Create a table structure on the fly in SQL Server using the analysis
•	If a field has null / blank across all the rows, then ignore those columns while inserting in a table
•	Store the data in a table called CS_FUND
•	Suggest an index for the table and create the index

STEP 3: Compare the fields in APXENRICHED_FUND with CS_FUND and store the data in a table
•	Take all the fields that exists in the APXENRICHED_FUND table and compare with the CS_FUND table
•	The Column that needs to be compared should have the same name in the two tables. Best if you create a metadata for the comparison columns
•	Compare the columns based on their datatype
o	String/varchar – exact match
o	Integer datatype column should have a tolerance of 1 (both ways)
o	Date datatype column should have a tolerance 1 day (both ways)
o	Float / decimal column should have a tolerance 0.01 (both ways)
•	Use ACCT_CD as the connection between the 2 tables for comparing each row
•	Identify the rows that exists in APXENRICHED_FUND but not in CS_FUND
•	Summarize the row/ column deviations and present their statistics / details
•	Insert the statistics at the column / row level comparison in table. You have the liberty to create the structure of the table.
•	 Visualize the Summary
