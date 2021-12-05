**Functions** are a common way that programmers minimize the code they write. You can define functions by using the keyword `def`, and can use them anywhere proceeding their definition in your program, this doesn't apply for **methods** defined within **classes**. The code within a function is commonly refered to as a "block" and is indented.

The syntax is as follows:
```py
def printPoggers():
    print("Poggers!")
```

Where "printPoggers", is the function name, and the code block beneath it is what is ran when the function is "called"

Calling the function can be done with the syntax: `printPoggers()` anywhere after the definition of the function in your program. (Obviously take into account that "printPoggers" is the name of the function).

---
**Functions with Arguments**
The utility of functions doesn't stop at being able to run code while writing less, you can also pass **arguments** to functions, which allow you to utilize values within those functions and potentially produce an output that you may find useful later on in your program.

For instance, take this simple adding function:
```py
def addTwoNumbers(a, b):
    return a + b
```

Arguments `a` and `b` will be added together, however this function does have some flaws, so you may want to look into *type-hinting*. Which helps you isolate what types you want your variables to be, it's not required but it's good practice.

For example, this is a type-hinted function:
```py
def addTwoNumbers(a : int, b : int) -> int:
    return a + b
```
*Where both a & b are identified that they will be integers, and the function itself is told that it should only return integers, this is also good practice for documentation.*
