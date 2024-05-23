# python-challenge-1
Module 2 Challenge

By: Esteban Missura
Date: 5/23/2024

Brief Description: 
    * This is an interactive ordering system from a food truck menu. A user is prompted to order from the menu, and the program prints out the order summary and total cost.

Detailed Description:
1. Starter code used included: 
    * Menu dictionary.
    * Welcome message.
    * while loop (main ordering loop allowing customers to place multiple orders), iterating, and printing options and error messages.
    * Message saying "This is what we are preparing for you", followed by the order list structure form.
2. Code filled out by me using skills learned and in class activities:
    * Question 1: Creating an empty list called order_list.
    * Question 2: Asking user for menu item number.
    * Question 3: Checking if the customer slected a valid option (number), if not error message.
    * Question 4: Checking if input is an option in the menu, if not error message, asking for quantity, and appending it all to the order list.
    * Question 5: Match case to see if customer wants to keep ordering.
    * Question 6-10: for loop through items in the order, calculating number of spaces for formatting, and printing the order list for the customer.
    * Question 11: Used list comprehension to multiply the price and quantity of each of the customer's order items, summed it all up and printed the total price.

Detailed Chat GPT Generated Explanation/Steps:
1. Menu Dictionary:
    * Defines the menu with categories such as Snacks, Meals, Drinks, and Dessert. Each category contains items with their respective prices.
2. Initialize Order List:
    * Creates an empty list order_list to store the ordered items.
3. Greet the Customer:
    * Prints a welcome message to the customer.
4. Main Ordering Loop:
    * The loop allows customers to place multiple orders until they choose to stop.
5. Display Menu Categories:
    * Iterates through the menu dictionary and prints the available categories.
6. Get Customer's Menu Category Choice:
    * Prompts the customer to choose a menu category by typing the corresponding number.
7. Validate Menu Category Input:
    * Checks if the input is a valid number and corresponds to an existing menu category.
8. Display Items in Chosen Category:
    * Prints the items available in the selected category, along with their prices.
9. Get Customer's Menu Item Choice:
    * Prompts the customer to choose an item from the selected category by typing the corresponding number.
10. Validate Menu Item Selection:
    * Checks if the input is a valid number and corresponds to an existing menu item.
11. Get Quantity of Selected Item:
    * Prompts the customer to enter the quantity they want to order for the selected item.
12. Validate Quantity Input:
    * Ensures the quantity input is a valid number, defaulting to 1 if it is not.
13. Add Item to Order List:
    * Appends the selected item, its price, and the quantity to the order_list.
14. Ask if Customer Wants to Keep Ordering:
    * Prompts the customer to decide if they want to continue ordering or complete their order.
15. Display Customer's Order:
    * Prints a summary of all items in the order_list.
16. Calculate and Print Total Cost:
    * Computes the total cost of the order by summing the product of price and quantity for each item and prints the total.