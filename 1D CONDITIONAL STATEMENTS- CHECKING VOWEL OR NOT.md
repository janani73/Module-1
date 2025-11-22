## Experiment No: 1d –Dog Age to Human Age Conversion Program in Python

## AIM  
To write a Python program that takes a dog’s age as input and converts it into equivalent human years using predefined conversion rules, then displays the correct human-age value.
## ALGORITHM  
```
1.Start the program.
2.Read the dog's age from the user and store it in age.
3.If age is 0, print that it corresponds to 0 human years.
4.If age is 1, print that it equals roughly 14 human years.
4.If age is 2, print that it equals approximately 22 human years.
5.Otherwise, calculate human years using the formula: 22 + (age - 2) * 5.
6.Print the calculated human-age value.
7.End the program.
```
## PROGRAM
```python
age=int(input())
human = 22 + (age -2) * 5
if age == 0:
    print("This corresponds to 0 human years!")
elif age==1:
    print("Roughly 14 years!")
elif age==2:
    print("Approximately 22 years!")
else:
    print("Corresponds to  " + str(human) + " human years!")
```

## OUTPUT
<img width="1183" height="315" alt="image" src="https://github.com/user-attachments/assets/94522835-06b1-4cca-89c4-a9ff7991e21c" />


## RESULT
The program successfully takes a dog’s age, applies the correct conversion rules, computes the equivalent human age, and displays accurate results for all age inputs.
