## SQL Performance Explained by Markus Winand

1. **Anatomy of an Index**
   - The Index Leaf Nodes
   - The Search Tree (B-Tree)
   - Slow Indexes, Part I

2. **The Where Clause**
   - The Equality Operator
   - Primary Keys
   - Concatenated Indexes
   - Slow Indexes, Part II
   - Functions
     - Case-Insensitive Search Using UPPER or LOWER
     - User-Defined Functions
   - Over-Indexing
   - Parameterized Queries
   - Searching for Ranges
     - Greater, Less and BETWEEN
     - Indexing LIKE Filters
     - Index Merge
   - Partial Indexes
     - NULL in the Oracle Database
     - Indexing NULL
     - NOT NULL Constraints
     - Emulating Partial Indexes
   - Obfuscated Conditions
     - Date Types
     - Numeric Strings
     - Combining Columns
     - Smart Logic
     - Math

3. **Performance and Scalability**
   - Performance Impacts of Data Volume
   - Performance Impacts of System Load
   - Response Time and Throughput

4. **The Join Operation**
   - Nested Loops
   - Hash Join
   - Sort Merge

5. **Clustering Data**
   - Index Filter Predicates Used Intentionally
   - Index-Only Scan
   - Index-Organized Tables

6. **Sorting and Grouping**
   - Indexing ORDER BY
   - Indexing ASC, DESC and NULLS FIRST/LAST
   - Indexing GROUP BY

7. **Partial Results**
   - Querying Top-N Rows
   - Paging Through Results
   - Using Window Functions for Pagination

8. **Modifying Data**
   - Insert
   - Delete
   - Update

9. **Execution Plans**
   - Oracle Database
   - PostgreSQL
   - SQL Server
   - MySQL