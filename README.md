## PYTHON PROGRAMMING MODULE 1

## NAME: Antony Aswin Kumar L
## REGISTER NUMBER: 212225040024

## Ex:1  Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program:

```
n=int(input("Enter the number :"))
if n%2==0:
    print("The given number is a EVEN number.")
else:
    print("The given number is a ODD number.")
```

## Output:

<img width="651" height="185" alt="Screenshot 2026-05-26 110859" src="https://github.com/user-attachments/assets/886b0d99-f384-4d1c-a675-7de17db4ba95" />

## Result:
Thus, the Python program to check whether the given number is **even** or **odd** using if...else statements is executed successfully.


## Ex:2 Datatypes-Boolean Expression Evaluation in Python

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

```
a = 0==True
b = False==False 
c = True+True
d = False+9
print("a is",a)
print("b is",b)
print("c:",c)
print("d:",d)
```

## Output

<img width="589" height="303" alt="image" src="https://github.com/user-attachments/assets/06a97663-ad6c-4085-b8ba-4ac36eb91f66" />

## Result
Thus,the Python program that evaluates and prints the results of boolean and arithmetic expressions involving True and False is executed successfully.



## Ex:3  Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program:

```
ch1='T'
ch2='a'
print(ch1)
print(ch2)
```

## Output:

<img width="390" height="175" alt="image" src="https://github.com/user-attachments/assets/b9c4597a-3d9f-4f9c-8c75-c7be3a6fdb77" />


## Result:

Thus,the Python program that prints the characters 'T' and 'a' using character literals.


## Ex:4  Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program:

```
real=int(input("Enter the real part: "))
imaginary=int(input("Enter the imaginary part: "))

z=complex(real,imaginary)
print("Complex Number : ",z)
print("Real part : ",z.real)
print("Imaginary part : ",z.imag)
```

## Output:

<img width="583" height="314" alt="Screenshot 2026-05-26 180259" src="https://github.com/user-attachments/assets/29185caf-2ed0-4602-a87a-0a959f67398c" />


## Result:

Thus the Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts is executed successfully.



## Ex:5  Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program:

```
men_stepped_on_the_moon = input("Enter the string : ")

print(men_stepped_on_the_moon)
```

## Output:

<img width="650" height="146" alt="Screenshot 2026-05-26 180317" src="https://github.com/user-attachments/assets/5ee817c5-98e8-45ed-befe-2bda70b91846" />

## Result

Thus the Python program to read a string from the user and then print it is executed successfully.
