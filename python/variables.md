**Variables** are used to store information to be later used within a program. Most programming languages contain some sort of way to store data within variables, and python is no different. It's helpful to think of variables as boxes which can hold something within them, whether it be a number, string or an object!

In python, variables can be declared by using the following syntax:
```py
myVariable = 4 # A variable named "myVariable", containing an integer value of 4
anotherVariable = "Hello World!" # Another variable, aptly named "anotherVariable", containing the words "Hello World!"
```
---
**Use Cases**

Variables can be used in a number of circumstances, but are most appropriately used alongside **functions**. For instance, `input()`, where you would need to use the returned value from that function to dictate the control flow of your code later on.

For example,
```py
myVariable = 4

if myVariable > 2:
      print("Wow, that variable is greater than 2!")
```
