# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
```
a = int(input("Enter real part: "))
b = int(input("Enter imaginary part: "))
x = complex(a, b)

print("Complex number is:", x)
print("Real part is:", x.real)
print("Imaginary part is:", x.imag)
```
## Output
<img width="516" height="283" alt="image" src="https://github.com/user-attachments/assets/0efac7eb-1096-4bce-80e7-5616d1a5b627" />


## Result
The program successfully creates a complex number using user inputs and displays its real and imaginary parts using .real and .imag attributes.
