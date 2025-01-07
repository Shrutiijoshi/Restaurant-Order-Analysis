# Restaurant-Order-Analysis
Analyze order data to identify the most and least popular menu items and types of cuisine

# International Restaurant Orders Data Analysis 

## Project Overview :
A quarter's worth of orders from a fictitious restaurant serving international cuisine, including the date and time of each order, the items ordered, and additional details on the type, name and price of the items.The Restaurant Orders Dataset provides detailed insights into customer ordering behavior, sales trends, and restaurant performance. By analyzing this dataset, valuable information can be derived to support decision-making in restaurant management, marketing strategies, and menu optimization.

## Data Content :
### 1. Order_Details table :
- order_details_id : Unique ID of an item in an order
- order_id : ID of an order
- order_date : Date an order was put in (MM/DD/YY)
- order_time : Time an order was put in (HH:MM:SS AM/PM)
- item_id	: Matches the menu_item_id in the menu_items table

### 2. Menu_items table :
- menu_item_id	: Unique ID of a menu item
- item_name	: Name of a menu item
- category	: Category or type of cuisine of the menu item
- price	: Price of the menu item (US Dollars $)

## Project Objectives :
**Least and most ordered items** :
Identify the categories they belonged to and their impact on sales.

**Highest spend orders** :
Analyze the items purchased and the total amount spent.

**Specific times with more or fewer orders** :
Identify patterns in order frequency based on time.

**Which cuisines should be prioritized for developing more menu items based on customer preferences?**

## Tool & Library used :
[<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/mysql_logo.png" alt="myql-logo" width="150" height="100"/>](https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/mysql_logo.png) &nbsp;

## Project Result :
[Click here to get full code](https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/SQL_UNGUIDED_PROJECT.sql)

## Query task :
1. View the menu_items table
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/menu_items.PNG" alt="menu_items" width="600" height="200"/>

2. write a query to find the number of items on the menu
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/no_of_items.PNG" alt="no_of_items" width="400" height="250"/>

3. What are the least and most expensive items on the menu?
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/most_expensive_item.PNG" alt="most_expensive_item" width="300" height="200"/>
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/least_expensive_item.PNG" alt="least_expensive_item" width="300" height="200"/>

4. How many Italian dishes are on the menu?
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/no_of_italian_dishes.PNG" alt="no_of_italian_dishes" width="300" height="200"/>

5. What are the least and most expensive Italian dishes on the menu?
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/most_expensive_italian_dish.PNG" alt="most_expensive_italian_dish" width="300" height="200"/>
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/least_expensive_italian_dish.PNG" alt="least_expensive_italian_dish" width="300" height="200"/>

6. How many dishes are in each category?
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/no_of_dishes.PNG" alt="no_of_dishes" width="300" height="200"/>

7. What is the average dish price within each category?
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/avg_dish_price.PNG" alt="avg_dish_price" width="300" height="200"/>

8. View the order_details table
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/order_details.PNG" alt="order_details" width="300" height="200"/>

9. What is the date range of the table?
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/date_range.PNG" alt="date_range" width="300" height="200"/>

10. How many orders were made within this date range?
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/orders_made.PNG" alt="orders_made" width="300" height="200"/>

11.  How many items were ordered within this date range?
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/items_ordered.PNG" alt="items_ordered" width="300" height="200"/>

12. Which orders had the most number of items?
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/no_of_items_by_order_id.PNG" alt="no_of_items_by_order_id" width="300" height="200"/>

13. How many orders had more than 12 items?
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/more_than_12_items.PNG" alt="more_than_12_items" width="300" height="400"/>

14. Combine the menu_items and order_details tables into a single table
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/combined_data.PNG" alt="combined_data" width="700" height="400"/>

15. What were the least and most ordered items? What categories were they in?
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/most_combined.PNG" alt="most_combined" width="600" height="100"/>
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/least_combined.PNG" alt="least_combined" width="600" height="100"/>

16. What were the top 5 orders that spent the most money?
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/top_5.PNG" alt="top_5" width="300" height="300"/>

17. View the details of the highest spend order. Which specific items were purchased?
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/highest_spent.PNG" alt="highest_spent" width="500" height="400"/>

18. View the details of the top 5 highest spend orders
<img src="https://github.com/Shrutiijoshi/Restaurant-Order-Analysis/blob/main/CODE/top_5_highest_spent.PNG" alt="top_5_highest_spent" width="1000" height="600"/>
