# Module 1 - Python Programming Exercises

This document combines all Module 1 exercise files into one Markdown file.

---

# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```python
a=int(input())
if(a%2==0):
    print("EVEN")
else:
    print("ODD")
```

## Output
<img width="467" height="373" alt="Even or odd output" src="https://github.com/user-attachments/assets/aa7f56e3-8ddb-49e6-bda8-b650e926af07" />

## Result
Thus, the Python program to check whether the given number is even or odd using if...else statements is created successfully.

---

# Ex 1: Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
```python
a=(0==True)
b=(False==False)
c=True+True
d=False+9
print(f"a is {a}")
print(f"b is {b}")
print(f"c: {c}")
print(f"d: {d}")
```

## Output
<img width="1112" height="283" alt="Boolean expression output" src="https://github.com/user-attachments/assets/f79d7b46-f3ff-49b0-85b7-e2751bc5a2a9" />

## Result
Thus, to write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving True and False is compiled and the output is verified successfully.

---

# Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
```python
char1='T'
char2='a'
print(char1)
print(char2)
```

## Output
<img width="951" height="250" alt="Character literal output" src="https://github.com/user-attachments/assets/c572263d-1822-460d-a5eb-fea06d3d09dd" />

## Result
Therefore to write a Python program that prints the characters 'T' and 'a' using character literals is compiled and the output is verified successfully.

---

# Datatypes-Complex Number Creation in Python

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
```python
a=int(input())

b=int(input())

x=complex(a,b)

print(x)

print(x.real)

print(x.imag)
```

## Output
<img width="887" height="224" alt="Complex number output" src="https://github.com/user-attachments/assets/e9758e13-665f-46a1-a2b1-9e439eb20f06" />

## Result
Thus the program has been successfully executed.

---

# Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```python
men_stepped_on_the_moon=input()

print(men_stepped_on_the_moon)
```

## Output
<img width="850" height="261" alt="String output" src="https://github.com/user-attachments/assets/8b69fa18-82cd-499c-b46e-03cebd562aed" />

## Result
Thus, the program has been successfully execute.
