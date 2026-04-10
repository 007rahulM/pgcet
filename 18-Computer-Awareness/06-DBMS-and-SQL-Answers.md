# DBMS and SQL — Practice Problem Solutions

---

### Q1

**❓ Question:** Which SQL command retrieves data?
(A) INSERT  (B) UPDATE  (C) SELECT  (D) DELETE

**🤔 What I understood:** This is asking me to identify which SQL command is used to fetch/read data from a table.

**💡 What I'll use:** My knowledge of SQL DML (Data Manipulation Language) commands from this chapter.

**✏️ My Thought Process:**
- Option A — INSERT: **Wrong** — INSERT adds new rows to a table. It creates data, not retrieves it.
- Option B — UPDATE: **Wrong** — UPDATE modifies existing rows. It changes data, not retrieves it.
- Option C — SELECT: **Correct** — SELECT is the SQL command for querying/retrieving data. Example: `SELECT * FROM students WHERE age > 18;` — it fetches matching rows without modifying the table.
- Option D — DELETE: **Wrong** — DELETE removes rows from a table. It destroys data, not retrieves it.

**✅ Answer: (C) SELECT**

---

### Q2

**❓ Question:** What does PRIMARY KEY ensure?
(A) Data is encrypted  (B) Unique identification of rows  (C) Automatic sorting  (D) Rows can be NULL

**🤔 What I understood:** This is asking me about the purpose and guarantee of a PRIMARY KEY constraint.

**💡 What I'll use:** My knowledge of database constraints and keys from this chapter.

**✏️ My Thought Process:**
- Option A — Data is encrypted: **Wrong** — Encryption is a security feature unrelated to primary keys. Primary keys have nothing to do with encryption.
- Option B — Unique identification of rows: **Correct** — A PRIMARY KEY uniquely identifies each row in a table. It enforces two rules: (1) values must be unique across all rows, and (2) values cannot be NULL. This ensures every row can be precisely located.
- Option C — Automatic sorting: **Wrong** — Primary keys may create a clustered index (ordering on disk in some databases), but "automatic sorting" is not their purpose or guarantee.
- Option D — Rows can be NULL: **Wrong** — This is the opposite. A primary key column **cannot** contain NULL values.

**✅ Answer: (B) Unique identification of rows**

---

### Q3

**❓ Question:** Which JOIN returns only matching rows from both tables?
(A) LEFT JOIN  (B) INNER JOIN  (C) FULL JOIN  (D) RIGHT JOIN

**🤔 What I understood:** This is asking me to identify which SQL JOIN type returns only the rows where there is a match in both tables.

**💡 What I'll use:** My knowledge of SQL JOIN types from this chapter.

**✏️ My Thought Process:**
- Option A — LEFT JOIN: **Wrong** — LEFT JOIN returns all rows from the left table and matching rows from the right; non-matching right rows show NULL. It includes unmatched left rows.
- Option B — INNER JOIN: **Correct** — INNER JOIN returns only the rows where the join condition is satisfied in **both** tables. Rows with no match in either table are excluded entirely.
- Option C — FULL JOIN (FULL OUTER JOIN): **Wrong** — FULL JOIN returns all rows from both tables, filling NULLs where there's no match. It includes unmatched rows from both sides.
- Option D — RIGHT JOIN: **Wrong** — RIGHT JOIN returns all rows from the right table and matching rows from the left; similar to LEFT JOIN but mirrored.

**✅ Answer: (B) INNER JOIN**

---

### Q4

**❓ Question:** Which aggregate function finds the highest value?
(A) SUM  (B) MIN  (C) AVG  (D) MAX

**🤔 What I understood:** This is asking me to identify the SQL aggregate function that returns the maximum value in a column.

**💡 What I'll use:** My knowledge of SQL aggregate functions from this chapter.

**✏️ My Thought Process:**
- Option A — SUM: **Wrong** — SUM adds all values in a column and returns the total. It doesn't find the highest individual value.
- Option B — MIN: **Wrong** — MIN returns the **lowest** (minimum) value, which is the opposite of what's asked.
- Option C — AVG: **Wrong** — AVG calculates the arithmetic mean of all values. It doesn't find the single highest value.
- Option D — MAX: **Correct** — MAX scans all values in a column and returns the single **highest** (maximum) value. Example: `SELECT MAX(salary) FROM employees;`

**✅ Answer: (D) MAX**

---

### Q5

**❓ Question:** Which SQL command removes a table permanently?
(A) DELETE  (B) TRUNCATE  (C) DROP  (D) REMOVE

**🤔 What I understood:** This is asking me to identify which command not only removes data but also removes the table structure itself permanently.

**💡 What I'll use:** My knowledge of the difference between DELETE, TRUNCATE, and DROP from this chapter.

**✏️ My Thought Process:**
- Option A — DELETE: **Wrong** — DELETE removes **rows** from a table (can use WHERE to select which rows). The table structure remains intact. It can be rolled back.
- Option B — TRUNCATE: **Wrong** — TRUNCATE removes **all rows** from a table quickly but keeps the table structure. The empty table still exists.
- Option C — DROP: **Correct** — DROP TABLE removes the **entire table** — both its data and its structure — permanently. The table no longer exists after DROP. This operation is irreversible (DDL command).
- Option D — REMOVE: **Wrong** — REMOVE is not a valid SQL command.

**✅ Answer: (C) DROP**

---

### Q6

**❓ Question:** What is the correct order of SQL clauses?
(A) WHERE, FROM, SELECT  (B) SELECT, FROM, WHERE  (C) FROM, WHERE, SELECT  (D) FROM, SELECT, WHERE

