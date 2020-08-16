# shoping_trip

in this excel script we are trying to do some simple calculations.
we are given a list of products and their price, then we want to ad taxes, calculate price with taxes and find the total amount paid.
1\ to calculate tax for evry item, we first create a new column "Tax Rate" at G1, and assign a rate to it, in this case our tax rate is 10%. next we create a new column called "Tax" at C1, the equation we use to calculate the tax is:
=B2*TaxRate
B2 is our item price multiplied by our tax rate.
2\ to calculate item price with taxes we create a column "price with taxes" and  simply add column B2 the price to column C2 tax with this equation:
=B2+C2
3\ finaly we want the total amount paid, we create a column "Paid Total" and sum up our Price with Taxes column with this equation:
=SUM(TaxPrice)