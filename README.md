# Coding
A simple Python project covering core concepts like loops, functions, and logic building.
# Function to check even or odd
def check_even_odd(num):
    if num % 2 == 0:
        return "Even"
    else:
        return "Odd"

# Function to find factorial using loop
def factorial(n):
    fact = 1
    for i in range(1, n + 1):
        fact *= i
    return fact

# Main logic
print("Numbers from 1 to 5 and their properties:\n")

for i in range(1, 6):   # Loop
    result = check_even_odd(i)   # Function call
    fact = factorial(i)          # Function call
    
    print("Number:", i)
    print("Type:", result)
    print("Factorial:", fact)
    print("-------------------")
