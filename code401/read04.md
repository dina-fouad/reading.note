## Classes and Objects
Objects are an encapsulation of variables and functions into a single entity. Objects get their variables and functions from classes. Classes are essentially a template to create your objects.

```
class MyClass:
    variable = "blah"

    def function(self):
        print("This is a message inside the class.")

myobjectx = MyClass()
myobjecty = MyClass()

myobjecty.variable = "yackity"

# Then print out both values
print(myobjectx.variable)
print(myobjecty.variable)
```

### output:
```
blah
yackity

```

## The algorithm for iterative present delivery implemented in Python:

```
houses = ["Eric's house", "Kenny's house", "Kyle's house", "Stan's house"]

def deliver_presents_iteratively():
    for house in houses:
        print("Delivering presents to", house)
```

### output :
```
>>> deliver_presents_iteratively()
Delivering presents to Eric's house
Delivering presents to Kenny's house
Delivering presents to Kyle's house
Delivering presents to Stan's house
```

### the function will continue to call itself and repeat its behavior until some condition is met to return a result. All recursive functions share a common structure made up of two parts: base case and recursive case.