<h2><a href="https://leetcode.com/problems/rising-temperature">Rising Temperature</a></h2> <img src="https://img.shields.io/badge/Difficulty-Easy-brightgreen" alt="Difficulty: Easy" /><hr><p>Table: <code>Weather</code></p>

<pre>
+---------------+---------+
| Column Name   | Type    |
+---------------+---------+
| id            | int     |
| recordDate    | date    |
| temperature   | int     |
+---------------+---------+
id is the column with unique values for this table.
This table contains information about the temperature on a certain day.
</pre>

<p> </p>

<p>Write a solution to find all dates' <code>Id</code> with higher temperatures compared to its previous dates (yesterday).</p>

<p>Return the result table in <strong>any order</strong>.</p>

<p>The result format is in the following example.</p>

<p> </p>
<p><strong class="example">Example 1:</strong></p>

<pre>
<strong>Input:</strong> 
Weather table:
+----+------------+-------------+
| id | recordDate | temperature |
+----+------------+-------------+
| 1  | 2015-01-01 | 10          |
| 2  | 2015-01-02 | 25          |
| 3  | 2015-01-03 | 20          |
| 4  | 2015-01-04 | 30          |
+----+------------+-------------+
<strong>Output:</strong> 
+----+
| id |
+----+
| 2  |
| 4  |
+----+
<strong>Explanation:</strong> 
In 2015-01-02, the temperature was higher than the previous day (10 -> 25).
In 2015-01-04, the temperature was higher than the previous day (20 -> 30).
</pre>

<hr>

### Maintainer

**Akhila Abbagani**
Data Analyst
Email: abbaganiakhila0920@gmail.com

Data Analyst with 3+ years of experience delivering analytics, business intelligence, and cloud-based data solutions across healthcare and insurance domains. This repository is part of a collection of SQL and data analysis solutions focused on building scalable ETL pipelines and transforming complex data into actionable insights.

**Key Technical Skills:**
- Languages: SQL, Python (Pandas, NumPy, Scikit-learn)
- Tools: Power BI, Snowflake, Azure Databricks, Azure Data Factory, Azure Synapse Analytics
- Expertise: ETL Pipelines, Data Modeling, Automation, and Business Intelligence