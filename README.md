# Find the GCD of two numbers

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
Program to find the gcd of two number using function.
Developed by: Masina Sree karsh
RegisterNumber:  23005860

def gcd():
    n1,n2=int(input()),int(input())
    if n1<n2:
        smaller=n1
    else:
        smaller=n2
    for i in range(1,smaller+1):
        if n1%i==0 and n2%i==0:
            gcd=i
    print("GCD of two numbers is:",gcd)        



```

## Output:
![image](https://github.com/sreekarsh/GCD-of-two-numbers/assets/139841918/92cad720-8647-42d8-ac1b-2d2b3df665ed)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
