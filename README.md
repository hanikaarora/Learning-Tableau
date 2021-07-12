Tableau
Ecommer retail data set:-

It contain 8 Variables,

1. InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.

2. StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.

3. Description: Product (item) name. Nominal.

4. Quantity: The quantities of each product (item) per transaction. Numeric.

5. InvoiceDate: Invoice Date and time. Numeric, the day and time when each transaction was generated.

6. UnitPrice: Unit price. Numeric, Product price per unit in sterling.

7. CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.

8. Country: Country name. Nominal, the name of the country where each customer resides.


Observations:-
Invoice: 
Cancel order moved to another sheet and created cancel dataset

Stock Code:
Stock code values like discount, carriage, manual 527 records 

Description
Blank Values is renamed as No description
Divide rows as product and transaction based on description
1040 records are transaction not having sales
Packing charge, next day carriage kept as it it

QTY:	
Qty with negative values is 10624 including cancel orders
After removing cancel orders, we get 1336 records

Invoice Data:
Having Null Value Kept as it is

Unit price:
After removing negative/loss values count is 1174 records
Unit price with negative value 

Sales: 
Created sales column by multiplying QTY * unit price

CustomerID: 
Blank Values will be replacing with 0 or left is as Null

Country:
Unspecified values are left as it is
