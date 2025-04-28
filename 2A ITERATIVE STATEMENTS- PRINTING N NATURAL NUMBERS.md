# Exp. No: 2a  
## PRIMALITY TEST – CHECKING IF A NUMBER IS PRIME

###  Aim
To create a Python program that tests whether a given number is prime or not.

###  Algorithm

1.Begin the program.
2.Use input() to read a number from the user.
3.Convert the input to an integer.
4.If the number is less than or equal to 1, it's not prime.
5.Use a for loop from 2 to the square root of the number (inclusive):
 If the number is divisible by any of these, it's not prime.
 If no divisors are found, the number is prime.
6.Display the result accordingly.
7.Terminate the program.

---

### 🧾 Program

```python
#Reg.NO - 212223020021
#Name - Ranjith P
#Write your Code here

n=int(input())
for i in range (2,n):
    if n%i==0:
        print("Given number {} is not a Prime Number".format(n))
        break
    else:
        print("Given number {} is a Prime Number".format(n))
        break
    

```
### OUTPUT
```
![Screenshot 2025-04-28 153614](https://github.com/user-attachments/assets/1486a7e3-e562-48f5-bdef-0787308a61c8)

```
### RESULT
```
Thus, the Python program to test whether a number is prime or not was executed successfully.

```