**🤔 What I understood:** This is asking me to recall the standard SQL query syntax order.

**💡 What I'll use:** My knowledge of SQL query structure from this chapter.

**✏️ My Thought Process:**
- Option A — WHERE, FROM, SELECT: **Wrong** — Writing WHERE before FROM makes no syntactic sense; you must specify the source (FROM) before filtering (WHERE).
- Option B — SELECT, FROM, WHERE: **Correct** — The standard SQL query order is:
  ```sql
  SELECT column(s)
  FROM table
  WHERE condition;
  ```
  SELECT specifies what to retrieve; FROM specifies the source; WHERE filters the results.
- Option C — FROM, WHERE, SELECT: **Wrong** — Although internally the database processes FROM before WHERE before SELECT, the **written syntax** order is SELECT → FROM → WHERE.
- Option D — FROM, SELECT, WHERE: **Wrong** — Not the correct written syntax.

**✅ Answer: (B) SELECT, FROM, WHERE**

---

### Q7

**❓ Question:** ACID property ensures if a transaction fails midway:
(A) Isolation  (B) Atomicity  (C) Consistency  (D) Durability

**🤔 What I understood:** This is asking me to identify which ACID property guarantees that a partially executed transaction is rolled back completely.

**💡 What I'll use:** My knowledge of ACID transaction properties from this chapter.

**✏️ My Thought Process:**
- Option A — Isolation: **Wrong** — Isolation ensures concurrent transactions don't interfere with each other. It's about multi-user scenarios, not about handling a mid-transaction failure.
- Option B — Atomicity: **Correct** — Atomicity means a transaction is "all or nothing." If a transaction fails at any point, all changes made so far are rolled back, leaving the database as if the transaction never started. No partial updates remain.
- Option C — Consistency: **Wrong** — Consistency ensures the database moves from one valid state to another. It's a correctness guarantee, but it's Atomicity that handles the rollback on failure.
- Option D — Durability: **Wrong** — Durability ensures that once a transaction is **committed**, its changes are permanent (survive crashes). It's about completed transactions, not failed ones.

**✅ Answer: (B) Atomicity**

---

### Q8

**❓ Question:** Which normal form eliminates partial dependencies?
(A) 1NF  (B) 2NF  (C) 3NF  (D) BCNF

**🤔 What I understood:** This is asking me to identify which normalization form specifically addresses partial dependencies.

**💡 What I'll use:** My knowledge of database normalization from this chapter.

**✏️ My Thought Process:**
- Option A — 1NF (First Normal Form): **Wrong** — 1NF eliminates repeating groups and ensures atomic values. It does not address partial dependencies.
- Option B — 2NF (Second Normal Form): **Correct** — 2NF builds on 1NF and eliminates **partial dependencies** — where a non-key attribute depends on only part of a composite primary key, rather than the whole key. Every non-key attribute must be fully dependent on the entire primary key.
- Option C — 3NF (Third Normal Form): **Wrong** — 3NF eliminates **transitive dependencies** (where a non-key attribute depends on another non-key attribute). It goes beyond 2NF.
- Option D — BCNF (Boyce-Codd Normal Form): **Wrong** — BCNF is a stronger version of 3NF, addressing anomalies where a determinant is not a candidate key.

**✅ Answer: (B) 2NF**

---

### Q9

**❓ Question:** A FOREIGN KEY in a table refers to:
(A) A non-unique column  (B) The primary key of another table  (C) An encrypted column  (D) An indexed column

**🤔 What I understood:** This is asking me to identify what a FOREIGN KEY references in a relational database.

**💡 What I'll use:** My knowledge of relational database keys and referential integrity from this chapter.

**✏️ My Thought Process:**
- Option A — A non-unique column: **Wrong** — A foreign key can contain duplicate values (since multiple rows can reference the same parent), but its definition is about *what it references*, not about its own uniqueness.
- Option B — The primary key of another table: **Correct** — A FOREIGN KEY in table B is a column (or set of columns) that references the PRIMARY KEY in table A. It establishes a relationship between tables and enforces referential integrity — you can only insert values that exist in the referenced primary key.
- Option C — An encrypted column: **Wrong** — Encryption is a security concept entirely unrelated to foreign keys.
- Option D — An indexed column: **Wrong** — While foreign keys often benefit from indexing for performance, that's not their definition. A foreign key is defined by what it *references*, not by indexing.

**✅ Answer: (B) Primary key of another table**

---

### Q10

**❓ Question:** Which command rolls back a transaction?
(A) COMMIT  (B) UNDO  (C) ROLLBACK  (D) CANCEL

**🤔 What I understood:** This is asking me to identify the SQL command that undoes all changes made in the current transaction.

**💡 What I'll use:** My knowledge of transaction control commands (TCL) from this chapter.

**✏️ My Thought Process:**
- Option A — COMMIT: **Wrong** — COMMIT permanently saves all changes made in the current transaction. It is the opposite of rolling back.
- Option B — UNDO: **Wrong** — UNDO is not a standard SQL transaction control command. Some databases have UNDO concepts internally, but it's not a user-facing SQL command.
- Option C — ROLLBACK: **Correct** — ROLLBACK undoes all changes made in the current transaction since the last COMMIT (or since the transaction began), restoring the database to its previous state.
- Option D — CANCEL: **Wrong** — CANCEL is not a valid SQL command.

**✅ Answer: (C) ROLLBACK**

---

[← Back to Practice Problems](./06-DBMS-and-SQL.md)
