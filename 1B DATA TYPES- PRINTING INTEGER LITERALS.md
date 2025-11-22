# Experiment No: 1BComplex Number Representation and Real-Part Extraction in Python

## AIM  
To write a Python program that demonstrates the relationship between Boolean values and integers by performing comparisons and arithmetic operations using True and False, and displaying the resulting outputs.

## ALGORITHM  
```
1.Start
2.Read the first input and store it in variable a (this represents the real part).
3.Read the second input and store it in variable b (this represents the imaginary part).
4.Create a complex number using the values a and b and store it in variable x.
5.Display the complex number x.
6.Extract the real part of the complex number using x.real.
7.Display the real part.
8.End
```
## PROGRAM
```python
a=int(input())
b=int(input())
 x=complex(a,b)
 print(x)
 print(x.real)
```
## OUTPUT
<img width="1173" height="282" alt="image" src="https://github.com/user-attachments/assets/338b792b-657e-4cec-bc6c-a66cbfe4e30c" />


## RESULT
The program successfully accepts two user inputs, forms a complex number, and displays it. It correctly extracts and prints the real part, demonstrating proper handling of complex data types in Python.
