# Python-program-to-implement-a-calculator-for-basic-operations
def add(x, y):
    print("Result:", x + y)

def subtract(x, y):
    print("Result:", x - y)

def multiply(x, y):
    print("Result:", x * y)

def divide(x, y):
    if y != 0:
        print("Result:", x / y)
    else:
        print("Division by zero is not allowed")

print("Enter two numbers:")
n1 = int(input())
n2 = int(input())

print("Enter the operation (+, -, *, /):")
op = input()

if op == '+':
    add(n1, n2)
elif op == '-':
    subtract(n1, n2)
elif op == '*':
    multiply(n1, n2)
elif op == '/':
    divide(n1, n2)
else:
    print("Invalid entry")
