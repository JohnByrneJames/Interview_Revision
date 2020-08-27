# Python Revsion

I am going to write points that I think are important and I find hard to remember

* **Important Points**
1. `#` is a comment in python

2. check type of data with `typeof()`
3. `complex` conversion for real world maths
4. Get index 2 to 4 `txt[2:5]`
5. `replace(to_reaplce,replace_with)`
6. membership operator `in` to check if item is in `list` ECT..
7. adding to `list` with `.append`
8. Inserting item into location in list `list.insert(location, item)`
9. Remove from list `list.remove("item")`
10. Add to set with `add`
11. Add a list to a set, multiple items to a set use `update`, `tuple.update(list)`
12. Set items can be removed with `remove` or `discard`
13. Get key value from dict with `dict.get["key_name"]`
14. Update key value with `dict["key_name"] = new_value`
15. Shorthand `if` statement: `print("Yes") if 5 > 2 else print("No")`
16. Creating a object or instance of a class `p1 = MyClass()`
17. The class `__init__` function to initialise with variables ECT..
18. Use `Super()` to inherit all parent `attributes and methods`.
18. print out all variable and function anme of module with `print(dir(module_name))`

**Python Collections**
1. **LISTS** : `ORDERED` `MUTABLE` `INDEXED` `ALLOW DUPLICATES` `[]`

2. **TUPLES** : `ORDERED` `IMMUTABLE` `ALLOW DUPLICATES` `()`

3. **SET** : `UNORDERED` `UNINDEXED` `MUTABLE` `NO DUPLICATES` `{}`

4. **DICTIONARY** : `UNORDERED` `MUTABLE` `INDEXED` `NO DUPLICATES` `{Key: Value}`

# OOP Object-oriented Programming

Programming that revolves around the concept of objects, and dealing with objects. These objects are what make up the structure of a program by bundling properties `attributes` and behaviours inside them `methods`.

An Object is created when you create a instance from a class, for example:

```python
class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age

  def myfunc(self):
    print("Hello my name is " + self.name)

p1 = Person("John", 36)
p1.myfunc() 
```

Here we are creating p1, as an object and then calling the myfun method inside the class to print out the object. Objects usually have self-reference types such as self, which refers the current instance E.G. our p1 object. 

We have instantiated this object with the values `Name = John` and `age = 36`, now we can use self to fetch these attributes when we need them.

**PILLARS OF OOP**

**1.** **INHERITANCE**

* If a class inherits a class it is known as a `child class` of the `parent class` it has inherited
* It allows you to follow **DRY**; it is done with the `super()` function in python which inherits all the `attributes` and `methods` of the parent class.

**2.** **ENCAPSULATION**

* Restrict access to method and attributes
* Prevent accidental modification of data and unwanted changes
* Encapsulation is not a real thing in python it is purely done by convention using `_` to define protected and `__` to define private which can also be access via name mangling.
* INFORMATION HIDING

**3.** **POLYMORPHISM**

* Multiple different classes can use the same method with differnt outcomes, sometimes this concept is referred to as overriding
* Producing differnent results throught the same method

**4.** **ABSTRACTION**

* extension to encapsulation, only expose components that need to be public (Example: We want a coffe, not to know how its done).
* Encapsulate all behind scenes mechanisms
* IMPLEMENATION HIDING