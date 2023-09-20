![image](https://github.com/Balaji-Jothiramalingam/GCD-of-two-numbers/assets/114234865/8cd8c57d-32df-47d9-8d1a-737b7123a763)![image](https://github.com/Balaji-Jothiramalingam/GCD-of-two-numbers/assets/114234865/29ccb0f2-9d8d-43d1-b989-3f3a6ba27021)# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: Balaji J
RegisterNumber:  212221243001
*/

def gcd():
    n1,n2=int(input()),int(input())
    if n1>n2:
        smaller=n2
    else:
        smaller=n2
    for i in range(1,smaller+1):
        if (n1%i==0 and n2%i==0):
            hcf=i
    print("GCD of two numbers is:",hcf)

```
## Output:
![image](https://github.com/Balaji-Jothiramalingam/GCD-of-two-numbers/assets/114234865/65028055-0941-41b4-8ddb-4d108175ee61)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
