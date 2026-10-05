# SQL Course – Complete Topic List
(Generated via Claude)

## 1. Introduction to the World of SQL
1. What is Data?
   - Types of Data: Textual, Numerical, Multimedia, Sensor Data
2. Data → Information → Knowledge (Transformation Process)
3. Vitality of Data
4. Why Data is Required?
   - To Draw Conclusions
   - To Gain Insights
   - To Make Predictions
5. Data Symphony – How is Data Collected?
   - Sensors
   - Trackers
   - Mobile Phones
   - Other Sources: Social media, POS systems, Cameras/Smart devices, IoT devices
6. How is Data Stored?
   - Flat Files
   - Databases
   - Data Warehouses
7. Central Data Tank – Types of Databases
   - What is a Database?
   - What is RDBMS?
   - Features of RDBMS: Tables, Primary Key, Foreign Key, SQL, Data Integrity
   - Examples of RDBMS Tools: MySQL, Oracle Database, Microsoft SQL Server, PostgreSQL

## 2. MySQL Workbench Installation (Gate Pass to the World of MySQL)
- Introduction to MySQL Workbench
- Step-by-Step Installation Guide
  1. Download MySQL Installer
  2. Launch and Select Setup Type
  3. Install Required Components
  4. Configure the MySQL Server
  5. Complete Installation and Start Workbench
  6. Launch and Test MySQL Workbench
- Quick Checks After Installation

## 3. Juggling Data Types
1. Understanding SQL Data Types
   - A. Numeric Data Types
     - Exact Numeric Types: INT/INTEGER, SMALLINT, BIGINT, DECIMAL/NUMERIC
     - Approximate Numeric Types: FLOAT, REAL, DOUBLE PRECISION
   - B. String (Character) Data Types: CHAR(n), VARCHAR(n), TEXT
   - C. Date and Time Data Types: DATE, TIME, DATETIME, TIMESTAMP, YEAR
   - D. Boolean Type: BOOLEAN/BOOL
   - E. Binary Data Types: BINARY(n), VARBINARY(n), BLOB
2. Practice: Try It Yourself
   - Create a Table with Mixed Data Types
   - Insert Sample Records
   - View Table Structure

## 4. Navigating Database Relationships
- Understanding Database Relationships
  - A. One-to-One Relationship
  - B. One-to-Many Relationship
  - C. Many-to-Many Relationship (Junction Tables)
- ER Diagrams (Entity-Relationship Diagrams)
  - Entities, Attributes, Relationships, Cardinality
  - Cardinality Types in ER Diagrams: One-to-One, One-to-Many, Many-to-Many

## 5. Data Quality and Speed: Constraints, Keys, and Indexing
1. Primary and Foreign Keys
   - Primary Key
   - Foreign Key
2. SQL Constraints (Detailed)
   - PRIMARY KEY
   - FOREIGN KEY
   - UNIQUE
   - NOT NULL
   - CHECK
   - DEFAULT
3. Indexes in SQL
   - Advantages of Indexes
   - Disadvantages of Indexes
   - Creating Indexes: Single-column Index, Composite Index
   - Removing Indexes

## 6. Normalisation and Denormalisation Strategies
1. What is Normalization?
   - Objectives of Normalization
2. Normalization Forms (Detailed Explanation)
   - First Normal Form (1NF)
   - Second Normal Form (2NF)
   - Third Normal Form (3NF)
3. Denormalization
   - When to Consider Denormalization?

## 7. Blueprinting Database Structures
1. Creating Databases and Tables
   - Steps to Create a Database
   - Creating Tables
2. Designing Tables with Appropriate Data Types
   - Importance of Correct Data Types
3. Data Types in SQL (INT, VARCHAR, CHAR, DATE, DECIMAL, BOOLEAN, TEXT)

## 8. SQL's Data Addition Tool – INSERT
1.1 What Is the INSERT Statement?
1.2 Basic Syntax
   - Inserting into All Columns
   - Inserting into Specific Columns
1.3 Example: Insert a New Student
1.4 Inserting Multiple Rows (Bulk Insert)
1.5 Inserting Data Using SELECT
1.6 Handling Identity (Auto-Increment) Columns
1.7 Inserting NULL Values
1.8 Error Handling and Best Practices

## 9. Data Maintenance with UPDATE
- What is the UPDATE Statement?
- When and Why is UPDATE Used?
- How Does the UPDATE Statement Work?
  - Specify the Table
  - Set New Values
  - Use Conditions
  - Use Subqueries or Joins
- Syntax Overview
- Important Notes
  - WHERE Clause is Critical
  - Multiple Columns Can Be Updated
  - Supports Expressions and Calculations
  - Can Use Subqueries
- Update Techniques Covered:
  - Update a Single Column
  - Update Multiple Columns
  - Update All Rows (No WHERE Clause)
  - Conditional Update Using Logical Operators
  - Update with Calculated Values
  - Using Subquery in an UPDATE
  - Update Using CASE (Conditional Logic)
  - UPDATE with JOIN

## 10. SQL Cleanup Crew (Mastering SQL with DELETE Statement)
- What is the DELETE Statement?
- Why Use DELETE?
- How DELETE Works
- Syntax Overview
- Important Points: Transactions, Referential Integrity, Performance
- Delete Techniques Covered:
  - Delete a Single Row
  - Delete Multiple Rows Based on Condition
  - Delete All Rows from a Table
  - Conditional DELETE with Multiple Criteria
  - DELETE with Subquery
  - DELETE with EXISTS
  - DELETE with JOIN (MySQL-style)
- Best Practices (Preview before delete, Transactions, Batch deletion)
- DELETE vs TRUNCATE

