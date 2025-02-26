<!--
---
Title: "CASE"
Subjects:
  - "data science"
Tags:
  - "data science"
  - "database"
  - "queries"
  - "table"
  - "postgressql"
  - "mysql"
  - "sqlite"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-sql"
  - "https://www.codecademy.com/learn/sql-table-transformation"
  - "https://www.codecademy.com/learn/paths/design-databases-with-postgresql"
  - "https://www.codecademy.com/learn/paths/full-stack-engineer-career-path"
---
-->

## Definition 
A logical test that creates different output based on the conditions of each CASE statement, closes with an END clause.

## Code Example

```sql
SELECT
  student_name AS Student,
  overall_gpa AS GPA,
CASE
  WHEN overall_gpa > 3.0 THEN "Exceptional grades, keep up the good work!"
  WHEN overall_gpa BETWEEN 2.0 AND 3.0 THEN "Good job! Study hard this term!"
  ELSE "You're at risk of academic probation, seek help if needed."
END
FROM Students;
```
