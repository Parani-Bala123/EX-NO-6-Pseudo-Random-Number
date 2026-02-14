# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
import random
def main():
    n = int(input("Enter how many random numbers to generate: "))
    print("Generated Random Numbers:")
    for _ in range(n):
        print(random.randint(0, 2**31 - 1), end=" ")  
if __name__ == "__main__":
    main()
```
# OUTPUT:
<img width="806" height="192" alt="image" src="https://github.com/user-attachments/assets/b70b224e-6c8e-49b3-abf3-ad98f6cd6cf6" />

# RESULT:
Thus, the code run successfully.
