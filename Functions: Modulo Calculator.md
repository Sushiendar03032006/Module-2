# Functions in Python: Modulo Calculator

## Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## Program
```
def result(a, b):
    mod = a % b
    print("The result of", a, "%", b, "is:", mod)

# Get two integer inputs from the user
a = int(input("Enter the first number: "))
b = int(input("Enter the second number: "))

# Call the function with user inputs
result(a, b)
```

## Output:
![image](https://github.com/user-attachments/assets/4f18dde1-2d46-42e1-a810-fd523078348f)




## Result:
Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator is successfully executed.
