# SQL Study Guide - What to Learn Before Each Module

## 📚 Prerequisites for Each 10-Question Module

---

### **Before Q1-10: SELECT Basics & Filtering**
**Core Concepts to Master:**
- `SELECT` statement syntax
- `WHERE` clause with comparison operators (`=`, `!=`, `<`, `>`, `<=`, `>=`)
- `AND`, `OR`, `NOT` logical operators
- `ORDER BY` (ASC/DESC)
- `LIMIT` and `OFFSET`
- `DISTINCT` keyword
- Handling `NULL` values (`IS NULL`, `IS NOT NULL`)
- Basic string functions: `LENGTH()`, `UPPER()`, `LOWER()`
- Comment syntax (`--` and `/* */`)

**Practice Focus:**
- Write simple queries to filter and sort data
- Understand how NULL values behave in comparisons
- Practice combining multiple WHERE conditions

---

### **Before Q11-20: Aggregate Functions & Grouping**
**New Concepts to Learn:**
- Aggregate functions: `COUNT()`, `SUM()`, `AVG()`, `MIN()`, `MAX()`
- `GROUP BY` clause
- `HAVING` clause (vs WHERE)
- `COUNT(*)` vs `COUNT(column_name)`
- Handling NULLs in aggregations
- Mathematical operations (`+`, `-`, `*`, `/`, `%`)
- `ROUND()`, `CEIL()`, `FLOOR()` functions

**Key Understanding:**
- Difference between WHERE (filters rows) and HAVING (filters groups)
- When to use each aggregate function
- How GROUP BY partitions data

**Practice Focus:**
- Calculate summary statistics per group
- Filter groups using HAVING
- Combine multiple aggregate functions

---

### **Before Q21-30: String & Date Functions**
**New Concepts to Learn:**

**String Functions:**
- `SUBSTRING()` / `SUBSTR()`
- `CONCAT()` and `||` operator
- `TRIM()`, `LTRIM()`, `RTRIM()`
- `REPLACE()`
- `LIKE` operator with wildcards (`%`, `_`)
- `REGEXP` / `RLIKE` (pattern matching)

**Date Functions:**
- `NOW()`, `CURRENT_DATE`, `CURRENT_TIME`
- `DATE()`, `TIME()`, `YEAR()`, `MONTH()`, `DAY()`
- `DATE_ADD()`, `DATE_SUB()` (MySQL) or `INTERVAL` (PostgreSQL)
- `DATEDIFF()`
- Date formatting functions
- Converting between date formats

**Practice Focus:**
- Manipulate and format text data
- Extract parts of dates
- Calculate date differences and add/subtract time periods

---

### **Before Q31-40: Basic Joins**
**New Concepts to Learn:**
- `INNER JOIN` syntax and behavior
- `LEFT JOIN` (LEFT OUTER JOIN)
- `RIGHT JOIN` (RIGHT OUTER JOIN)
- `FULL OUTER JOIN`
- Join conditions with `ON` clause
- Table aliases (`AS` keyword)
- Understanding primary keys and foreign keys
- Cartesian products (cross joins)

**Key Understanding:**
- When each type of join is appropriate
- How joins multiply result sets
- Difference between ON and WHERE in joins

**Practice Focus:**
- Join two tables with related data
- Handle missing relationships (LEFT/RIGHT joins)
- Use table aliases for cleaner queries

---

### **Before Q41-50: Advanced Joins & Subqueries**
**New Concepts to Learn:**
- Multiple table joins (3+ tables)
- Self joins (joining a table to itself)
- Subqueries in `WHERE` clause
- Subqueries in `SELECT` clause
- Correlated vs non-correlated subqueries
- `IN`, `NOT IN`, `EXISTS`, `NOT EXISTS`
- `ANY`, `ALL` operators with subqueries

**Key Understanding:**
- When to use subqueries vs joins
- Performance implications of different approaches
- How correlated subqueries execute

**Practice Focus:**
- Join multiple related tables
- Use subqueries to filter based on aggregate conditions
- Compare values against sets of values

---

### **Before Q51-60: Window Functions & CTEs**
**New Concepts to Learn:**

**Window Functions:**
- `ROW_NUMBER()`, `RANK()`, `DENSE_RANK()`
- `PARTITION BY` clause
- `ORDER BY` within window functions
- `SUM()`, `COUNT()`, `AVG()` as window functions
- `LAG()`, `LEAD()` functions
- `FIRST_VALUE()`, `LAST_VALUE()`
- Window frames (`ROWS`, `RANGE`)

