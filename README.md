# SQL-Learning-exercises
## Learning SQL from basic to complex queries
### SQL SELECT

Select all columns from 'Customers' table
```
SELECT *
FROM Customers
```

Select specific column/s from 'Customers' table
```
SELECT City
FROM Customers
```

Select unique values from specific column/s from 'Customers' table
```
SELECT DISTINCT Country
FROM Customers
```

### SQL WHERE

Select values which meet specific criteria
```
SELECT * FROM Customers
WHERE City = "Berlin"
```
