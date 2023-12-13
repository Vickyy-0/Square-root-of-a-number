# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: vignesh.v
RegisterNumber: 23002301 
*/
n=int(input())
approx=0.5*n
for i in range(1,n+1):
    b=0.5*(approx+(n/approx))
    approx=b
print("Square root of the number:",b)
```

## Output:
<img width="597" alt="image" src="https://github.com/Vigneshv-23/Square-root-of-a-number/assets/110780412/967b9f8c-79c9-440b-a989-5dc2b501cd1b">


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