**Common Table Expressions (CTEs):**
- `WITH` clause syntax
- Creating temporary named result sets
- Multiple CTEs in one query
- Benefits over subqueries

**Practice Focus:**
- Rank data within groups
- Calculate running totals and moving averages
- Access previous/next row values
- Break complex queries into readable steps with CTEs

---

### **Before Q61-70: Conditional Logic & Advanced Filtering**
**New Concepts to Learn:**
- `CASE WHEN` statements (simple and searched)
- `COALESCE()` and `NULLIF()` functions
- `ISNULL()` or `NVL()` (database-specific)
- Advanced GROUP BY: `GROUPING SETS`, `ROLLUP`, `CUBE`
- Conditional aggregation with CASE
- `FILTER` clause (PostgreSQL) or conditional SUM/COUNT

**Key Understanding:**
- When to use CASE vs other conditional functions
- Creating custom grouping hierarchies
- Pivot-like operations using conditional aggregation

**Practice Focus:**
- Transform data based on conditions
- Create summary reports with subtotals
- Handle complex business logic in queries

---

### **Before Q71-80: Self-Joins & Recursive Queries**
**New Concepts to Learn:**
- Advanced self-join patterns
- Recursive Common Table Expressions (Recursive CTEs)
- `UNION` and `UNION ALL`
- Graph traversal in SQL
- Hierarchical data representation
- Tree structures in databases

**Key Understanding:**
- How recursive CTEs work (anchor + recursive member)
- When recursion is needed vs iterative approaches
- Preventing infinite recursion

**Practice Focus:**
- Work with hierarchical data (org charts, categories)
- Find connected components in graphs
- Generate sequences and series
- Navigate parent-child relationships

---

### **Before Q81-90: Performance Optimization**
**New Concepts to Learn:**
- Query execution plans (`EXPLAIN` / `EXPLAIN PLAN`)
- Index types and usage
- Query optimization techniques
- `ANALYZE` / `UPDATE STATISTICS`
- Join algorithms (hash, merge, nested loop)
- Partitioning strategies
- Materialized views
- Query hints (database-specific)

**Key Understanding:**
- How the query optimizer works
- Reading execution plans
- Identifying performance bottlenecks
- Cost-based vs rule-based optimization

**Practice Focus:**
- Analyze slow queries
- Design appropriate indexes
- Rewrite queries for better performance
- Use database-specific optimization features

---

### **Before Q91-100: Real-World Case Studies**
**Integration of All Previous Concepts:**
- Complex business requirements
- Multi-step analytical processes
- Data warehouse concepts (facts, dimensions)
- ETL patterns in SQL
- Advanced analytical functions
- Industry-specific calculations (financial, e-commerce, healthcare)
- Data quality and validation
- Reporting and dashboard queries

**Practice Focus:**
- Solve complete business problems
- Handle real-world data complexities
- Optimize end-to-end query performance
- Create maintainable, documented solutions

---

## 📖 **Recommended Study Resources by Module**

### **Books:**
- **Q1-40:** "SQL in 10 Minutes, Sams Teach Yourself" by Ben Forta
- **Q41-70:** "Learning SQL" by Alan Beaulieu  
- **Q71-100:** "SQL Antipatterns" by Bill Karwin

### **Online Resources:**
- **W3Schools SQL Tutorial** (Q1-30)
- **SQLZoo Interactive Tutorials** (Q1-50)
- **Mode Analytics SQL Tutorial** (Q31-80)
- **PostgreSQL Documentation** (Advanced topics)

### **Practice Platforms:**
- **DB Fiddle** - Test queries quickly
- **SQLiteOnline** - Practice without setup
- **Docker + PostgreSQL/MySQL** - Local development environment

---

## ⚡ **Study Tips for Each Module**

1. **Don't skip ahead** - Each concept builds on previous ones
2. **Practice daily** - Consistency beats intensity
3. **Understand, don't memorize** - Focus on concepts, not syntax
4. **Test edge cases** - What happens with NULLs, empty sets, duplicates?
5. **Optimize from the start** - Always consider performance
6. **Use real data** - Practice with meaningful datasets
7. **Explain your solutions** - If you can't explain it, you don't understand it

Happy learning! Each module should take 1-2 weeks to master before moving forward. 🚀
