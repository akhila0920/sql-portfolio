<h2><a href="https://leetcode.com/problems/get-the-second-most-recent-activity/description/">Get the Second Most Recent Activity</a></h2> <img src="https://img.shields.io/badge/Difficulty-Hard-red" alt="Difficulty: Hard" />

<hr>

<p>Table: <code>UserActivity</code></p>

<pre>
+---------------+---------+
| Column Name   | Type    |
+---------------+---------+
| username      | varchar |
| activity      | varchar |
| startDate     | Date    |
| endDate       | Date    |
+---------------+---------+
This table does not contain primary key.
This table contains information about the activity performed by each user in a period of time.
A person with username performed an activity from startDate to endDate.
</pre>


<p>Write an SQL query to show the second most recent activity of each user.</p>

<p>If the user only has one activity, return that one.</p>

<p>A user can't perform more than one activity at the same time. Return the result table in any order.</p>


<pre>

<strong>Input: </strong>

"UserActivity" table:

+------------+--------------+-------------+-------------+
| username   | activity     | startDate   | endDate     |
+------------+--------------+-------------+-------------+
| Alice      | Travel       | 2020-02-12  | 2020-02-20  |
| Alice      | Dancing      | 2020-02-21  | 2020-02-23  |
| Alice      | Travel       | 2020-02-24  | 2020-02-28  |
| Bob        | Travel       | 2020-02-11  | 2020-02-18  |
+------------+--------------+-------------+-------------+

<strong>Result Set: </strong>

+------------+--------------+-------------+-------------+
| username   | activity     | startDate   | endDate     |
+------------+--------------+-------------+-------------+
| Alice      | Dancing      | 2020-02-21  | 2020-02-23  |
| Bob        | Travel       | 2020-02-11  | 2020-02-18  |
+------------+--------------+-------------+-------------+
</pre>

<hr>

<h3>Maintainer</h3>
<p>
<strong>Akhila Abbagani</strong><br>
Data Analyst<br>
Email: abbaganiakhila0920@gmail.com
</p>

<p>
<strong>About the Developer</strong><br>
Akhila is a Data Analyst with 3+ years of experience delivering analytics, business intelligence, and cloud-based data solutions. She specializes in SQL, Python, and Azure data services to build scalable ETL pipelines and analytical data models. Her work focuses on transforming complex data into actionable insights and improving reporting efficiency through automation and cross-functional collaboration.
</p>