# concatination-and-Interpolation

```python
# Task 1: Version 1 specs - with concatenation
# Define a variable name, and assign a string
name = input("What is your name?")
print(name)
# Re-assign the original variable with your name
name = "Fatema  "
# use concatenation to print a welcome message
print("Hello "+name+" , Welcome onboard!")
#Use methods to format the name/input (remove white spaces)
name_without__whitespaces = name.strip()
print(len(name_without__whitespaces))

# Task 2: Interpolation
#Define another variable full_name to a random string
full_name = input("Please enter a random string")
#Re-assign the variable full_name to a name
full_name = input("Please enter your full name")
#use interpolation to print the message
print(f"Hello {full_name}, Welcome aboard!")

# Code Refactor
# creating an empty list
names = []

# number of names as input
num = int(input("Enter number of names to be entered : "))

# iterating till the range
for i in range(0, num):
    one_name = (input("Please enter your name").strip().capitalize())

    names.append(one_name)  # adding the name one at a time

print(f"Hello all in the list! {names}")
```
