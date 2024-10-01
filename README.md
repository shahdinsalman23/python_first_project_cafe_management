# Python Restaurant Ordering System

This is a simple Python program for a restaurant ordering system. The user can order items from a menu, and the program calculates the total cost of the selected items.

## Features
- Display the available menu items along with their prices.
- Allows the user to order one or two items from the menu.
- Calculates the total cost based on the ordered items.
- Informs the user if the item they ordered is unavailable.

## Menu
The available items in the menu are:
- **Pizza**: Rs. 2000
- **Pasta**: Rs. 500
- **Burger**: Rs. 60
- **Salad**: Rs. 70
- **Coffee**: Rs. 80

## How to Use
1. The program will display the menu and prompt the user to enter the name of the item they want to order.
2. If the item is available, it will be added to the order total.
3. The user will be asked if they want to order another item. If they respond with "Yes", they can add one more item.
4. The program will calculate and display the total cost of the ordered items.

## Sample Output

```python
Welcome to PYTHON Restaurant
Pizza: Rs2000
Pasta: Rs500
Burger: Rs60
Salad: Rs70
Coffee Rs80

Enter the name of item you want to order = Burger
Your item Burger has been added to your order
Do you want to add another item? (Yes/No) Yes
Enter the name to second item = Coffee
Item Coffee has been added to order
The total amount of items to pay is 140
