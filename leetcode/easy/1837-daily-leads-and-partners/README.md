<h2><a href="https://leetcode.com/problems/daily-leads-and-partners">Daily Leads and Partners</a></h2> <img src="https://img.shields.io/badge/Difficulty-Easy-brightgreen" alt="Difficulty: Easy" /><hr><p>Table: <code>DailySales</code></p>

<pre>
+-------------+---------+
| Column Name | Type    |
+-------------+---------+
| date_id     | date    |
| make_name   | varchar |
| lead_id     | int     |
| partner_id  | int     |
+-------------+---------+
There is no primary key (column with unique values) for this table. It may contain duplicates.
This table contains the date and the name of the product sold and the IDs of the lead and partner it was sold to.
The name consists of only lowercase English letters.
</pre>

<p> </p>

<p>For each <code>date_id</code> and <code>make_name</code>, find the number of <strong>distinct</strong> <code>lead_id</code>'s and <strong>distinct</strong> <code>partner_id</code>'s.</p>

<p>Return the result table in <strong>any order</strong>.</p>

<p>The result format is in the following example.</p>

<p> </p>
<p><strong class="example">Example 1:</strong></p>

<pre>
<strong>Input:</strong> 
DailySales table:
+-----------+-----------+---------+------------+
| date_id   | make_name | lead_id | partner_id |
+-----------+-----------+---------+------------+
| 2020-12-8 | toyota    | 0       | 1          |
| 2020-12-8 | toyota    | 1       | 0          |
| 2020-12-8 | toyota    | 1       | 2          |
| 2020-12-7 | toyota    | 0       | 2          |
| 2020-12-7 | toyota    | 0       | 1          |
| 2020-12-8 | honda     | 1       | 2          |
| 2020-12-8 | honda     | 2       | 1          |
| 2020-12-7 | honda     | 0       | 1          |
| 2020-12-7 | honda     | 1       | 2          |
| 2020-12-7 | honda     | 2       | 1          |
+-----------+-----------+---------+------------+
<strong>Output:</strong> 
+-----------+-----------+--------------+-----------------+
| date_id   | make_name | unique_leads | unique_partners |
+-----------+-----------+--------------+-----------------+
| 2020-12-8 | toyota    | 2            | 3               |
| 2020-12-7 | toyota    | 1            | 2               |
| 2020-12-8 | honda     | 2            | 2               |
| 2020-12-7 | honda     | 3            | 2               |
+-----------+-----------+--------------+-----------------+
<strong>Explanation:</strong> 
For 2020-12-8, toyota gets leads = [0, 1] and partners = [0, 1, 2] while honda gets leads = [1, 2] and partners = [1, 2].
For 2020-12-7, toyota gets leads = [0] and partners = [1, 2] while honda gets leads = [0, 1, 2] and partners = [1, 2].
</pre>

<hr>

### About the Developer

This project is maintained by **Akhila Abbagani**, a Data Analyst with over 3 years of experience in delivering analytics and business intelligence solutions. With a strong background in SQL, Python, and cloud-based data platforms like Snowflake and Azure, Akhila specializes in transforming complex datasets into actionable business insights through automated ETL pipelines and interactive reporting.

**Contact Information:**
- **Email:** abbaganiakhila0920@gmail.com
- **Role:** Data Analyst
- **Skills:** SQL, Python, Power BI, Snowflake, Azure Data Factory, Pandas, NumPy