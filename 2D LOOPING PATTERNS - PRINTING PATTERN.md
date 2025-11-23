# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN
# AIM
To write a Python program to print a triangular star pattern using loops.

# ALGORITHM
Begin the program.
Read the integer n from the user using input(). This will determine the number of rows in the pattern.
Initialize a variable i = 0. This will help adjust the spacing before the stars.
Loop through rows from 0 to n - 1:
For each row, calculate the number of spaces to print using the formula: ((n - rows - 1) * 2) + i.
Print the calculated number of spaces using print(" ", end="").
Increment i by 1 after each row.
Print stars using a nested loop: the number of stars in each row is rows + 1, printed using print("*", end="  ").
Print a newline after each row using print("") to move to the next line.
Terminate the program.
# PROGRAM
```
for i in range(rows,0,-1): 
for j in range(0,i): 
print("*",end=" ") 
print()
```
# OUTPUT
<img width="466" height="619" alt="image" src="https://github.com/user-attachments/assets/e59994ba-5e8a-4ca3-97ef-c2f2d529c375" />


# RESULT
Thus the Python program to print a downward pyramid star pattern using loops was executed successfully and the output was verified.
