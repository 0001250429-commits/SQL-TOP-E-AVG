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

26
SELECT *
FROM OrderDetails
WHERE ProductID % 3 = 0
ORDER BY Quantity
LIMIT 7;

27
SELECT *
FROM OrderDetails
WHERE OrderDetailID BETWEEN 5 AND 50
ORDER BY OrderID
LIMIT 10;

28
SELECT *
FROM OrderDetails
ORDER BY Quantity DESC,
ProductID
LIMIT 6;

29
SELECT *
FROM OrderDetails
WHERE ProductID % 2 <> 0
ORDER BY Quantity
LIMIT 4;

30
SELECT *
FROM OrderDetails
WHERE OrderID > 15
ORDER BY ProductID
LIMIT 8;

31
SELECT *
FROM OrderDetails
WHERE Quantity < 5
ORDER BY OrderID
LIMIT 3;

32
SELECT *
FROM OrderDetails
WHERE ProductID % 2 = 0
ORDER BY OrderID
LIMIT 5;

33
SELECT *
FROM OrderDetails
ORDER BY OrderDetailID DESC
LIMIT 10;

34
SELECT *
FROM OrderDetails
WHERE Quantity % 5 = 0
ORDER BY ProductID
LIMIT 7;

35
SELECT *
FROM OrderDetails
ORDER BY ProductID,
OrderID
LIMIT 2;

36
SELECT *
FROM OrderDetails
WHERE OrderID LIKE '%1'
ORDER BY Quantity
LIMIT 8;

37
SELECT *
FROM OrderDetails
ORDER BY OrderID DESC,
OrderDetailID
LIMIT 4;

38
SELECT *
FROM OrderDetails
WHERE Quantity > 30
ORDER BY ProductID
LIMIT 9;

39
SELECT *
FROM OrderDetails
ORDER BY ProductID,
OrderID
LIMIT 5;

40
SELECT *
FROM OrderDetails
ORDER BY OrderDetailID DESC,
Quantity
LIMIT 6;

41
SELECT *
FROM OrderDetails
WHERE OrderID % 2 <> 0
ORDER BY Quantity
LIMIT 10;

42
SELECT *
FROM OrderDetails
WHERE Quantity = 20
ORDER BY ProductID
LIMIT 3;

43
SELECT *
FROM OrderDetails
WHERE OrderDetailID < 200
ORDER BY OrderID
LIMIT 7;

44
SELECT *
FROM OrderDetails
WHERE OrderID BETWEEN 100 AND 200
ORDER BY ProductID
LIMIT 5;

45
SELECT *
FROM OrderDetails
ORDER BY Quantity DESC,
OrderDetailID
LIMIT 12;

46
SELECT *
FROM OrderDetails
WHERE ProductID < 10
ORDER BY OrderID
LIMIT 9;

47
SELECT *
FROM OrderDetails
WHERE OrderID LIKE '%0'
ORDER BY Quantity
LIMIT 2;

48
SELECT *
FROM OrderDetails
ORDER BY OrderID,
ProductID
LIMIT 5;

49
SELECT *
FROM OrderDetails
WHERE Quantity % 4 = 0
ORDER BY ProductID
LIMIT 6;

50
SELECT *
FROM OrderDetails
ORDER BY ProductID DESC,
Quantity
LIMIT 10;


1
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
ORDER BY Quantity;

2
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderID > 10
ORDER BY Quantity;

3
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE ProductID = 5
ORDER BY Quantity;

4
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderDetailID < 50
ORDER BY Quantity;

5
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderID > 100
ORDER BY Quantity;

6
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE ProductID % 2 = 0
ORDER BY Quantity;

7
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderDetailID % 2 <> 0
ORDER BY Quantity;

8
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE ProductID BETWEEN 5 AND 15
ORDER BY Quantity;

9
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderID % 10 = 0
ORDER BY Quantity;

10
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderDetailID BETWEEN 10 AND 30
ORDER BY Quantity;

11
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE Quantity > 25
ORDER BY MediaQuantidade;

12
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE Quantity < 10
ORDER BY MediaQuantidade;

13
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE ProductID > 7
ORDER BY MediaQuantidade;

14
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderID < 20
ORDER BY MediaQuantidade;

15
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE Quantity % 5 = 0
ORDER BY MediaQuantidade;

16
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE ProductID < 12
ORDER BY MediaQuantidade;

17
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderID BETWEEN 15 AND 30
ORDER BY MediaQuantidade;

18
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE CAST(OrderDetailID AS CHAR) LIKE '2%'
ORDER BY MediaQuantidade;

19
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE ProductID > 10
ORDER BY MediaQuantidade;

20
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderID % 2 <> 0
ORDER BY MediaQuantidade;

21
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE ProductID % 3 = 0
ORDER BY MediaQuantidade;

22
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderDetailID > 30
ORDER BY MediaQuantidade;

23
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE Quantity BETWEEN 10 AND 20
ORDER BY MediaQuantidade;

24
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderID % 10 = 5
ORDER BY MediaQuantidade;

25
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE ProductID IN (3,5,7)
ORDER BY MediaQuantidade;

26
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE Quantity NOT BETWEEN 15 AND 25
ORDER BY MediaQuantidade;

27
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE ProductID BETWEEN 5 AND 15
ORDER BY MediaQuantidade;

28
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderID = 100
ORDER BY MediaQuantidade;

29
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderDetailID BETWEEN 100 AND 200
ORDER BY MediaQuantidade;

30
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE Quantity > 20
ORDER BY MediaQuantidade;

31
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE ProductID NOT IN (1,2,3)
ORDER BY MediaQuantidade;

32
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderDetailID % 10 = 2
ORDER BY MediaQuantidade;

33
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE Quantity % 2 = 0
ORDER BY MediaQuantidade;

34
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderID > 200
ORDER BY MediaQuantidade;

35
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE ProductID = 10
ORDER BY MediaQuantidade;

36
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderDetailID BETWEEN 50 AND 100
ORDER BY MediaQuantidade;

37
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE CAST(OrderID AS CHAR) LIKE '1%'
ORDER BY MediaQuantidade;

38
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE ProductID % 5 = 0
ORDER BY MediaQuantidade;

39
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE Quantity NOT IN (5,10,15)
ORDER BY MediaQuantidade;

40
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderDetailID < 10
ORDER BY MediaQuantidade;

41
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE ProductID > 20
ORDER BY MediaQuantidade;

42
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE Quantity = 15
ORDER BY MediaQuantidade;

43
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderDetailID IN (10,20,30)
ORDER BY MediaQuantidade;

44
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE Quantity BETWEEN 5 AND 10
ORDER BY MediaQuantidade;

45
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderID % 10 <> 3
ORDER BY MediaQuantidade;

46
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE ProductID > 30
ORDER BY MediaQuantidade;

-- 47
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderID < 100
ORDER BY MediaQuantidade;

48
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE ProductID BETWEEN 10 AND 50
ORDER BY MediaQuantidade;

49
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE Quantity % 4 = 0
ORDER BY MediaQuantidade;

50
SELECT AVG(Quantity) AS MediaQuantidade
FROM OrderDetails
WHERE OrderDetailID % 10 = 0
ORDER BY MediaQuantidade;
