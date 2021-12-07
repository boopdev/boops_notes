`These are The Object-Oriented Programming notes, Which aren't taught in Programming 1`
**Classmethods** are methods which can be used without an instance being created. Due to this, they do not recieve the first argument `self`, but the first argument is replaced with `cls`, which is the class itself. Class Methods are commonly used to instantiate objects in ways that the traditional `__init__` would not suffice for, and can allow you to create alternative steps along the way!

Classmethods are also denoted with the `@classmethod` decorator.

An example of defining and calling a classmethod:
```py
class Frog(object):
    has_hat : bool = False # Frogs by default has no hat :(

    @classmethod
    def newFrogWithHat(cls) -> "Frog":
        newFrog = cls() # Creating a new `Frog` instance
        newFrog.has_hat = True # Giving the frog a cool hat :)
        return newFrog # Returning the new frog instance

##############################
>> charles = Frog() # Instantiating a new frog the normal way
>> charles.has_hat # Checking to see if charles has a hat
> False # :(

>> wallace = Frog.newFrogWithHat() # Instantiating a new frog with the class method
>> wallace.has_hat # Does wallace have a hat?
> True # No way... Wallace has a cool hat !!!
```