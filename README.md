# CSE 311 (SLF) — Faculty: Data Management  
**Course materials index (Markdown)**

This file organizes the PDFs in this folder into a clear study path for **CSE 311: Data Management / Database Systems**.

---

## Folder map

- **Midterm materials**: `MIdterm/`
- **Final materials**: `FInal/`
- **Project**: `Project/`
- **Extra questions**: `some_Q/`

---

## Midterm (Lectures + practice)

### Lecture slides
- **01 — Introduction**: [01-Introduction.pdf](MIdterm/01-Introduction.pdf)
- **02 — Relational Model**: [02-Relational%20Model.pdf](MIdterm/02-Relational%20Model.pdf)
- **03 — Introduction to SQL**: [03%20Introduction%20to%20SQL.pdf](MIdterm/03%20Introduction%20to%20SQL.pdf)

### Practice / sample questions
- **Midterm questions**: [midtermq.pdf](MIdterm/midtermq.pdf)
- **Sample Question SQL (FA-25)**: [Sample%20Question%20SQL-FA-25.pdf](MIdterm/Sample%20Question%20SQL-FA-25.pdf)
- **Sample Questions slide 01 & 02**: [Sample%20Questions%20slide%2001%20and%20slide%2002%20(1).pdf](MIdterm/Sample%20Questions%20slide%2001%20and%20slide%2002%20(1).pdf)


---

## Final (ERD + normalization + joins/views + constraints + authorization)

### ER modeling
- **04-a — Entity-Relationship Modeling (FA25)**: [04-a%20Entity-Relationship%20Modeling%20FA25.pdf](FInal/04-a%20Entity-Relationship%20Modeling%20FA25.pdf)
- **04-b — Entity-Relationship Modeling (FA25)**: [04-b%20Entity-Relationship%20Modeling%20FA25.pdf](FInal/04-b%20Entity-Relationship%20Modeling%20FA25.pdf)

### Normalization
- **05 — Normalization**: [05%20Normalization.pdf](FInal/05%20Normalization.pdf)
- **Sample question on Normalization**: [Sample%20question%20on%20Normalization.pdf](FInal/Sample%20question%20on%20Normalization.pdf)

### Joins, Views, Integrity Constraints, Authorization
- **06 — Joins / Views / Integrity Constraints / Authorization**: [06%20%20Joins%20Views%20Integrity%20Constraints%20and%20authorization.pdf](FInal/06%20%20Joins%20Views%20Integrity%20Constraints%20and%20authorization.pdf)
- **Combined sample (Outer Join + Norm + Views + Integrity + User Mgt)**: [Sample%20question%20on%20(OuterJoin%2BNorm%2Bviews%2BIntegrity%2BUserMgt)-FA25.pdf](FInal/Sample%20question%20on%20(OuterJoin%2BNorm%2Bviews%2BIntegrity%2BUserMgt)-FA25.pdf)

### ERD sample questions (final prep)
- **Sample questions on ERD (set 1)**: [861537460-sample-questions-on-ERD.pdf](FInal/861537460-sample-questions-on-ERD.pdf)
- **Updated ERD sample questions**: [908640292-Updated-Sample-Questions-on-ERD-1.pdf](FInal/908640292-Updated-Sample-Questions-on-ERD-1.pdf)
- **ERD Quiz-2**: [sample%20questions%20on%20ERD%20Quiz-2.pdf](FInal/sample%20questions%20on%20ERD%20Quiz-2.pdf)
- **ERD final set**: [sample%20questions%20on%20ERD-FA25_final.pdf](FInal/sample%20questions%20on%20ERD-FA25_final.pdf)

### Reference book
- **Database System Concepts (7th Edition)**: [Database-System-Concepts-7th-Edition.pdf](FInal/Database-System-Concepts-7th-Edition.pdf)

---

## Project

- **Final project report**: [finalprojectreport.pdf](Project/finalprojectreport.pdf)
- **edoc.zip** (project resources): [edoc.zip](Project/edoc.zip)

---

## Topic checklist (what to know)

### 1) Database basics
- Database vs DBMS, schema vs instance, data models
- 3-level architecture (external/conceptual/internal)
- Keys, constraints, redundancy, anomalies

### 2) Relational model
- Relations/tuples/attributes/domains
- Keys: super key, candidate key, primary key, foreign key
- Integrity: entity integrity, referential integrity
- Relational algebra ideas (selection/projection/join)

### 3) SQL (core)
- DDL: `CREATE`, `ALTER`, `DROP`
- DML: `SELECT`, `INSERT`, `UPDATE`, `DELETE`
- Filtering: `WHERE`, `AND/OR`, `LIKE`, `IN`, `BETWEEN`, `IS NULL`
- Aggregation: `COUNT`, `SUM`, `AVG`, `MIN`, `MAX` + `GROUP BY` + `HAVING`
- Subqueries: `IN`, `EXISTS`, correlated subqueries

### 4) Joins
- Inner join vs outer joins (`LEFT`, `RIGHT`, `FULL`)
- Join conditions and common mistakes (cartesian product)
- Natural join vs explicit join with `ON`

### 5) Views
- Creating views and using them for abstraction/security
- Updatable vs non-updatable views (concept)

### 6) Constraints & authorization
- Constraints: `PRIMARY KEY`, `FOREIGN KEY`, `UNIQUE`, `NOT NULL`, `CHECK`
- Actions: `ON DELETE` / `ON UPDATE` (e.g., `CASCADE`, `SET NULL`, `RESTRICT`)
- Basic authorization concepts (users/roles/privileges)

### 7) ER modeling
- Entity sets, attributes (simple/composite/multivalued/derived)
- Relationships (degree, cardinality, participation constraints)
- Weak entities, identifying relationships
- Mapping ERD → relational schema

### 8) Normalization
- Functional dependencies (FDs)
- 1NF, 2NF, 3NF, BCNF (definitions + how to test)
- Decomposition: lossless join + dependency preservation (concept)

---

## Suggested study order (fast)

1. **Relational model + keys/constraints** (Midterm slides)
2. **SQL SELECT + GROUP BY + subqueries**
3. **Joins + outer joins + views**
4. **ERD modeling + mapping to relations**
5. **Normalization + FD practice**
6. **Mixed practice sets** (final samples)

---

## Notes (quick reminders)

- **`WHERE` vs `HAVING`**: `WHERE` filters rows before grouping; `HAVING` filters groups after `GROUP BY`.
- **Outer join**: keeps unmatched rows from the preserved side; unmatched columns become `NULL`.
- **3NF vs BCNF**: BCNF is stricter; if a relation violates BCNF, 3NF decomposition may still be acceptable when dependency preservation matters.


