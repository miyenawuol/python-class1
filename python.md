Here is a complete Python script that prompts for item price and quantity, converts the inputs, calculates the total, and displays a summary.

```python
# Program to calculate the total cost of items based on user input

# Prompt the user for input and convert the string values
price = float(input("Enter the price of one item: "))
quantity = int(input("Enter the quantity you want: "))

# Calculate total cost
total = price * quantity

# Display friendly summary formatted to two decimal places
print(f"\n{quantity} item(s) at {price:.2f} each = {total:.2f}")

```

### Example Interactive Run

```text
Enter the price of one item: 50
Enter the quantity you want: 3

3 item(s) at 50.00 each = 150.00

```