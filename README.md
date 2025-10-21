# PYTHON PROGRAMMMING MODULE 1
### DATE: 21.10.25
# Ex 01-A: Conditional Statements in Python: Even or Odd Checker

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
```
num = int(input())
if num%2==0:
    print("EVEN")
else:
    print("ODD")
```

## Output


<img width="390" height="315" alt="1" src="https://github.com/user-attachments/assets/b56cc56b-b48e-4eeb-8c24-245955c88c67" />

## Result
Thus the Python Program for determining whether the given number is odd or even has been executed successfully and the output has been verified.

# Ex 01-B:Datatypes-Boolean Expression Evaluation in Python

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
a = (0 == True)
b = (False == False)
c = True + True
d = False + 9

print("a is", a)
print("b is", b)
print("c:", c)
print("d:", d)

```

## Output

<img width="392" height="356" alt="2" src="https://github.com/user-attachments/assets/90ff30f1-02ce-4a64-85f6-b7e2d9827934" />

## Result
Thus the given Python program has been executed successfully and the output has been verified.

# EX 01-C:  Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
```
#Printing character literals
print('T')
print('a')
```
## Output

<img width="367" height="311" alt="3" src="https://github.com/user-attachments/assets/65623ae5-4db5-41d4-a21a-a13ce706c355" />

## Result
Thus the given Python Program has been exceuted successfully and the output has been verified.

# EX 01-D:Datatypes-Complex Number Creation in Python

##  Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

##  Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

##  Program
```
a = int(input())
b = int(input())

x = complex(a, b)
print(x)
print(x.real)
print(x.imag)
```
## Output

<img width="434" height="332" alt="4" src="https://github.com/user-attachments/assets/bfd89ad0-de2f-402e-88cf-7fb90df62c9f" />


## Result
Therefore the given Python Program has been executed succeefully and the output has been verified.

# EX 01-E:Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```
string = input()
print(string)

```
## Output

<img width="840" height="234" alt="5" src="https://github.com/user-attachments/assets/a32ca587-0431-4f35-bee5-53df4691c5f9" />


## Result
Therfore the given Python program has been executed successfully and the output has been verified.
