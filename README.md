# Fun Calculator 🎉

Welcome to the Fun Calculator! This simple Python script performs basic arithmetic operations on two numbers with a touch of humor and emoji flair. 😄

## Features ✨
- Addition ➕
- Subtraction ➖
- Multiplication ✖️
- Division ➗
- Emoji-powered output 🎉
- Decimal number support

## Requirements 🛠️
- Python 3.x

## How to Run 🚀
1. Save the code as `fun_calculator.py`
2. Run in terminal:
```bash
python fun_calculator.py
```
3. Enter two numbers when prompted
4. See the magic results! ✨

## Example Usage 💻
```
Enter the first number: 8
Enter the second number: 2

Results of your two numbers:
Sum: 10.0
Difference: 6.0
Product: 16.0
Quotient: 4.0
```

## Important Notes ⚠️
1. Division by zero will crash the program (intentional design for now)
2. Only accepts numerical inputs
3. Handles decimal numbers gracefully

## Code Structure 🧠
```python
# Get two decimal numbers from user
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Perform calculations
sum_result = num1 + num2
difference_result = num1 - num2
product_result = num1 * num2
quotient_result = num1 / num2  # Watch out for division by zero!

# Display results with emojis
print(f"Results of your two numbers:")
print(f"Sum: {sum_result}")  # ➕
print(f"Difference: {difference_result}")  # ➖
print(f"Product: {product_result}")  # ✖️
print(f"Quotient: {quotient_result}")  # ➗
```

## Contribution Ideas 💡
- Add error handling for division by zero
- Include more operations (exponents, modulo)
- Create a GUI version
- Add history tracking

Made with ❤️ and Python! Happy calculating! 😎
