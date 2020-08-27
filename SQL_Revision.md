# SQL-Revision

This is my practice for **SQL**, it is a refresher of SQL as it was done it week 2 of the course.

## Learning Points

### 1st Normal form

* Make Everything atomic (data is as small as it can be)
* There should be no repeating columns, 2 author columns 

### 2nd Normal form

* It is 1st Normal Form
* All non key attributes are fully functionally dependent on the Primary key
* **Composite Keys** are made up of two different columns to make a unique primary key, sometimes known as a junction table.

### 3rd Normal form

* It is a 2nd Normal Form
* There is no transitive functional dependency is when a non-key column is functionally dependent on another non-key column, which is functionally depdent on the primary key.

**Structured Query Language Key words**

| DML    | DDL      |
|--------|----------|
| `SELECT` | `CREATE`   |
| `INSERT` | `ALTER`    |
| `UPDATE` | `DROP`     |
| `DELETE` | `TRUNCATE` |


* **LOGICAL** (syntax) Sequence

1. **SELECT** 
2. **WHERE** 
3. **GROUP BY** 
4. **HAVING** 
5. **SELECT** 
6. **DISTINCT** 
7. **ORDER BY** 

* **JOINS**
    * `INNER JOIN` - Returns records that have matching values in both tables and only shows the relational data.
    * `LEFT JOIN` - Returns all records from the left table, and the matched records from the right table.
    * `RIGHT JOIN` - Returns all records from the right table, and the matched records from the left table.
    * `FULL JOIN` - Returns all records when there is a match in either left or right table
    * `SELF JOIN` - A Self JOIN is a regular join, but the table is joined with itself

**JOIN** clauses are used to combine rows from two or more tables, based on a related 
column between them. It allows you to create a lsit of combined rows of matching data from different 
tables.

Performing a left join on orders and customers table. Using customer ID as the relationship between the two.

```sql
SELECT *
FROM Orders
LEFT JOIN Customers
ON Orders.CustomerID = Customers.CustomerID;
```

`INNER JOIN` to select all records from two tables to show a match in both tables.

```sql
SELECT *
FROM Orders
INNER JOIN Customers
ON Orders.CustomerID=Customers.CustomerID;
```


* **AGGREGATE FUNCTIONS** 

|           | Description                                                                             |
|-----------|-----------------------------------------------------------------------------------------|
| **SUM**   | `SUM(OrderTotal)` for the grand total of a column for all rows selected                 |
| **AVG**   | `AVG(UnitPrice)` for the average of a column for all rows selected                      |
| **MIN**   | `MIN(UnitPrice)` for the smallest value in a column for all rows selected               |
| **MAX**   | `MAX(UnitPrice)` for the largest value in a column for all rows selected                |
| **COUNT** | `COUNT(*)` for the number of NOT NULL rows selected. If * is used all rows are counted. |

* **Sub Queries**

This is an example of subquery in the `WHERE` clause, check to see which customers 
have not place any orders. This could also be achieving `JOINS`

```sql 
SELECT CompanyName AS "Customer"
FROM Customers 
WHERE CustomerID NOT IN 
    (SELECT CustomerID FROM Orders)
```

_Same Problem as above but using a `JOIN` this can only be accomplished using 
an outer `JOIN` like the `FULL`, `LEFT` and `RIGHT`._

```sql 
SELECT c.CompanyName AS "Customer"
FROM Customers c 
LEFT JOIN Orders o ON c.CustomerID = o.CustomerID
WHERE o.CustomerID IS NULL
```

_This is an example of a nested subquery in the `SELECT` clause (acts like a column). 
Subqueries must be contained by parenthesis (excluding any alias). Outputs the highest price in the table 
on every row in the result set._

**Wildcards**

```sql
SELECT * FROM Customers
WHERE City LIKE '[acs]%';
```

Multiple starting letters `a`, `c` and `s` can be the first letter.

```sql
SELECT * FROM Customers
WHERE City LIKE '[a-f]%';
```

Starts with anything from an `a` to an `f`.

```sql
SELECT * FROM Customers
WHERE Country IN ('Norway', 'France');
```

Select all records where country is either norway or france.

```sql
ALTER TABLE Persons
DROP column Birthday
```

Delete column birthday from Person table

