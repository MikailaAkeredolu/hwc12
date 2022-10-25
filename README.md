# Andrew

```
select quantity, COUNT(*) from products GROUP BY quantity;
+----------+----------+
| quantity | COUNT(*) |
+----------+----------+
|     5000 |        1 |
|     8000 |        2 |
|     2000 |        1 |
|    10000 |        1 |
+----------+----------+


select * from products WHERE productID < 1004 AND price > 1.20 ORDER BY productID DESC;
+-----------+-------------+-----------+----------+-------+
| productID | productCode | name      | quantity | price |
+-----------+-------------+-----------+----------+-------+
|      1003 | PEN         | Pen Black |     2000 |  1.25 |
|      1002 | PEN         | Pen Blue  |     8000 |  1.25 |
|      1001 | PEN         | Pen Red   |     5000 |  1.23 |
+-----------+-------------+-----------+----------+-------+




```
