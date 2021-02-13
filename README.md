## All the analysis for this project is found in the ../Analysis Projects Folder/Pewlett-Hackard-Analysis Folder/

# Pewlett-Hackard-Analysis

The purpose of this analysis is to discover how many employees with their titles will be retiring.  And the other analysis is to find out which employees are eligible to participate in a mentorship program.

Analysis:
In this analysis the emp_no, first_name, and last_name columns were retieved from the Employees table.
The title, from_date, and to_date columns were retreived from the Titles table.
The two tables were inner joined on their primary key.
Then data was filtered on the birth_date column to retrieve the employees who were born between 1952 and 1955 and ordered by the employee number, then it was saved into the retirement_titles.csv.
The starter code was used on the DISTINCT ON statement to reterive the fist occurrence of the employee number for each set of rows.

![]image/unique_title.PNG
