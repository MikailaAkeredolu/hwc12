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
```
