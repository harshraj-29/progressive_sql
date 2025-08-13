# 100 SQL Practice Questions - Progressive Learning Sequence

## Overview
This list contains 100 SQL practice questions arranged in a progressive learning sequence, starting from basic SELECT statements and advancing to complex real-world scenarios. Each question builds upon previously introduced concepts without jumping ahead.

## Learning Path Structure
- **Q1-Q10:** SELECT basics, filtering, sorting
- **Q11-Q20:** Aggregate functions and grouping
- **Q21-Q30:** String and date functions
- **Q31-Q40:** Basic joins
- **Q41-Q50:** Advanced joins and subqueries
- **Q51-Q60:** Window functions and CTEs
- **Q61-Q70:** Conditional logic and advanced filtering
- **Q71-Q80:** Self-joins and recursive queries
- **Q81-Q90:** Performance optimization
- **Q91-Q100:** Real-world case studies

---

| # | Title | Concept(s) | Difficulty | Source | Link | Problem Summary |
|---|-------|------------|------------|--------|------|-----------------|
| 1 | Recyclable and Low Fat Products | SELECT, WHERE | Easy | LeetCode | [Link](https://leetcode.com/problems/recyclable-and-low-fat-products/) | Find products that are both recyclable and low fat from product table |
| 2 | Find Customer Referee | SELECT, WHERE, NULL handling | Easy | LeetCode | [Link](https://leetcode.com/problems/find-customer-referee/) | Select customers not referred by customer with id 2 |
| 3 | Big Countries | SELECT, WHERE, OR conditions | Easy | LeetCode | [Link](https://leetcode.com/problems/big-countries/) | Find countries with large area OR population |
| 4 | Article Views I | SELECT, WHERE, DISTINCT | Easy | LeetCode | [Link](https://leetcode.com/problems/article-views-i/) | Find authors who viewed their own articles |
| 5 | Invalid Tweets | SELECT, WHERE, LENGTH function | Easy | LeetCode | [Link](https://leetcode.com/problems/invalid-tweets/) | Find tweets with more than 15 characters |
| 6 | Replace Employee ID | SELECT, ORDER BY | Easy | LeetCode | [Link](https://leetcode.com/problems/replace-employee-id-with-the-unique-identifier/) | Join employees with unique identifiers, handle nulls |
| 7 | Product Sales Analysis I | SELECT, basic filtering | Easy | LeetCode | [Link](https://leetcode.com/problems/product-sales-analysis-i/) | Get product name, year, and price from sales data |
| 8 | Customer Who Visited | SELECT, WHERE conditions | Easy | LeetCode | [Link](https://leetcode.com/problems/customer-who-visited-but-did-not-make-any-transactions/) | Find customers who visited but didn't make transactions |
| 9 | Rising Temperature | SELECT, WHERE, date comparison | Easy | LeetCode | [Link](https://leetcode.com/problems/rising-temperature/) | Find dates with higher temperature than previous day |
| 10 | Average Time Process | SELECT, ORDER BY, LIMIT | Easy | LeetCode | [Link](https://leetcode.com/problems/average-time-of-process-per-machine/) | Calculate average processing time per machine |
| 11 | Employee Bonus | SELECT, SUM | Easy | LeetCode | [Link](https://leetcode.com/problems/employee-bonus/) | Find employees with bonus less than 1000 |
| 12 | Students and Examinations | COUNT, GROUP BY | Easy | LeetCode | [Link](https://leetcode.com/problems/students-and-examinations/) | Count exam attempts per student per subject |
| 13 | Managers with 5+ Reports | COUNT, GROUP BY, HAVING | Medium | LeetCode | [Link](https://leetcode.com/problems/managers-with-at-least-5-direct-reports/) | Find managers with at least 5 direct reports |
| 14 | Confirmation Rate | AVG, GROUP BY | Medium | LeetCode | [Link](https://leetcode.com/problems/confirmation-rate/) | Calculate confirmation rate for each user |
| 15 | Not Boring Movies | SELECT, WHERE, aggregates | Easy | LeetCode | [Link](https://leetcode.com/problems/not-boring-movies/) | Find odd-numbered movies that aren't boring |
| 16 | Average Selling Price | AVG, SUM, mathematical operations | Easy | LeetCode | [Link](https://leetcode.com/problems/average-selling-price/) | Calculate average selling price per product |
| 17 | Project Employees I | AVG, ROUND, GROUP BY | Easy | LeetCode | [Link](https://leetcode.com/problems/project-employees-i/) | Calculate average experience years per project |
| 18 | Percentage Users Attended | COUNT, percentage calculation | Medium | LeetCode | [Link](https://leetcode.com/problems/percentage-of-users-attended-a-contest/) | Calculate attendance percentage by contest |
| 19 | Queries Quality and Percentage | AVG, conditional aggregation | Medium | LeetCode | [Link](https://leetcode.com/problems/queries-quality-and-percentage/) | Calculate query quality and poor query percentage |
| 20 | Monthly Transactions I | COUNT, SUM, GROUP BY month | Medium | LeetCode | [Link](https://leetcode.com/problems/monthly-transactions-i/) | Group transactions by country and month |
| 21 | Immediate Food Delivery II | String functions, date comparison | Medium | LeetCode | [Link](https://leetcode.com/problems/immediate-food-delivery-ii/) | Find percentage of immediate orders for first orders |
| 22 | Game Play Analysis IV | Date functions, LAG window function | Hard | LeetCode | [Link](https://leetcode.com/problems/game-play-analysis-iv/) | Calculate fraction of players logging in day after first login |
| 23 | Number of Unique Subjects | String manipulation, DISTINCT | Medium | StrataScratch | [Link](https://platform.stratascratch.com/coding/10311-find-the-percentage-of-shipable-orders) | Count unique subjects taught by each teacher |
| 24 | Customer Order Frequency | Date functions, conditional aggregation | Medium | LeetCode | [Link](https://leetcode.com/problems/customer-order-frequency/) | Find customers who ordered in consecutive months |
| 25 | Fix Names in a Table | String functions (UPPER, LOWER, SUBSTRING) | Easy | LeetCode | [Link](https://leetcode.com/problems/fix-names-in-a-table/) | Fix capitalization of names |
| 26 | Group Sold Products By Date | String aggregation, CONCAT | Easy | LeetCode | [Link](https://leetcode.com/problems/group-sold-products-by-the-date/) | Group products sold by date with concatenated names |
| 27 | Patients with a Condition | String pattern matching, LIKE | Easy | LeetCode | [Link](https://leetcode.com/problems/patients-with-a-condition/) | Find patients with specific condition codes |
| 28 | Calculate Special Bonus | String functions, conditional logic | Easy | LeetCode | [Link](https://leetcode.com/problems/calculate-special-bonus/) | Calculate bonus based on employee ID and name criteria |
| 29 | Delete Duplicate Emails | String comparison, DELETE operation | Easy | LeetCode | [Link](https://leetcode.com/problems/delete-duplicate-emails/) | Remove duplicate email records keeping lowest ID |
| 30 | Second Highest Salary | String/numeric functions, subqueries | Medium | LeetCode | [Link](https://leetcode.com/problems/second-highest-salary/) | Find second highest salary using LIMIT and OFFSET |
| 31 | Customers Who Never Order | INNER JOIN, IS NULL | Easy | LeetCode | [Link](https://leetcode.com/problems/customers-who-never-order/) | Find customers with no orders using LEFT JOIN |
| 32 | Combine Two Tables | LEFT JOIN basics | Easy | LeetCode | [Link](https://leetcode.com/problems/combine-two-tables/) | Join person and address tables |
| 33 | Employee Earning More | Self JOIN, comparison | Easy | LeetCode | [Link](https://leetcode.com/problems/employees-earning-more-than-their-managers/) | Find employees earning more than their managers |
| 34 | Duplicate Emails | GROUP BY, HAVING with JOIN | Easy | LeetCode | [Link](https://leetcode.com/problems/duplicate-emails/) | Find duplicate email addresses |
| 35 | Customers Bought All Products | JOIN, GROUP BY, COUNT comparison | Hard | LeetCode | [Link](https://leetcode.com/problems/customers-who-bought-all-products/) | Find customers who bought all available products |
| 36 | Rising Temperature (JOIN version) | Self JOIN, date arithmetic | Easy | LeetCode | [Link](https://leetcode.com/problems/rising-temperature/) | Find dates with temperature higher than previous day using JOIN |
| 37 | Tree Node | INNER JOIN, conditional logic | Medium | LeetCode | [Link](https://leetcode.com/problems/tree-node/) | Classify tree nodes as root, leaf, or inner |
| 38 | Exchange Seats | JOIN with mathematical operations | Medium | LeetCode | [Link](https://leetcode.com/problems/exchange-seats/) | Swap adjacent student seats |
| 39 | Sales Person | Multiple JOINs, filtering | Easy | LeetCode | [Link](https://leetcode.com/problems/sales-person/) | Find salespeople who never sold to Red company |
| 40 | Triangle Judgement | JOIN conditions, mathematical logic | Easy | LeetCode | [Link](https://leetcode.com/problems/triangle-judgement/) | Determine if three sides can form a triangle |
| 41 | Classes More Than 5 Students | Advanced GROUP BY, subqueries | Easy | LeetCode | [Link](https://leetcode.com/problems/classes-more-than-5-students/) | Find classes with 5+ students using subquery |
| 42 | Human Traffic of Stadium | Multiple JOINs, consecutive records | Hard | LeetCode | [Link](https://leetcode.com/problems/human-traffic-of-stadium/) | Find 3+ consecutive days with 100+ people |
| 43 | Department Highest Salary | Subquery in WHERE clause | Medium | LeetCode | [Link](https://leetcode.com/problems/department-highest-salary/) | Find employees with highest salary in each department |
| 44 | Department Top Three Salaries | Correlated subquery, ranking | Hard | LeetCode | [Link](https://leetcode.com/problems/department-top-three-salaries/) | Find top 3 salaries in each department |
| 45 | Trips and Users | Complex JOINs, conditional aggregation | Hard | LeetCode | [Link](https://leetcode.com/problems/trips-and-users/) | Calculate cancellation rates for unbanned users |
| 46 | Game Play Analysis III | Subqueries, running totals | Medium | LeetCode | [Link](https://leetcode.com/problems/game-play-analysis-iii/) | Calculate running sum of games played |
| 47 | Friend Requests II | Multiple subqueries, set operations | Medium | LeetCode | [Link](https://leetcode.com/problems/friend-requests-ii-who-has-the-most-friends/) | Find person with most friends |
| 48 | Investments in 2016 | Complex WHERE subqueries | Medium | LeetCode | [Link](https://leetcode.com/problems/investments-in-2016/) | Sum investments with specific location/premium criteria |
| 49 | Customer Placing Largest Orders | Subqueries with aggregation | Easy | LeetCode | [Link](https://leetcode.com/problems/customer-placing-the-largest-number-of-orders/) | Find customer with most orders |
| 50 | Biggest Single Number | Subquery filtering, MAX function | Easy | LeetCode | [Link](https://leetcode.com/problems/biggest-single-number/) | Find largest number that appears only once |
| 51 | Rank Scores | ROW_NUMBER(), DENSE_RANK() | Medium | LeetCode | [Link](https://leetcode.com/problems/rank-scores/) | Rank scores without gaps |
| 52 | Consecutive Numbers | Window functions, LAG/LEAD | Medium | LeetCode | [Link](https://leetcode.com/problems/consecutive-numbers/) | Find numbers appearing 3+ times consecutively |
| 53 | Nth Highest Salary | Window functions, NTILE | Medium | LeetCode | [Link](https://leetcode.com/problems/nth-highest-salary/) | Find Nth highest salary using window functions |
| 54 | Department Top 3 Salaries (Window) | DENSE_RANK(), PARTITION BY | Hard | LeetCode | [Link](https://leetcode.com/problems/department-top-three-salaries/) | Top 3 salaries per department using window functions |
| 55 | Median Employee Salary | PERCENTILE_CONT, window functions | Hard | LeetCode | [Link](https://leetcode.com/problems/median-employee-salary/) | Calculate median salary per company |
| 56 | Running Total Revenue | SUM() OVER, window frames | Medium | StrataScratch | [Link](https://platform.stratascratch.com/coding/9991-top-ranked-songs) | Calculate running total of revenue |
| 57 | Customer Order Analysis | CTE, window functions | Medium | Mode Analytics | [Link](https://mode.com/sql-tutorial/sql-window-functions/) | Analyze customer ordering patterns |
| 58 | Sales Growth Rate | CTE, LAG function, percentage calculation | Hard | StrataScratch | [Link](https://platform.stratascratch.com/coding/9905-highest-target-under-manager) | Calculate month-over-month growth rates |
| 59 | Employee Hierarchy | Recursive CTE basics | Hard | HackerRank | [Link](https://www.hackerrank.com/challenges/15-days-of-learning-sql) | Find employee reporting structure |
| 60 | Monthly Active Users | CTE, date functions, window functions | Medium | StrataScratch | [Link](https://platform.stratascratch.com/coding/10322-finding-user-purchases) | Calculate monthly active user metrics |
| 61 | Weather Observation 20 | CASE WHEN, conditional aggregation | Medium | HackerRank | [Link](https://www.hackerrank.com/challenges/weather-observation-station-20) | Calculate weather statistics with conditions |
| 62 | Binary Tree Nodes | CASE WHEN, complex conditions | Medium | HackerRank | [Link](https://www.hackerrank.com/challenges/binary-search-tree-1) | Classify binary tree node types |
| 63 | The PADS | CASE WHEN, string concatenation | Medium | HackerRank | [Link](https://www.hackerrank.com/challenges/the-pads) | Format names with profession indicators |
| 64 | Occupations | PIVOT operation, conditional logic | Hard | HackerRank | [Link](https://www.hackerrank.com/challenges/occupations) | Pivot occupation data into columns |
| 65 | New Companies | Complex CASE conditions | Medium | HackerRank | [Link](https://www.hackerrank.com/challenges/the-company) | Count employees by hierarchy level |
| 66 | Contest Leaderboard | CASE WHEN, advanced grouping | Hard | HackerRank | [Link](https://www.hackerrank.com/challenges/contest-leaderboard) | Calculate contest scores with maximum submission rule |
| 67 | SQL Project Planning | Advanced CASE logic | Medium | HackerRank | [Link](https://www.hackerrank.com/challenges/sql-projects) | Find project start and end dates |
| 68 | Placements | CASE WHEN with JOINs | Medium | HackerRank | [Link](https://www.hackerrank.com/challenges/placements) | Compare friend vs student salaries |
| 69 | Symmetric Pairs | CASE conditions, pair matching | Medium | HackerRank | [Link](https://www.hackerrank.com/challenges/symmetric-pairs) | Find symmetric coordinate pairs |
| 70 | Weather Station 18 | CASE WHEN, mathematical calculations | Medium | HackerRank | [Link](https://www.hackerrank.com/challenges/weather-observation-station-18) | Calculate Manhattan distance |
| 71 | Employee Names | Self JOIN basics | Easy | HackerRank | [Link](https://www.hackerrank.com/challenges/more-than-75-marks) | Find students with specific name patterns |
| 72 | Top Competitors | Self JOIN, multiple conditions | Medium | HackerRank | [Link](https://www.hackerrank.com/challenges/full-score) | Find hackers with perfect scores |
| 73 | Ollivander's Inventory | Self JOIN optimization | Medium | HackerRank | [Link](https://www.hackerrank.com/challenges/harry-potter-and-wands) | Find minimum cost wands with power requirements |
| 74 | Challenges | Self JOIN with aggregation | Medium | HackerRank | [Link](https://www.hackerrank.com/challenges/challenges) | Count challenges created by each hacker |
| 75 | Contest Performance | Self JOIN, complex filtering | Hard | StrataScratch | [Link](https://platform.stratascratch.com/coding/9632-host-popularity-rental-prices) | Analyze contest performance comparisons |
| 76 | Print Prime Numbers | Self JOIN for mathematical operations | Hard | HackerRank | [Link](https://www.hackerrank.com/challenges/print-prime-numbers) | Generate prime numbers using SQL |
| 77 | Recursive Employee Hierarchy | Recursive CTE advanced | Hard | Mode Analytics | [Link](https://mode.com/sql-tutorial/sql-recursive-cte/) | Build complete organizational chart |
| 78 | Family Tree Relations | Recursive CTE, genealogy | Hard | StrataScratch | [Link](https://platform.stratascratch.com/coding/9899-percentage-of-total-spend) | Map family relationships recursively |
| 79 | Route Planning | Recursive CTE, graph traversal | Hard | LeetCode | [Link](https://leetcode.com/problems/all-paths-from-source-to-target/) | Find all possible routes between cities |
| 80 | Fibonacci Sequence | Recursive CTE, mathematical sequences | Hard | HackerRank | [Link](https://www.hackerrank.com/challenges/fibonacci-modified) | Generate Fibonacci numbers in SQL |
| 81 | Query Optimization 1 | Index hints, EXPLAIN PLAN | Hard | Mode Analytics | [Link](https://mode.com/sql-tutorial/sql-performance-tuning/) | Optimize slow running queries using indexes |
| 82 | Partition Pruning | Table partitioning, performance | Hard | StrataScratch | [Link](https://platform.stratascratch.com/coding/9913-order-details) | Use partition elimination for faster queries |
| 83 | Memory Usage Analysis | Query performance, execution plans | Hard | PostgreSQL Tutorial | [Link](https://www.postgresqltutorial.com/postgresql-performance-tips/) | Analyze memory consumption in queries |
| 84 | Index Strategy | Index design, covering indexes | Hard | SQLZoo | [Link](https://sqlzoo.net/wiki/Window_functions) | Design optimal indexing strategy |
| 85 | Bulk Data Processing | Performance optimization, batch processing | Hard | Mode Analytics | [Link](https://mode.com/sql-tutorial/sql-data-types/) | Process large datasets efficiently |
| 86 | Statistics Update | Query optimization, statistics | Hard | StrataScratch | [Link](https://platform.stratascratch.com/coding/9728-inspections-that-resulted-in-violations) | Optimize queries using table statistics |
| 87 | Materialized Views | Performance, view optimization | Hard | PostgreSQL Docs | [Link](https://www.postgresql.org/docs/current/rules-materializedviews.html) | Use materialized views for performance |
| 88 | Query Parallelization | Parallel processing, performance tuning | Hard | Oracle Docs | [Link](https://docs.oracle.com/en/database/oracle/oracle-database/19/vldbg/parallel-exec-intro.html) | Optimize queries for parallel execution |
| 89 | Memory-Efficient Joins | JOIN optimization, hash vs merge | Hard | MySQL Performance | [Link](https://dev.mysql.com/doc/refman/8.0/en/nested-loop-joins.html) | Choose optimal JOIN algorithms |
| 90 | Cost-Based Optimization | Query planner, cost estimation | Hard | StrataScratch | [Link](https://platform.stratascratch.com/coding/9782-customer-revenue-in-march) | Understand and influence query execution plans |
| 91 | E-commerce Analytics | Real-world case study, all concepts | Hard | StrataScratch | [Link](https://platform.stratascratch.com/coding/9913-order-details) | Complete e-commerce sales analysis |
| 92 | Social Media Insights | Complex analytics, user behavior | Hard | Mode Analytics | [Link](https://mode.com/sql-tutorial/sql-business-analytics-training/) | Analyze social media engagement patterns |
| 93 | Financial Reporting | Financial calculations, regulatory compliance | Hard | StrataScratch | [Link](https://platform.stratascratch.com/coding/9663-find-the-most-profitable-company-in-the-financial-sector-of-the-entire-world) | Generate comprehensive financial reports |
| 94 | Supply Chain Analysis | Multi-table analysis, logistics | Hard | LeetCode | [Link](https://leetcode.com/problems/market-analysis-i/) | Optimize supply chain operations |
| 95 | Customer Lifetime Value | Advanced analytics, predictive modeling | Hard | StrataScratch | [Link](https://platform.stratascratch.com/coding/9663-find-the-most-profitable-company-in-the-financial-sector-of-the-entire-world) | Calculate and segment customer lifetime value |
| 96 | Healthcare Data Analysis | Healthcare domain, privacy considerations | Hard | Mode Analytics | [Link](https://mode.com/sql-tutorial/sql-business-analytics-training/) | Analyze patient outcomes and treatment efficacy |
| 97 | Marketing Campaign ROI | Marketing analytics, attribution modeling | Hard | StrataScratch | [Link](https://platform.stratascratch.com/coding/9728-inspections-that-resulted-in-violations) | Measure marketing campaign effectiveness |
| 98 | Fraud Detection System | Anomaly detection, pattern recognition | Hard | LeetCode | [Link](https://leetcode.com/problems/human-traffic-of-stadium/) | Identify fraudulent transaction patterns |
| 99 | Time Series Forecasting | Advanced time series, statistical functions | Hard | Mode Analytics | [Link](https://mode.com/sql-tutorial/sql-window-functions/) | Forecast future trends using historical data |
| 100 | Data Warehouse ETL | Complete ETL process, data integration | Hard | StrataScratch | [Link](https://platform.stratascratch.com/coding/9913-order-details) | Design and implement full ETL pipeline |

---

## Study Tips

1. **Follow the sequence** - Each question builds on previous concepts
2. **Practice regularly** - Aim for 2-3 questions per day
3. **Understand concepts** - Don't just memorize solutions
4. **Test different approaches** - Many problems have multiple valid solutions
5. **Focus on optimization** - Always consider query performance
6. **Use real data** - Practice with realistic datasets when possible

## Additional Resources

- **Platform Access**: Most questions are free on LeetCode, HackerRank, and SQLZoo
- **SQL Documentation**: Refer to official docs for your target database system
- **Practice Environment**: Use DB Fiddle, SQLiteOnline, or local database setup
- **Community**: Join SQL communities on Reddit, Stack Overflow, and platform-specific forums

Happy learning! 🚀
