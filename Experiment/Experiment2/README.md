# Experiment 2

**Name:** Sonia  
**UID:** 24BCS12732

## Aim

To understand and implement SQL set operators (**UNION**, **UNION ALL**, **INTERSECT**, and **EXCEPT**) for combining and comparing the results of multiple SELECT statements.

---

## Question 1: UNION

### Problem Statement

Write a query using **UNION** to stack the table **Arts** over **Science** and display the final table.

### SQL Query Used

Refer to **union.sql**

### Output

See **union.png**

### Result

The records from the **Arts** and **Science** tables were successfully combined using the **UNION** operator. Duplicate rows were removed from the final result.

---

## Question 2: UNION ALL

### Problem Statement

Write a query to display the employee names from both **employee** and **pt_employee** tables without removing duplicate names.

### SQL Query Used

Refer to **union_all.sql**

### Output

See **union_all.png**

### Result

The employee names from both tables were successfully combined using the **UNION ALL** operator, and duplicate records were retained.

---

## Question 3: INTERSECT

### Problem Statement

Write a query to display the fruits that are available in both the **fruit** table and the **inventory** table.

### SQL Query Used

Refer to **intersect.sql**

### Output

See **intersect.png**

### Result

The common fruit names present in both tables were successfully retrieved using the **INTERSECT** operator.

---

## Question 4: EXCEPT

### Problem Statement

Write a query to display the fruits that are present in the **fruit** table but not in the **inventory** table.

### SQL Query Used

Refer to **except.sql**

### Output

See **except.png**

### Result

The fruit names available only in the **fruit** table were successfully retrieved using the **EXCEPT** operator.
