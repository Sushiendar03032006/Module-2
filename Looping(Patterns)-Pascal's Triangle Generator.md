# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program:
```
import math

# Start the program
# Input the number of rows from the user
rows = int(input("Enter the number of rows: "))

# Loop from 0 to the number of rows
for i in range(rows):
    # Print appropriate spaces to shape the triangle
    print(" " * (rows - i), end="")

    # Compute and print values using C(n, k) = n! / (k!(n-k)!)
    for j in range(i + 1):
        value = math.factorial(i) // (math.factorial(j) * math.factorial(i - j))
        print(value, end=" ")

    print()  # Move to the next line

# End of the program

```

## Sample Output:
![Screenshot 2025-04-30 230220](https://github.com/user-attachments/assets/96e3ac32-aef0-41e7-9109-74a8dc8e2328)



## Result:
The Python program that generates **Pascal's Triangle** using numbers is successfully executed.


