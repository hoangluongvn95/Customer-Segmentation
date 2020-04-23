# Customer-Segmentation

## Part 1: Data Exploration
- Products ordered: The count of the products ordered in product_type column by a customer.
- Average Return Rate: The ratio of returned item quantity and ordered item quantity.
- Total spending: The sum of total sales value which is the amount after the taxes and returns.

![](/Report/1.png)

## Part 2:  Features Engineering
Apply numpy.log1p transformation to the column as a result returns log1p applied pandas series

## Part 3:  Segmentation using K-means Clustering
Create initial K-means model

## Part 4: Hyperparameter Tuning (Elbow Method)
Make a list of inertia values against 1 to K (inclusive) return the inertia values list and update the optimal number of clusters.

![](/Report/4.png)

## Part 5: Visualization and Interpretation 
Green: Customers who ordered 1 to 13 products, with average total spending of 600 and average return rate as 0. It makes the most valuable customer group for the company.

![](/Report/5.png)
