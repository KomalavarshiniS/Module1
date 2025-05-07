# EX-01-Conditional Statements in Python: Even or Odd Checker

## Aim:
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## Algorithm:
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## Program:
```
a=int(input())
if a%2==0:
    print(f"{a} is an Even number")
    if a>=25:
        print(f"{a} is greater than or equal to 25")
    else:
        print(f"{a} is lesser than 25")
else:
    print(f"{a} is NOT an Even number")
```
## Output:
![image](https://github.com/user-attachments/assets/c66bfbc3-9889-48eb-a196-b194b940380b)

## Result:
Thus the program to check whether the given number is **even** or **odd** using `if...else` statements has been executed successfully
