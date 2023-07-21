**Overview**
=====================
PetMind is a retailer of products for pets. They are based in the United States. PetMind sells products that are a mix of luxury items and everyday items. Luxury items include toys. Everyday items include food. The company wants to increase sales by selling more everyday products repeatedly. They have been testing this approach for the last year. They now want a report on how repeat purchases impact sales.

**Tasks**

1. For every column in the data:
<li>
State whether the values match the description given in the table above
<li>
State the number of missing values in the column
<li>
Describe what you did to make values match the description if they did not match

  
2. Create a visualization that shows how many products are repeat purchases. Use the visualization to:
  
<li>
State which category of the variable repeat purchases has the most observations
<li>
Explain whether the observations are balanced across categories of the variable repeat purchases

  
3. Describe the distribution of all of the sales. Your answer must include a visualization that shows the distribution

4. Describe the relationship between repeat purchases and sales. Your answer must include a visualization to demonstrate the relationship

**Data description**
<li>
product_id. Nominal. The unique identifier of the product.
Missing values are not possible due to the database structure.
<li>
category. Nominal. The category of the product, one of 6 values (Housing,
Food, Toys, Equipment, Medicine, Accessory). Missing values should be replaced with “Unknown”.
<li>
animal. Nominal. The type of animal the product is for. One of Dog, Cat,
Fish, Bird. Missing values should be replaced with “Unknown”.
<li>
size. Ordinal. The size of animal the product is for. Small, Medium,
Large. Missing values should be replaced with “Unknown”.
<li>
price. Continuous. The price the product is sold at. Can be any positive
value, round to 2 decimal places. Missing values should be replaced with the overall median price.
<li>
sales. Continuous. The value of all sales of the product in the last year.
This can be any positive value, rounded to 2 decimal places Missing values should be replaced with the overall median sales.
<li>
rating. Discrete. Customer rating of the product from 1 to 10.
Missing values should be replaced with 0.
<li>
repeat_purchase. Nominal. Whether customers repeatedly buy the product (1) or not (0). Missing values should be removed.
  
**Libs**

`pandas`  `numpy`  `plotly` 
