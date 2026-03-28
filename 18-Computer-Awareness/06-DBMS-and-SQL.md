# DBMS & SQL — Database Concepts and Queries

## 🔑 What is a Database?

A **Database** is an organized collection of data.
A **DBMS** (Database Management System) is software to create, manage, and query databases.

**Examples:** MySQL, Oracle, PostgreSQL, MS Access, SQLite

---

## 📐 Key DBMS Concepts

### DBMS vs File System:
| Feature | File System | DBMS |
|---------|------------|------|
| Data Redundancy | High | Low |
| Data Consistency | Poor | Good |
| Security | Limited | Strong |
| Query | Manual | SQL |
| Concurrency | No | Yes |

### Database Models:
| Model | Description | Example |
|-------|-------------|---------|
| **Hierarchical** | Tree structure | IBM IMS |
| **Network** | Graph structure | IDMS |
| **Relational** | Tables with rows & columns | MySQL, Oracle |
| **Object-Oriented** | Objects with attributes | ObjectDB |

**Most common: Relational Model** — this is what SQL is for.

---

## 📐 Relational Database Terms

| Term | Meaning |
|------|---------|
| **Table/Relation** | Grid with rows and columns |
| **Row/Tuple** | One record |
| **Column/Attribute** | One field/characteristic |
| **Primary Key** | Unique identifier for each row |
| **Foreign Key** | Key in one table linking to another table's primary key |
| **Candidate Key** | Any key that can be primary key |
| **Super Key** | Any combination of columns that uniquely identifies a row |

---

## 📐 SQL — Structured Query Language

### SQL Categories:
| Category | Commands | Purpose |
|----------|----------|---------|
| **DDL** — Data Definition | CREATE, ALTER, DROP | Define structure |
| **DML** — Data Manipulation | INSERT, UPDATE, DELETE | Modify data |
| **DQL** — Data Query | SELECT | Retrieve data |
| **DCL** — Data Control | GRANT, REVOKE | Permissions |
| **TCL** — Transaction Control | COMMIT, ROLLBACK | Transactions |

---

## 📐 SQL SELECT — The Most Important Command

### Basic Syntax:
```sql
SELECT column1, column2
FROM table_name
WHERE condition
ORDER BY column ASC/DESC
GROUP BY column
HAVING condition
LIMIT n;
```

### Examples:

**1. Select all records:**
```sql
SELECT * FROM Students;
```

**2. Select specific columns:**
```sql
SELECT Name, Age FROM Students;
```

**3. With condition:**
```sql
SELECT * FROM Students WHERE Age > 20;
```

**4. With ordering:**
```sql
SELECT * FROM Students ORDER BY Name ASC;
```

**5. Count records:**
```sql
SELECT COUNT(*) FROM Students;
```

**6. With GROUP BY:**
```sql
SELECT Department, COUNT(*) 
FROM Employees 
GROUP BY Department;
```

**7. JOIN two tables:**
```sql
SELECT Students.Name, Courses.CourseName
FROM Students
INNER JOIN Courses ON Students.CourseID = Courses.ID;
```

---

## 📐 SQL Aggregate Functions

| Function | Purpose | Example |
|----------|---------|---------|
| COUNT() | Count rows | COUNT(*) |
| SUM() | Add values | SUM(Salary) |
| AVG() | Average | AVG(Marks) |
| MAX() | Maximum | MAX(Age) |
| MIN() | Minimum | MIN(Price) |

---

## 📐 SQL JOIN Types

| Join | Returns |
|------|---------|
| **INNER JOIN** | Only matching rows in both tables |
| **LEFT JOIN** | All rows from left + matching from right |
| **RIGHT JOIN** | All rows from right + matching from left |
| **FULL JOIN** | All rows from both tables |

---

## 📐 Normalization

**Purpose:** Eliminate data redundancy and ensure data integrity.

| Normal Form | Rule |
|-------------|------|
| **1NF** | No repeating groups; atomic values |
| **2NF** | 1NF + no partial dependencies on primary key |
| **3NF** | 2NF + no transitive dependencies |
| **BCNF** | Stronger version of 3NF |

---

