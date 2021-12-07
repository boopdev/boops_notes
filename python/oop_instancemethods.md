`These are The Object-Oriented Programming notes, Which aren't taught in Programming 1`
In Object-Oriented python there are numerous different types of methods you can define for your classes. Namely `classmethod`s, `staticmethod`s and `instancemethod`s.

First, and the easiest to understand, are "Instance Methods". Which are methods which can only be used once an instance of the class has been instantiated. These are considerably the closest to regular functions within classes you are going to get. These also have no decorator, and have near identical syntax to functions.

An example of defining and calling an instance method:
```py
class Frog(object):

    # ...

    def jump(self, height : float) -> None:
        print("The frog jumped!")

##############################
>> franklin = Frog()
>> franklin.jump()
> "The frog jumped!"
```
Every Instance Method is passed the "self" argument as its first argument so it can have access to all the variables within the scope of the class. This is incredibly useful in some cases where you dont want a variable to be in global scope, but still want it to be accessible to numerous functions related to the same thing.