## 11. Mastering SELECT Statement
1. Introduction to SELECT Statement
2. Using Aliases for Columns
3. Filtering Data with WHERE Clause
4. Applying Conditions to SELECT Queries
   - Comparison Operators: =, >, <, >=, <=, <> / !=
5. Combining Multiple Conditions with AND, OR
   - Logical Operators: AND, OR, NOT
   - Combining AND and OR with Parentheses

## 12. Sorting Query Result
1. Introduction to ORDER BY Clause
2. Sorting in Descending Order (DESC)
3. Sorting by Multiple Columns
4. Sorting by Column Index and Expressions

## 13. Result Control with LIMIT and OFFSET
1. Introduction to LIMIT Clause
2. Using OFFSET to Skip Rows
3. Pagination with LIMIT and OFFSET
   - Advantages of Using LIMIT and OFFSET
   - Limitations

## 14. Window Functions Decoded: Part 1
- What are Window Functions in SQL?
- Why Use Window Functions?
  - Retains Individual Rows
  - Ranks and Sorts Data Efficiently
  - Improves Analytical Queries
- Key Window Functions Covered:
  1. ROW_NUMBER()
  2. RANK()
  3. DENSE_RANK()
- Basic Syntax of Window Functions (PARTITION BY, ORDER BY)

## 15. Nulls Decoded
1. Understanding NULL in SQL
   - Key Properties of NULL: Unknown Value, Not Comparable, Three-Valued Logic
2. Checking for NULL Values (IS NULL, IS NOT NULL)
3. Handling NULL with COALESCE and IFNULL
4. NULL in Aggregate Functions
5. Sorting NULLs with ORDER BY
6. Logical Expressions Involving NULL

## 16. String Manipulation Magic (String Functions in SQL)
1.1 What Are String Functions in SQL?
1.2 CONCAT() – Combining Strings
1.3 SUBSTRING() – Extracting Part of a String
1.4 LENGTH() – Counting Characters in a String
1.5 LOCATE() – Finding the Position of a Substring
1.6 CONCAT_WS() – Combine with Separator
1.7 UPPER() and LOWER() – Changing Case
- Also referenced: TRIM(), REPLACE()

## 17. Unlocking Maths Prowess (Mathematical Functions in SQL)
1.1 Introduction to Mathematical Functions in SQL
1.2 Basic Arithmetic Operations (+, -, *, /, %)
1.3 ROUND() – Rounding to Specific Decimal Places
1.4 CEIL() and FLOOR() – Round Up or Down
1.5 ABS() – Absolute Value
1.6 POWER() and SQRT() – Exponentiation and Square Root
1.7 MOD() – Remainder After Division
1.8 SIGN() – Detect Number Sign
1.9 TRUNCATE() – Remove Decimal Digits Without Rounding
- Also referenced: RAND()

## 18. Mastering Dates and Times (Date and Time Functions in SQL)
1.1 Introduction to Date and Time in SQL
   - Data types: DATE, TIME, DATETIME/TIMESTAMP
1.2 Getting the Current Date and Time (CURRENT_DATE, CURRENT_TIME, NOW())
1.3 EXTRACT() – Extracting Parts of a Date
1.4 DATE_ADD() and DATE_SUB() – Date Arithmetic
1.5 DATEDIFF() – Finding the Number of Days Between Two Dates
1.6 DATE_FORMAT() – Custom Formatting of Dates
1.7 Working with TIME Values (HOUR(), MINUTE(), SECOND(), ADDTIME(), SUBTIME())
- Also referenced: TIMESTAMPDIFF(), LAST_DAY(), DAYNAME(), WEEKDAY(), DATE_TRUNC()

## 19. Crunching Numbers with SQL (Aggregation Functions in SQL)
1.1 Introduction to Aggregation Functions
1.2 SUM() – Total of Values
1.3 AVG() – Average of Values
1.4 COUNT() – Counting Records
1.5 MAX() – Maximum Value
1.6 MIN() – Minimum Value
1.7 Combining Aggregates with GROUP BY

## 20. Discovering SQL Trends (GROUP BY and HAVING Clause)
1.1 Introduction to GROUP BY and HAVING
1.2 GROUP BY Clause
1.3 Aggregate Functions with GROUP BY (SUM, AVG, COUNT, MAX, MIN)
1.4 HAVING Clause
1.5 Difference Between WHERE and HAVING
1.6 ORDER BY with GROUP BY
1.7 Real-World Use Cases (Retail, Education, HR, Finance)

## 21. Connecting Data for Better Insights (JOINS in SQL)
1.1 What Are JOINS in SQL?
1.2 Types of Joins
   1. INNER JOIN
   2. LEFT JOIN
   3. RIGHT JOIN
   4. FULL JOIN (OUTER JOIN)
1.3 INNER JOIN
1.4 LEFT JOIN (LEFT OUTER JOIN)
1.5 RIGHT JOIN (RIGHT OUTER JOIN)
1.6 FULL OUTER JOIN
1.7 Choosing the Right JOIN
1.8 Join Conditions and Aliases

## 22. Subqueries for Smarter Data Access (Subqueries in SQL)
1.1 What Is a Subquery?
1.2 Why Use Subqueries?
1.3 Common Types of Subqueries
   1. Scalar Subquery
   2. Multiple Row Subquery
   3. Table Subquery
   4. Correlated Subquery
1.4 Subquery in WHERE Clause (Single Value)
1.5 Subquery in WHERE Clause (Multiple Values)
1.6 Subquery in FROM Clause (Inline View)
1.7 Correlated Subquery
1.8 Subquery in SELECT Clause
1.9 Subquery Limitations
