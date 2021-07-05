# Import Optimizer

With the recent surge of freight prices, many traders are looking to optimize the shipping costs of their merchandise.

This code optimize the income of an import project by taking into account the budget of the import project, the size of the container in cubic meter, the size of the products as well as the gain per product and gives the number of each goods that maximizes the profit.

The problem can be written:


## Mathematically

This optimization problem can be written:

max g1*g1_profit + g2*g2_profit  
s.t. (g1*g1_price + g2*g2_price) <= budget  
     (g1*g1_size + g2*g2_size) <= total_size  

With:
g1, g2 the number of good 1 and 2  
g1_size, g2_size the size of goods 1 and 2  
g1_price, g2_price the price of goods 1 and 2  
g1_profit, g2_profit the profit made by the sale of goods 1 and 2  


## How
SciPy optimize provides functions for minimizing or maximizing objective functions.


## How to use
Simply by changing the values of the inputs.
