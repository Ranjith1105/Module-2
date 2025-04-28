# Exp.No:2e  
## SEB - SUM OF FACTORIAL SERIES

---

### AIM  
To create a Python program to find the sum of the series: 1! + 2! + 3! + ... + n!

---

### ALGORITHM

1.Begin the program.
2.Use input() to read the value of n from the user.
3.Convert the input to an integer.
4.Initialize a variable sum to 0.
5.Use a loop from 1 to n (inclusive):
    -For each number i, calculate its factorial using another loop or the math.factorial() function.
    -Add the factorial value to sum.
6.After the loop ends, display the final value of sum.
7.Terminate the program.

---

### PROGRAM
Reg no: 212223020021
Name: Ranjith P

```
a=int(input())
p=1
s=0
for i in range(1,a+1):
    p*=i
    s+=p
print(f'The sum of the series =  {s}')
```
### OUTPUT
![Screenshot 2025-04-28 155738](https://github.com/user-attachments/assets/1ebf4497-7384-46a5-8253-aebce7ca04c5)


### RESULT
Thus, the Python program to compute the sum of the series 1! + 2! + 3! + ... + n! was executed successfully.


