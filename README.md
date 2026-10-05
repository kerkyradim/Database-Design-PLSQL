# Database Design Topics — Oracle PL/SQL (Harokopio University)

Course: **Θέματα Σχεδίασης Βάσεων Δεδομένων** (Database Design Topics)  
**Author:** [Kerkyra Dimisianou](https://github.com/kerkyradim) · IT22026  
**Institution:** Harokopio University of Athens — Department of Informatics and Telematics

Oracle **PL/SQL** coursework: relational schema design, analytical SQL on retail data (**XSALES**), and a library management case with stored programs, triggers, and performance analysis.

---

## Assignments in this repository

| Folder | Topic | Main artifacts |
|--------|--------|----------------|
| [`ergasia-01/`](ergasia-01/) | 1st assignment (course brief) | Assignment specification (PDF) |
| [`ergasia-02/`](ergasia-02/) | 2nd assignment — **XSALES** customer analytics | `2hergasia.sql`, cleanup script |
| [`ergasia-03/`](ergasia-03/) | 3rd assignment — **library system** | DDL/DML, packages, functions, procedures |
| [`labs/`](labs/) | Query optimizer lab | `optimizer.sql` (`EXPLAIN PLAN`, indexes) |

Run scripts in **Oracle SQL Developer** or SQL\*Plus against a schema with access to sample objects (e.g. `XSALES` where required). Execute **`drop_*.sql`** only when you intend to tear down objects.

---

## Highlights (CV-friendly)

- Designed normalized tables, keys, and constraints; used **sequences** for surrogate keys  
- Built **views**, aggregations, and customer segmentation (age groups, income bands)  
- Implemented **PL/SQL** functions, procedures, and **packages** (library lending workflow)  
- Analyzed execution plans with **`EXPLAIN PLAN`**, hints, and **indexes** for join/filter performance  

---

## Repository layout

```
ergasia-01/     # 1st assignment PDF
ergasia-02/     # 2nd assignment SQL + brief
ergasia-03/     # 3rd assignment SQL scripts + brief
labs/           # Optimizer exercises
```

---

## License

Academic coursework — reference use with attribution.
