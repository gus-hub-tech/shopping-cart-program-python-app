# shopping cart program - python

## Description

This is a simple Python command-line program that simulates a shopping cart. The user can add food products and their prices to the cart, and when finished, the program displays all items with their prices and the total cost.

## How It Works

1. **Start the Program:**  
   The program welcomes the user and starts an input loop.

2. **Add Items:**  
   The user is prompted to enter the name of a food product.  
   - If the user types `exit`, the program stops asking for more items.
   - Otherwise, the user is prompted to enter the price of the product.

3. **Store Data:**  
   - Each food item is added to a list of foods.
   - Each price is added to a list of prices.
   - The total cost is updated with each new item.

4. **Display Cart:**  
   After the user exits, the program prints a summary of all food items and their prices, followed by the total cost.

5. **End Message:**  
   The program thanks the user for using the shopping cart.

## Example Usage

```
Welcome to the Shopping Cart Program!
Enter a food product (or type 'exit' to finish): Bread
Enter the price of Bread: R12.50
Enter a food product (or type 'exit' to finish): Milk
Enter the price of Milk: R18.00
Enter a food product (or type 'exit' to finish): exit
-----Your CART-----
Bread - R12.50
Milk - R18.00

Total cost: R30.50
-----End of CART-----
Thank you for using the Shopping Cart Program!
```

## Requirements

- Python 3.x

## How to Run

1. Save the script as `shopping_cart.py`.
2. Open a terminal and navigate to the script's directory.
3. Run the script with:
   ```
   python shopping_cart.py
   ```

## Features

- Add as many items as you want.
- See a summary of your cart and total cost.
- Simple and easy to use.

---
