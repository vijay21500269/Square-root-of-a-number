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
Developed by: R.Vijay
RegisterNumber:  21500269
*/
```
~~~
def newlin_method(number,number_iter=100):
    b=float(number)
    for i in range(number_iter):
        number=0.5*(number+(b/number))
    return number
number=int(input())
print('Square root of the number:',newlin_method(number))
~~~
## Output:
![gcd of two number](https://github.com/vijay21500269/Square-root-of-a-number/blob/main/Screenshot%20(3).png?raw=true)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
