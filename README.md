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

# favoriteColors
this a conditional check.
we have a list of colors ["Red","Blue","Yellow","Green","Purple","Orange"] using Choose(Randbetween(1,6),"Red","Blue","Yellow","Green","Purple","Orange") function to choose colors reandomly, then we check numbers of colors by using COUNTIF for all colors, like num of red is assigned a conditional =COUNTIF(Colors,"Red") which will return number of red color in the list then check if they are above five by using =IF(C2>5,TRUE,FALSE) which will return boolian True if number above 5 and False if number is not above 5.