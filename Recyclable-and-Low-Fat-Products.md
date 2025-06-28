# [1757. Recyclable and Low Fat Products](https://leetcode.com/problems/recyclable-and-low-fat-products/description/)

Solution:

```sql
SELECT product_id 
FROM Products 
WHERE recyclable = 'Y'
AND low_fats = 'Y'

```
Brief Explanation:

> 1. I used the SELECT statement to select the column named 'product_id' FROM the 'Products' table.
> 2. I then used the 'WHERE' clause to filter which products are recyclable and low_fats by combining the 2 boolean statements with the 'AND' operator.
> 3. The filter returns only rows that are true for both statements.

