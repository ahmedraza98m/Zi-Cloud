# calculator.py

def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y == 0:
        return "Cannot divide by zero!"
    return x / y

# Sample usage
if __name__ == "__main__":
    print("Add: ", add(5, 3))
    print("Subtract: ", subtract(5, 3))
    print("Multiply: ", multiply(5, 3))
    print("Divide: ", divide(5, 0))
