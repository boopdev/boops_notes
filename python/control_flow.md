**What is "Control Flow"?**

Control flow can be defined as the order in which individual statements, instructions, or function calls of a program are executed or evaluated. This is most commonly dictated using `if/elif/else` statements. These **conditional statements** are commonly used to check if a condition is satisfied or not, and then proceeds to do something in that case, this is the common use-case when it comes to `if`. `elif` however, runs only if the previous condition was not met, and provided it meets the corresponding condition, you can have multiple `elif` statements. `else` statements simply tells the program what to do if no condition was satisfied.

*The next page will contain an example*
---
**An example of how conditionals work, utilizing all `if/elif/else`!**
```py
x = 9 # a variable called x, that equals the integer value 9.

if x > 20: # Our first, inital condition

    # Anything that is indented and underneath that conditional statement will run.
    # However in this case, since x is 9, this code won't be ran, because it doesn't
    # satisfy the condition.
    print("The variable is larger than 20!") 
    
elif x > 10: # A secondary condition

    # This code will also not be ran, because x still doesn't meet the condition
    print("The variable is larger than 10!")
    
else: # Anything that doesn't pass both conditions will end up triggering this
    
    # In this scenario, the code will run, because it does not satisfy any
    # of the conditional statements above!
    print("The variable is smaller than 10!")
```
*Try this yourself, and alter the value of `x` to see how different code is executed depending on the value!*
