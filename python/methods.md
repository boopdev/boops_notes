**Methods** are a type of function which specifically applies to objects. For instance, the `.upper()` and `.lower()` functions, are methods for string objects. There are numerous kinds of methods for many of the different types in Python. 

A few examples of calling methods:
```py
>> myAnimalRatings = {"fish" : 3, "cat" : 4, "dog" : 5, "bird" : 2, "frog" : 10}

>> myAnimalRatings.get("fish") # Gets the rating for fish
> 3 # Returns the value corresponding to that key for the dict

>> myAnimalRatings.get("fox", 0) # Gets the rating for foxes
> 0 # Returns "0" because that's the default value we specified.
```
