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

# 1. Define a function
def sqrt_iter(a):
    
    # 2. Number of iterations
    number_iters = 100

    # Initial guess
    number = a

    # 3. Set i = 0
    i = 0

    # 4. Iterate 100 times
    for i in range(number_iters):
        number = 0.5 * (number + a / number)

    # 5. Return number
    return number


# Input from user
a = float(input("Enter a number: "))

result = sqrt_iter(a)

print("Square root of", a, "is:", result)
<img width="1672" height="753" alt="image" src="https://github.com/user-attachments/assets/7991b9be-71d5-4c0c-bdce-d769fc445a84" />


## Output


<img width="1672" height="753" alt="image" src="https://github.com/user-attachments/assets/7991b9be-71d5-4c0c-bdce-d769fc445a84" />

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
