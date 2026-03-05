<h2><a href="https://leetcode.com/problems/rearrange-products-table">Rearrange Products Table</a></h2> <img src="https://img.shields.io/badge/Difficulty-Easy-brightgreen" alt="Difficulty: Easy" /><hr><p>Table: <code>Products</code></p>

<pre>
+-------------+---------+
| Column Name | Type    |
+-------------+---------+
| product_id  | int     |
| store1      | int     |
| store2      | int     |
| store3      | int     |
+-------------+---------+
product_id is the primary key (column with unique values) for this table.
Each row in this table indicates the product's price in 3 different stores: store1, store2, and store3.
If the product is not available in a store, the price will be null in that store's column.
</pre>

<p>Write a solution to rearrange the <code>Products</code> table so that each row has <code>(product_id, store, price)</code>. If a product is not available in a store, do <strong>not</strong> include a row with that <code>product_id</code> and <code>store</code> combination in the result table.</p>

<p>Return the result table in <strong>any order</strong>.</p>

<p>The result format is in the following example.</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> 
Products table:
+------------+--------+--------+--------+
| product_id | store1 | store2 | store3 |
+------------+--------+--------+--------+
| 0          | 95     | 100    | 105    |
| 1          | 70     | null   | 80     |
+------------+--------+--------+--------+
<strong>Output:</strong> 
+------------+--------+-------+
| product_id | store  | price |
+------------+--------+-------+
| 0          | store1 | 95    |
| 0          | store2 | 100   |
| 0          | store3 | 105   |
| 1          | store1 | 70    |
| 1          | store3 | 80    |
+------------+--------+-------+
<strong>Explanation:</strong> 
Product 0 is available in all three stores with prices 95, 100, and 105 respectively.
Product 1 is available in store1 with price 70 and store3 with price 80. The product is not available in store2.
</pre>

<hr>

<h3>Maintainer</h3>

<p>
<strong>Akhila Abbagani</strong><br>
Data Analyst
</p>

<p>
Data Analyst with 3+ years of experience delivering analytics, business intelligence, and cloud-based data solutions across healthcare and insurance domains. Experienced in SQL, Python, Power BI, Snowflake, Azure Databricks, Azure Data Factory, and Azure Synapse Analytics for building scalable ETL pipelines and analytical data models.
</p>

<p>
<strong>Key Skills:</strong> Python, SQL, DAX, Pandas, NumPy, Scikit-learn<br>
<strong>Email:</strong> abbaganiakhila0920@gmail.com
</p>