1-SELECT CustomerName, City, Country 
FROM Customers
LIMIT 5

2-SELECT *
FROM OrderDetails
WHERE Quantity > 10
Order by OrderID
LIMIT 3

3-SELECT *
FROM OrderDetails
WHERE Quantity > 10
Order by Quantity desc
LIMIT 7

4-SELECT * 
FROM Products 
WHERE ProductID = 4
LIMIT 10

5-SELECT OrderID
FROM OrderDetails
Order by OrderDetailID
LIMIT 2

6-SELECT *
FROM OrderDetails
Order by Quantity
LIMIT 15

7-SELECT ProductID,
Quantity
FROM OrderDetails
Order by Quantity 
LIMIT 20

8-SELECT OrderDetailID,
Quantity
FROM OrderDetails
Order by Quantity DESC
LIMIT 8

9-SELECT *
FROM OrderDetails
WHERE ProductID > 3
Order by OrderID 
LIMIT 5

10-SELECT OrderID,
Quantity
FROM OrderDetails
ORDER BY OrderID,
Quantity
LIMIT 10

11-SELECT *
FROM OrderDetails
WHERE Quantity < 15
ORDER BY Quantity
LIMIT 12

12-SELECT *
FROM OrderDetails
WHERE ProductID % 2=0
ORDER BY Quantity
LIMIT 6

13-SELECT *
FROM OrderDetails
WHERE ProductID > 0
ORDER BY ProductID desc
LIMIT 5

14-SELECT *
FROM OrderDetails
ORDER BY OrderID,
Quantity
LIMIT 7

15-SELECT *
FROM OrderDetails
Where Quantity <8
ORDER BY OrderID,
ProductID
LIMIT 3

16-SELECT *
FROM OrderDetails
ORDER BY Quantity desc,
OrderID 
LIMIT 9

17-SELECT *
FROM OrderDetails
where OrderID=20
Order by OrderID
LIMIT 2

18-SELECT *
FROM OrderDetails
where Quantity>25
Order by ProductID
LIMIT 10

19-SELECT *
FROM OrderDetails
where OrderDetailID<50
Order by Quantity
LIMIT 4

20-SELECT *
FROM OrderDetails
where OrderID BETWEEN 10 AND 30
Order by ProductID
LIMIT 6

21-SELECT *
FROM OrderDetails
Order by Quantity desc,
OrderDetailID
LIMIT 8

22-SELECT *
FROM OrderDetails
WHERE ProductID LIKE '%7'
Order by OrderID
LIMIT 5

23-SELECT *
FROM OrderDetails
WHERE OrderID>100 
Order by Quantity,
OrderID
LIMIT 3

24-SELECT *
FROM OrderDetails
WHERE Quantity>15 
Order by OrderDetailID,
Quantity
LIMIT 10

25-SELECT *
FROM OrderDetails
Order by OrderID,
ProductID
LIMIT 12
