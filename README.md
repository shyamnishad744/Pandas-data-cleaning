# PANDAS DATA CLEANING PROJECT

This project demonstrate how clean raw-data using python and pandas library

# DATA CLEANING PERFORMED

1. **Removing Duplicates** – Eliminating redundant records to ensure data integrity and prevent inconsistencies. This is done using techniques like `DISTINCT`, `GROUP BY`, or `DELETE` with subqueries.  

2. **Dropping Unnecessary Columns** – Removing irrelevant or redundant columns to optimize storage and improve query performance. This is achieved using the `ALTER TABLE ... DROP COLUMN` statement.  

3. **Stripping Whitespaces** – Ensuring text data is clean by removing leading and trailing spaces using functions like `TRIM()`, which helps maintain consistency in textual data.  

4. **Standardizing Phone Numbers** – Formatting phone numbers into a uniform structure by removing special characters (like dashes and parentheses) and ensuring a consistent format across records. This is useful for data validation and easier querying.  

5. **Splitting Columns** – Dividing data stored in a single column (e.g., full name) into multiple columns (e.g., first name, last name) to improve data organization and usability. This is often done using string functions like `SUBSTRING_INDEX()` or `STRING_SPLIT()`.  

6. **Filling NULL Values** – Handling missing data by replacing `NULL` values with default or meaningful values to prevent errors in calculations and reports.  