## 📐 ACID Properties (Transactions)

| Letter | Property | Meaning |
|--------|----------|---------|
| A | **Atomicity** | All operations complete or none |
| C | **Consistency** | DB remains in valid state |
| I | **Isolation** | Transactions don't interfere |
| D | **Durability** | Committed data persists |

---

## 📝 Practice Problems

1. Which SQL command retrieves data?
   (A) INSERT  (B) UPDATE  (C) SELECT  (D) DELETE

2. What does PRIMARY KEY ensure?
   (A) Data is encrypted  (B) Unique identification of rows  
   (C) Automatic sorting  (D) Rows can be NULL

3. Which JOIN returns only matching rows from both tables?
   (A) LEFT JOIN  (B) INNER JOIN  (C) FULL JOIN  (D) RIGHT JOIN

4. Which aggregate function finds the highest value?
   (A) SUM  (B) MIN  (C) AVG  (D) MAX

5. Which SQL command removes a table permanently?
   (A) DELETE  (B) TRUNCATE  (C) DROP  (D) REMOVE

6. What is the correct order of SQL clauses?
   (A) WHERE, FROM, SELECT  (B) SELECT, FROM, WHERE  
   (C) FROM, WHERE, SELECT  (D) FROM, SELECT, WHERE

7. ACID property ensures if a transaction fails midway:
   (A) Isolation  (B) Atomicity  (C) Consistency  (D) Durability

8. Which normal form eliminates partial dependencies?
   (A) 1NF  (B) 2NF  (C) 3NF  (D) BCNF

9. A FOREIGN KEY in a table refers to:
   (A) A non-unique column  (B) The primary key of another table  
   (C) An encrypted column  (D) An indexed column

10. Which command rolls back a transaction?
    (A) COMMIT  (B) UNDO  (C) ROLLBACK  (D) CANCEL

---

## ✔️ Answers with Full Explanation

1. **(C) SELECT**
   Explanation: SELECT is a DQL (Data Query Language) command used to retrieve/read data from tables. INSERT adds new rows, UPDATE modifies existing rows, DELETE removes rows.

2. **(B) Unique identification of rows**
   Explanation: PRIMARY KEY uniquely identifies each row in a table. No two rows can have the same primary key value. It also cannot be NULL. Example: Student_ID as primary key ensures no two students have the same ID.

3. **(B) INNER JOIN**
   Explanation: INNER JOIN returns only rows where there is a match in BOTH tables. LEFT JOIN returns all left table rows + matched right rows (unmatched = NULL). RIGHT JOIN is the reverse.

4. **(D) MAX**
   Explanation: MAX() returns the highest value in a column. MIN() returns lowest. AVG() returns average. SUM() returns total. Use: SELECT MAX(Salary) FROM Employees;

5. **(C) DROP**
   Explanation: DROP TABLE removes the entire table structure AND data permanently. DELETE removes specific rows but table remains. TRUNCATE removes all rows but table structure remains. DROP is DDL, DELETE/TRUNCATE are DML.

6. **(B) SELECT, FROM, WHERE**
   Explanation: SQL syntax order: SELECT (what columns) → FROM (which table) → WHERE (which rows). Full order: SELECT → FROM → WHERE → GROUP BY → HAVING → ORDER BY.

7. **(B) Atomicity**
   Explanation: Atomicity = "all or nothing". If a transaction fails halfway (e.g., system crash during bank transfer), all changes are rolled back as if nothing happened. The entire transaction must complete or none of it applies.

8. **(B) 2NF**
   Explanation: 2NF eliminates partial dependencies — all non-key attributes must depend on the ENTIRE primary key, not just part of it. 1NF eliminates repeating groups. 3NF eliminates transitive dependencies.

9. **(B) The primary key of another table**
   Explanation: A FOREIGN KEY creates a link between two tables. It references the PRIMARY KEY of another table. Example: Orders table has Customer_ID as foreign key linking to Customers table's primary key.

10. **(C) ROLLBACK**
    Explanation: ROLLBACK undoes all changes made in the current transaction, returning the database to its last committed state. COMMIT saves all changes permanently. There's no UNDO command in standard SQL.
