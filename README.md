# SQL-Learning-exercises
## Learning SQL from basic to complex queries
### SQL SELECT

*Select all columns from 'Customers' table*
```
SELECT *
FROM Customers
```

*Select specific column/s from 'Customers' table*
```
SELECT City
FROM Customers
```

*Select unique values from specific column/s from 'Customers' table*
```
SELECT DISTINCT Country
FROM Customers
```

### SQL WHERE

*Select records which meet specific criteria*
```
SELECT * FROM Customers
WHERE City = "Berlin"
```

*Select records which do not meet specific crieria*
```
SELECT * FROM Customers
WHERE NOT City = 'Berlin'
```

*Select records which match a specific value*
```
SELECT * FROM Customers
WHERE CustomerID = 32
```

*Select records with multiple columns matching specific criteria*
```
SELECT *
FROM Customers
WHERE City = 'Berlin'
AND PostalCode = 12209
 ```
 
 *Select records matching either criteria*
 ```
 SELECT *
 FROM Customers
 WHERE City = 'Berlin'
 OR City = 'London'
```
