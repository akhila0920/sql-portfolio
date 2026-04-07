<h2><a href="https://leetcode.com/problems/department-highest-salary">Department Highest Salary</a></h2> <img src='https://img.shields.io/badge/Difficulty-Medium-orange' alt='Difficulty: Medium' /><hr><p>Table: <code>Employee</code></p>

<pre>
+--------------+---------+
| Column Name  | Type    |
+--------------+---------+
| id           | int     |
| name         | varchar |
| salary       | int     |
| departmentId | int     |
+--------------+---------+
id is the primary key (column with unique values) for this table.
departmentId is a foreign key (reference columns) of the ID from the <code>Department </code>table.
Each row of this table indicates the ID, name, and salary of an employee. It also contains the ID of their department.
</pre>

<p>&nbsp;</p>

<p>Table: <code>Department</code></p>

<pre>
+-------------+---------+
| Column Name | Type    |
+-------------+---------+
| id          | int     |
| name        | varchar |
+-------------+---------+
id is the primary key (column with unique values) for this table. It is guaranteed that department name is not <code>NULL.</code>
Each row of this table indicates the ID of a department and its name.
</pre>

<p>&nbsp;</p>

<p>Write a solution to find employees who have the highest salary in each of the departments.</p>

<p>Return the result table in <strong>any order</strong>.</p>

<p>The result format is in the following example.</p>

<p>&nbsp;</p>
<p><strong class="example">Example 1:</strong></p>

<pre>
<strong>Input:</strong> 
Employee table:
+----+-------+--------+--------------+
| id | name  | salary | departmentId |
+----+-------+--------+--------------+
| 1  | Joe   | 70000  | 1            |
| 2  | Jim   | 90000  | 1            |
| 3  | Henry | 80000  | 2            |
| 4  | Sam   | 60000  | 2            |
| 5  | Max   | 90000  | 1            |
+----+-------+--------+--------------+
Department table:
+----+-------+
| id | name  |
+----+-------+
| 1  | IT    |
| 2  | Sales |
+----+-------+
<strong>Output:</strong> 
+------------+----------+--------+
| Department | Employee | Salary |
+------------+----------+--------+
| IT         | Jim      | 90000  |
| Sales      | Henry    | 80000  |
| IT         | Max      | 90000  |
+------------+----------+--------+
<strong>Explanation:</strong> Max and Jim both have the highest salary in the IT department and Henry has the highest salary in the Sales department.
</pre>

<hr>

<h3>Maintainer</h3>
<p><strong>Akhila Abbagani</strong><br>
Data Analyst<br>
Email: abbaganiakhila0920@gmail.com</p>

<p>Data Analyst with 3+ years of experience specializing in SQL, Python, and cloud-based data solutions. This repository contains technical implementations and solutions for complex data modeling and analytical challenges, focusing on efficiency and scalability in data-driven environments.</p>