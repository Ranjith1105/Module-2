# Exp.No:2d
## LOOPING PATTERNS - PRINTING PASCAL'S TRIANGLE

---

### AIM  
To create a Python program to print Pascal’s Triangle by getting the number of rows as input from the user.

---

### ALGORITHM

1.Begin the program.
2.Use input() to read the number of rows from the user.
3.Convert the input to an integer.
4.Define a function to calculate the factorial of a number (or use math.factorial).
5.Use nested for loops:
    -Outer loop for each row i from 0 to n-1.
    -Inner loop to print spaces for alignment.
    -Another loop to print the values using the formula: C(i, j) = i! / (j! * (i-j)!).
6.Print each row of the triangle.
7.Terminate the program.

---

### PROGRAM
```
#Reg.No: 212223020021
#Name: Ranjith P
#Add Your Code Here

rows = int(input())
coef = 1

for i in range(1, rows+1):
    for space in range(1, rows-i+1):
        print(" ",end="")
    for j in range(0, i):
        if j==0 or i==0:
            coef = 1
        else:
            coef = coef * (i - j)//j
        print(coef, end = " ")
    print()

```

### OUTPUT
![Screenshot 2025-04-28 155332](https://github.com/user-attachments/assets/26dcb36c-746f-4b39-bb80-1d1988f86600)

### RESULT
Thus, the Python program to print Pascal’s Triangle based on user input for the number of rows was executed successfully.
