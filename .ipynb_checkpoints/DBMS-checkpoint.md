1. * **DDL** - Data Definition Language. *CREATE, ALTER, DROP, and RENAME* 
   * **DML** - Data Manipulation Language. *SELECT, INSERT, and UPDATE*
   * **DCL** - Data Control Language. *GRANT and REVOKE*
   
2. **ACID** 

   * ***Atomicity*** -  This property reflects the concept of either executing the whole query or executing nothing at all, which implies that if an update occurs in a database then that update should either be reflected in the whole database or should not be reflected at all.
   * ***Consistency*** - This property ensures that the data remains consistent before and after a transaction in a database.
   * ***Isolation*** - This property ensures that each transaction is occurring independently of the others. This implies that the state of an ongoing transaction doesn’t affect the state of another ongoing transaction.
   * ***Durability*** - This property ensures that the data is not lost in cases of a system failure or restart and is present in the same state as it was before the system failure or restart.

3. ### Are NULL values in a database the same as that of blank space or zero?

   No, a NULL value is very different from that of zero and blank space as it represents a value that is assigned, unknown, unavailable, or not applicable as compared to blank space which represents a character and zero represents a number.

4. ### What is meant by Data Warehousing?

   The process of collecting, extracting, transforming, and loading data from multiple sources and storing them into one database is known as data warehousing.

5. **JOIN** 

   An SQL Join is used to combine data from two or more tables, based on a common field between them.

6. * **INNER JOIN** - Returns records that have matching values in both tables
   * **LEFT OUTER JOIN** - Returns all records from the left table, and the matched records from the right table
   * **RIGHT OUTER JOIN** - Returns all records from the right table, and the matched records from the left table
   * **FULL OUTER JOIN** - Returns all records when there is a match in either left or right table

7. * **UNION** - Join data from 2 or more tables with distinct rows.
   * **UNION ALL** - Does not remove the duplicate rows, it just picks all the data from the tables. 

8. * **Intension** - Intension or popularly known as database schema is used to define the description of the database and is specified during the design of the database and mostly remains unchanged.
   * **Extension** - Extension is the number of tuples present in the database at any given point in time. The extension of a database is also referred to as the snapshot of the database and its value keeps changing as and when the tuples are created, updated, or destroyed in a database.

9. | DELETE                                                       | TRUNCATE                                                     |
   | ------------------------------------------------------------ | ------------------------------------------------------------ |
   | Delete rows from a table based on the condition provided by the WHERE clause. | Remove complete data from a table in a database.             |
   | Maintains a log to lock the row of the table before deleting it and hence it’s slow. | Doesn’t maintain a log and deletes the whole table at once and hence it’s fast. |

10. **LOCK** - A database lock is a mechanism to protect a shared piece of data from getting updated by two or more database users at the same time.

   * ***Shared Lock*** - A shared lock is required for reading a data item and many transactions may hold a lock on the same data item in a shared lock. Multiple transactions are allowed to read the data items in a shared lock.
   * ***Exclusive Lock*** - An exclusive lock is a lock on any transaction that is about to perform a write operation. This type of lock doesn’t allow more than one transaction and hence prevents any inconsistency in the database.

11. | NORMALIZATION                                                | DENORMALIZATION                                              |
       | ------------------------------------------------------------ | ------------------------------------------------------------ |
       | Process of reducing redundancy by organizing the data into multiple tables. | Reverse process of normalization as it combines the tables which have been normalized into a single table so that data retrieval becomes faster. |
       | Leads to better usage of disk spaces and makes it easier to maintain the integrity of the database. | ***JOIN*** operation allows us to create a denormalized form of the data by reversing the normalization. |

12. **FIRST NORAML FORM (1NF)** 

    * Every column must have a single value and should be atomic.
    * Duplicate columns from the same table should be removed.
    * Separate tables should be created for each group of related data and each row should be identified with a unique column.

13. **SECOND NORMAL FORM (2NF)** 

    * The table should be in its 1NF.
    * Every non-prime attribute of the table should be fully functionally dependent on the primary key.

14. **THIRD NORMAL FORM (3NF)** 

    * The table should be in its 2NF.
    * There is no transitive functional dependency of one attribute on any attribute in the same table.

15. **BOYCE-CODD NORMAL FORM (BCNF)** 

    * The table should be in its 3NF.
    * For every functional dependency of any attribute A on B (A->B), A should be the super key of the table.

16. * **PRIMARY KEY** -  A set of attributes that are used to uniquely identify every tuple.
    * **UNIQUE KEY** - *PRIMARY* key with NULL value.
    * **CANDIDATE KEY** - A set of properties that can uniquely identify a table. Each table may have multiple candidate keys and one such key is *PRIMARY* key.
    * **SUPER KEY** - A set of attributes that can uniquely identify a tuple and superset of *CANDIDATE* key and *PRIMARY* key.
    * **ALTERNATE KEY** - All the candidate keys which are not chosen as primary keys are considered as alternate Keys.
    * **FOREIGN KEY** - An attribute that can only take the values present in one table common to the attribute present in another table.
    * **COMPOSITE KEY** - A combination of two or more columns that can uniquely identify each tuple in a table.

17. **PATTERN MATCHING** -
    * The LIKE operator is used in conjunction with SQL Wildcards to fetch the required information.
    * * % - 0 or more characters
    * * K% - Begin wih K
    * * %K - End with K
    * * __K% - Third position character is K
    * * ____ - Exactly 4 characters
    * * __ % - Three or more characters