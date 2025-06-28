# [584. Find Customer Referee](https://leetcode.com/problems/find-customer-referee/description/)

Solution:
```sql
SELECT name FROM Customer
WHERE referee_id != 2 
OR referee_id IS NULL;
```

Brief Explanation:

> 1. I used the select statement to select the 'name' column 'FROM' the 'Customer' table.
> 2. The 'WHERE' clause filters using the Operations.

Important Lesson from this:
> 1. I first wrote the query without the NULL check, and my code run into an error.
> 2. Its important to check the NULL case when working with such tables.
