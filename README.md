# week-2-assigment-data-base-


### ✅ 1. **Retrieve `checkNumber`, `paymentDate`, and `amount` from `payments` table**
```sql
SELECT checkNumber, paymentDate, amount
FROM payments;
```

---

### ✅ 2. **Retrieve `orderDate`, `requiredDate`, and `status` of orders 'In Process', sorted by `orderDate` descending**
```sql
SELECT orderDate, requiredDate, status
FROM orders
WHERE status = 'In Process'
ORDER BY orderDate DESC;
```

---

### ✅ 3. **Display `firstName`, `lastName`, and `email` of employees with job title 'Sales Rep', ordered by `employeeNumber` descending**
```sql
SELECT firstName, lastName, email
FROM employees
WHERE jobTitle = 'Sales Rep'
ORDER BY employeeNumber DESC;
```

---

### ✅ 4. **Retrieve all columns and records from `offices` table**
```sql
SELECT * 
FROM offices;
```

---

### ✅ 5. **Fetch `productName` and `quantityInStock` from `products`, sort by `buyPrice` ascending, limit to 5 records**
```sql
SELECT productName, quantityInStock
FROM products
ORDER BY buyPrice ASC
LIMIT 5;
