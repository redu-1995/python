# Python tutorial

# Python String

A String is a data structure in Python that represents a sequence of characters. It is an immutable data type, meaning that once you have created a string, you cannot change it. Strings are used widely in many different applications, such as storing and manipulating text data, representing names, addresses, and other types of data that can be represented as text.

# What is a String in Python?

**[Python](https://www.geeksforgeeks.org/python-programming-language/)** does not have a character data type, a single character is simply a string with a length of 1.

**Example:**

```
"Geeksforgeeks" or 'Geeksforgeeks' or "a"
```

- Python3

```python
print("A Computer Science portal for geeks")
print('A')
```

---

**Output:**

```
A Computer Science portal for geeks
A

```

# Creating a String in Python

**Strings in Python** can be created using single quotes or double quotes or even triple quotes. Let us see how we can define a string in Python.

**Example:**

In this example, we will demonstrate different ways to create a Python String. We will create a string using single quotes (‘ ‘), double quotes (” “), and triple double quotes (“”” “””). The triple quotes can be used to declare multiline strings in Python.

- Python3

```python
# Python Program for 
# Creation of String 

# Creating a String 
# with single Quotes 
String1 = 'Welcome to the Geeks World'
print("String with the use of Single Quotes: ") 
print(String1) 

# Creating a String 
# with double Quotes 
String1 = "I'm a Geek"
print("\nString with the use of Double Quotes: ") 
print(String1) 

# Creating a String 
# with triple Quotes 
String1 = '''I'm a Geek and I live in a world of "Geeks"'''
print("\nString with the use of Triple Quotes: ") 
print(String1) 

# Creating String with triple 
# Quotes allows multiple lines 
String1 = '''Geeks 
			For 
			Life'''
print("\nCreating a multiline String: ") 
print(String1)
```

---

**Output:**

```
String with the use of Single Quotes:
Welcome to the Geeks World
String with the use of Double Quotes:
I'm a Geek
String with the use of Triple Quotes:
I'm a Geek and I live in a world of "Geeks"
Creating a multiline String:
Geeks
            For
            Life

```

# Python String constants

| Built-In Function | Description |
| --- | --- |
| https://www.geeksforgeeks.org/python-string-ascii_letters/ | Concatenation of the ascii_lowercase and ascii_uppercase constants. |
| https://www.geeksforgeeks.org/python-string-ascii_lowercase/ | Concatenation of lowercase letters |
| https://www.geeksforgeeks.org/python-string-ascii_uppercase/ | Concatenation of uppercase letters |
| https://www.geeksforgeeks.org/python-string-digits/ | Digit in strings |
| https://www.geeksforgeeks.org/python-string-hexdigits/ | Hexadigit in strings |
| string.letters | concatenation of the strings lowercase and uppercase |
| string.lowercase | A string must contain lowercase letters. |
| string.octdigits | Octadigit in a string |
| string.punctuation | ASCII characters having punctuation characters. |
| string.printable | String of characters which are printable |
| https://www.geeksforgeeks.org/string-endswith-python/ | Returns True if a string ends with the given suffix otherwise returns False |
| https://www.geeksforgeeks.org/python-string-startswith/ | Returns True if a string starts with the given prefix otherwise returns False |
| https://www.geeksforgeeks.org/python-string-isdigit-application/ | Returns “True” if all characters in the string are digits, Otherwise, It returns “False”. |
| https://www.geeksforgeeks.org/python-string-isalpha-method/ | Returns “True” if all characters in the string are alphabets, Otherwise, It returns “False”. |
| https://www.geeksforgeeks.org/python-string-isdecimal/ | Returns true if all characters in a string are decimal. |
| https://www.geeksforgeeks.org/python-format-function/ | one of the string formatting methods in Python3, which allows multiple substitutions and value formatting. |
| https://www.geeksforgeeks.org/python-string-index-applications/ | Returns the position of the first occurrence of substring in a string |
| string.uppercase | A string must contain uppercase letters. |
| https://www.geeksforgeeks.org/python-string-isspace-application/ | A string containing all characters that are considered whitespace. |
| https://www.geeksforgeeks.org/python-string-swapcase/ | Method converts all uppercase characters to lowercase and vice versa of the given string, and returns it |
| https://www.geeksforgeeks.org/python-string-replace/ | returns a copy of the string where all occurrences of a substring is replaced with another substring. |

# Python Lists

**Python Lists** are just like dynamically sized arrays, declared in other languages (vector in C++ and ArrayList in Java). In simple language, a list is a collection of things, enclosed in [ ] and separated by commas.

> The list is a sequence data type which is used to store the collection of data. Tuples and String are other types of sequence data types.
> 

# Example of list in Python

Here we are creating Python **List** using [].

- Python3

```python
Var = ["Geeks", "for", "Geeks"]
print(Var)
```

```python
student_list = ['hana','john','dav']
print(type(student_list))
```

---

```python
# Python program to demonstrate
# Creation of List

# Creating a List
List = []
print("Blank List: ")
print(List)

# Creating a List of numbers
List = [10, 20, 14]
print("\nList of numbers: ")
print(List)

# Creating a List of strings and accessing
# using index
List = ["Geeks", "For", "Geeks"]
print("\nList Items: ")
print(List[0])
print(List[2])
```

# Python Tuples

**Tuple** is a collection of Python objects much like a list. The sequence of values stored in a tuple can be of any type, and they are indexed by integers.

Values of a tuple are syntactically separated by ‘commas’. Although it is not necessary, it is more common to define a tuple by closing the sequence of values in parentheses. This helps in understanding the Python tuples more easily.

```python
name = ('hana','john','dav')
print(type(name))
```

```python
# Creating an empty Tuple
Tuple1 = ()
print("Initial empty Tuple: ")
print(Tuple1)

# Creating a Tuple
# with the use of string
Tuple1 = ('Geeks', 'For')
print("\nTuple with the use of String: ")
print(Tuple1)

# Creating a Tuple with
# the use of list
list1 = [1, 2, 4, 5, 6]
print("\nTuple using List: ")
print(tuple(list1))

# Creating a Tuple
# with the use of built-in function
Tuple1 = tuple('Geeks')
print("\nTuple with the use of function: ")
print(Tuple1)
```

**Output:**

```
Initial empty Tuple:
()

Tuple with the use of String:
('Geeks', 'For')

Tuple using List:
(1, 2, 4, 5, 6)

Tuple with the use of function:
('G', 'e', 'e', 'k', 's')
```

# Python Sets

In Python, a **Set** is an unordered collection of data types that is iterable, mutable and has no duplicate elements. The order of elements in a set is undefined though it may consist of various elements. The major advantage of using a set, as opposed to a list, is that it has a highly optimized method for checking whether a specific element is contained in the set.

### Creating a Set

Sets can be created by using the built-in **set()** function with an iterable object or a sequence by placing the sequence inside curly braces, separated by a ‘comma’.

> Note: A set cannot have mutable elements like a list or dictionary, as it is mutable.
> 

```python
# Python program to demonstrate 
# Creation of Set in Python

# Creating a Set
set1 = set()
print("Initial blank Set: ")
print(set1)

# Creating a Set with 
# the use of a String
set1 = set("GeeksForGeeks")
print("\nSet with the use of String: ")
print(set1)

# Creating a Set with
# the use of Constructor
# (Using object to Store String)
String = 'GeeksForGeeks'
set1 = set(String)
print("\nSet with the use of an Object: " )
print(set1)

# Creating a Set with
# the use of a List
set1 = set(["Geeks", "For", "Geeks"])
print("\nSet with the use of List: ")
print(set1)

# Creating a Set with
# the use of a tuple
t=("Geeks","for","Geeks")
print("\nSet with the use of Tuple: ")
print(set(t))

# Creating a Set with
# the use of a dictionary
d={"Geeks":1,"for":2,"Geeks":3}
print("\nSet with the use of Dictionary: ")
print(set(d))
```

**Ouput**

```
Initial blank Set:
set()

Set with the use of String:
{'e', 'G', 's', 'F', 'o', 'r', 'k'}

Set with the use of an Object:
{'e', 'G', 's', 'F', 'o', 'r', 'k'}

Set with the use of List:
{'For', 'Geeks'}

Set with the use of Tuple:
{'for', 'Geeks'}

Set with the use of Dictionary:
{'for', 'Geeks'}
```

```python
student_list = ['hana','john','dav']
print(type(student_list))
```

# Dictionaries in Python

**A dictionary in Python** is a data structure that stores the value in value:key pairs.

**Example:**

```python
Dict = {1: 'Geeks', 2: 'For', 3: 'Geeks'}
print(Dict)
```

**Output:**

```
{1: 'Geeks', 2: 'For', 3: 'Geeks'}
```

```python
student_info ={
    'name':'hana',
    'age':12,
    'sec':'b',
    'height': 1.3,
    'skills':['java','javascript','php']

}
print(student_info['height'])
```

# Python If Else Statements – Conditional Statements

If-Else statements in Python are part of conditional statements, which decide the control of code. As you can notice from the name If-Else, you can notice the code has two ways of directions.

There are situations in real life when we need to make some decisions and based on these decisions, we decide what we should do next. Similar situations arise in programming also where we need to make some decisions and based on these decisions we will execute the next block of code.

Conditional statements in Python languages decide the direction(Control Flow) of the flow of program execution.

# Python if statement

The **[if statement](https://www.geeksforgeeks.org/python3-if-if-else-nested-if-if-elif-statements/)** is the most simple decision-making statement. It is used to decide whether a certain statement or block of statements will be executed or not.

**Syntax**:

```
ifcondition:
   # Statements to execute if
   # condition is true
```

Here, the condition after evaluation will be either true or false. if the statement accepts boolean values – if the value is true then it will execute the block of statements below it otherwise not.

As we know, python uses indentation to identify a block. So the block under an if statement will be identified as shown in the below example:

```
if condition:
   statement1
statement2
# Here if the condition is true, if block
# will consider only statement1 to be inside
# its block.
```

### Example of Python if Statement

As the condition present in the if statement is false. So, the block below the if statement is executed.

```python
# python program to illustrate If statement 

i = 10

if (i > 15): 
	print("10 is less than 15") 
print("I am Not in if")
```

**Output:**

```
I am Not in if
```

# Python If-Else Statement

The if statement alone tells us that if a condition is true it will execute a block of statements and if the condition is false it won’t. But if we want to do something else if the condition is false, we can use the else statement with the if statement to execute a block of code when the if condition is false.

**Syntax of Python If-Else**:

```
if (condition):
    # Executes this block if
    # condition is true
else:
    # Executes this block if
    # condition is false
```

### Using Python if-else statement

The block of code following the else statement is executed as the condition present in the if statement is false after calling the statement which is not in the block(without spaces).

```python
# python program to illustrate If else statement 
#!/usr/bin/python 

i = 20
if (i < 15): 
	print("i is smaller than 15") 
	print("i'm in if Block") 
else: 
	print("i is greater than 15") 
	print("i'm in else Block") 
print("i'm not in if and not in else Block")
```

**Output:**

```
i is greater than 15
i'm in else Block
i'm not in if and not in else Block
```

# Python Functions

**Python Functions** is a block of statements that return the specific task. The idea is to put some commonly or repeatedly done tasks together and make a function so that instead of writing the same code again and again for different inputs, we can do the function calls to reuse code contained in it over and over again.

Some **Benefits of Using Functions**

- Increase Code Readability
- Increase Code Reusability

# Creating a Function in Python

We can define a function in Python, using the **def** keyword. We can add any type of functionalities and properties to it as we require.

# A simple Python function

```python
def fun():
print("Welcome to GFG")
```

# Creating a Function in Python

We can define a function in Python, using the **def** keyword. We can add any type of functionalities and properties to it as we require.

```python
# A simple Python function 

def fun():
print("Welcome to GFG")
```

### alling a Python Function

After creating a function in Python we can call it by using the name of the function followed by parenthesis containing parameters of that particular function.

```python
# A simple Python function
def fun():
	print("Welcome to GFG")

# Driver code to call a function
fun()
```

**Output:**

```
Welcome to GFG

```

# **Python map() function**

**map()** function returns a map object(which is an iterator) of the results after applying the given function to each item of a given iterable (list, tuple etc.)

### Python map() Function Syntax

> Syntax: map(fun, iter)Parameters:fun: It is a function to which map passes each element of given iterable.iter: It is iterable which is to be mapped.NOTE: You can pass one or more iterable to the map() function.Returns: Returns a list of the results after applying the given function to each item of a given iterable (list, tuple etc.)NOTE : The returned value from map() (map object) then can be passed to functions like list() (to create a list), set() (to create a set) .
> 

```python
# Python program to demonstrate working
# of map.

# Return double of n
def addition(n):
	return n + n

# We double all numbers using map()
numbers = (1, 2, 3, 4)
result = map(addition, numbers)
print(list(result))
```

**Output**

```
[2, 4, 6, 8]
```

### **map() with Lambda Expressions**

We can also use **[lambda expressions](https://www.geeksforgeeks.org/python-lambda-anonymous-functions-filter-map-reduce/)** with map to achieve above result. In this example, we are using map() with lambda expression.

```python
# Double all numbers using map and lambda

numbers = (1, 2, 3, 4)
result = map(lambda x: x + x, numbers)
print(list(result))
```

**Output**

```
[2, 4, 6, 8]

```

# Introduction of Object Oriented Programming

As the name suggests, Object-Oriented Programming or OOPs refers to languages that use objects in programming. Object-oriented programming aims to implement real-world entities like inheritance, hiding, polymorphism, etc in programming. The main aim of OOP is to bind together the data and the functions that operate on them so that no other part of the code can access this data except that function.

**OOPs Concepts:**

- Class
- Objects
- Data Abstraction
- Encapsulation
- Inheritance
- Polymorphism

**1. Class:**

A class is a user-defined data type. It consists of data members and member functions, which can be accessed and used by creating an instance of that class. It represents the set of properties or methods that are common to all objects of one type. A class is like a blueprint for an object.

***For Example:*** Consider the Class of Cars. There may be many cars with different names and brands but all of them will share some common properties like all of them will have 4 wheels, Speed Limit, Mileage range, etc. So here, Car is the class, and wheels, speed limits, mileage are their properties.

**2. Object:**

It is a basic unit of Object-Oriented Programming and represents the real-life entities. An Object is an instance of a Class. When a class is defined, no memory is allocated but when it is instantiated (i.e. an object is created) memory is allocated. An object has an identity, state, and behavior. Each object contains data and code to manipulate the data. Objects can interact without having to know details of each other’s data or code, it is sufficient to know the type of message accepted and type of response returned by the objects.

For example “Dog” is a real-life Object, which has some characteristics like color, Breed, Bark, Sleep, and Eats.

![https://media.geeksforgeeks.org/wp-content/uploads/20200901221937/Object-660x185.png](https://media.geeksforgeeks.org/wp-content/uploads/20200901221937/Object-660x185.png)

*Object*

**3. Data Abstraction:**

Data abstraction is one of the most essential and important features of object-oriented programming. Data abstraction refers to providing only essential information about the data to the outside world, hiding the background details or implementation. Consider a real-life example of a man driving a car. The man only knows that pressing the accelerators will increase the speed of the car or applying brakes will stop the car, but he does not know about how on pressing the accelerator the speed is increasing, he does not know about the inner mechanism of the car or the implementation of the accelerator, brakes, etc in the car. This is what abstraction is.

**4. Encapsulation:**

Encapsulation is defined as the wrapping up of data under a single unit. It is the mechanism that binds together code and the data it manipulates. In Encapsulation, the variables or data of a class are hidden from any other class and can be accessed only through any member function of their class in which they are declared. As in encapsulation, the data in a class is hidden from other classes, so it is also known as **data-hiding**.

![https://media.geeksforgeeks.org/wp-content/uploads/20200911171522/EncapsulationinOOPs.png](https://media.geeksforgeeks.org/wp-content/uploads/20200911171522/EncapsulationinOOPs.png)

Consider a real-life example of encapsulation, in a company, there are different sections like the accounts section, finance section, sales section, etc. The finance section handles all the financial transactions and keeps records of all the data related to finance. Similarly, the sales section handles all the sales-related activities and keeps records of all the sales. Now there may arise a situation when for some reason an official from the finance section needs all the data about sales in a particular month. In this case, he is not allowed to directly access the data of the sales section. He will first have to contact some other officer in the sales section and then request him to give the particular data. This is what encapsulation is. Here the data of the sales section and the employees that can manipulate them are wrapped under a single name “sales section”.

**5. Inheritance:**

Inheritance is an important pillar of OOP(Object-Oriented Programming). The capability of a class to derive properties and characteristics from another class is called Inheritance. When we write a class, we inherit properties from other classes. So when we create a class, we do not need to write all the properties and functions again and again, as these can be inherited from another class that possesses it. Inheritance allows the user to reuse the code whenever possible and reduce its redundancy.

![https://media.geeksforgeeks.org/wp-content/uploads/20200911171738/InheritanceinObjectOrientedProgramming.png](https://media.geeksforgeeks.org/wp-content/uploads/20200911171738/InheritanceinObjectOrientedProgramming.png)

**6. Polymorphism:**

The word polymorphism means having many forms. In simple words, we can define polymorphism as the ability of a message to be displayed in more than one form. For example, A person at the same time can have different characteristics. Like a man at the same time is a father, a husband, an employee. So the same person posses different behavior in different situations. This is called polymorphism.

![https://media.geeksforgeeks.org/wp-content/uploads/20200911171857/PolymorphisminObjectOrientedProgramming.png](https://media.geeksforgeeks.org/wp-content/uploads/20200911171857/PolymorphisminObjectOrientedProgramming.png)

# **Python OOPs Concepts**

In Python, object-oriented Programming (OOPs) is a programming paradigm that uses objects and classes in programming. It aims to implement real-world entities like inheritance, polymorphisms, encapsulation, etc. in the programming. The main concept of OOPs is to bind the data and the functions that work on that together as a single unit so that no other part of the code can access this data.

# OOPs Concepts in Python

- Class
- Objects
- Polymorphism
- Encapsulation
- Inheritance
- Data Abstraction

![https://media.geeksforgeeks.org/wp-content/uploads/20230818181616/Types-of-OOPS-2.gif](https://media.geeksforgeeks.org/wp-content/uploads/20230818181616/Types-of-OOPS-2.gif)

*Python OOPs Concepts*

# Python Class

A class is a collection of objects. A class contains the blueprints or the prototype from which the objects are being created. It is a logical entity that contains some attributes and methods.

To understand the need for creating a class let’s consider an example, let’s say you wanted to track the number of dogs that may have different attributes like breed, and age. If a list is used, the first element could be the dog’s breed while the second element could represent its age. Let’s suppose there are 100 different dogs, then how would you know which element is supposed to be which? What if you wanted to add other properties to these dogs? This lacks organization and it’s the exact need for classes.

**Some points on Python class:**

- Classes are created by keyword class.
- Attributes are the variables that belong to a class.
- Attributes are always public and can be accessed using the dot (.) operator. Eg.: Myclass.Myattribute

**Class Definition Syntax:**

```
class ClassName:
   # Statement-1
   .
   .
   .
   # Statement-N

```

### Creating an Empty Class in Python

In the above example, we have created a class named Dog using the class keyword.

```python
# Python3 program to
# demonstrate defining
# a class

class Dog:
	pass
```

# Python Objects

The object is an entity that has a state and behavior associated with it. It may be any real-world object like a mouse, keyboard, chair, table, pen, etc. Integers, strings, floating-point numbers, even arrays, and dictionaries, are all objects. More specifically, any single integer or any single string is an object. The number 12 is an object, the string “Hello, world” is an object, a list is an object that can hold other objects, and so on. You’ve been using objects all along and may not even realize it.

**An object consists of:**

- **State:** It is represented by the attributes of an object. It also reflects the properties of an object.
- **Behavior:** It is represented by the methods of an object. It also reflects the response of an object to other objects.
- **Identity:** It gives a unique name to an object and enables one object to interact with other objects.

To understand the state, behavior, and identity let us take the example of the class dog (explained above).

- The identity can be considered as the name of the dog.
- State or Attributes can be considered as the breed, age, or color of the dog.
- The behavior can be considered as to whether the dog is eating or sleeping.

### Creating an Object

This will create an object named obj of the class Dog defined above. Before diving deep into objects and classes let us understand some basic keywords that will we used while working with objects and classes.

```python
obj = Dog()
```

### **The Python self**

1. Class methods must have an extra first parameter in the method definition. We do not give a value for this parameter when we call the method, Python provides it
2. If we have a method that takes no arguments, then we still have to have one argument.
3. This is similar to this pointer in C++ and this reference in Java.

When we call a method of this object as myobject.method(arg1, arg2), this is automatically converted by Python into MyClass.method(myobject, arg1, arg2) – this is all the special self is about.

### **The Python __init__ Method**

The **[__init__ method](https://www.geeksforgeeks.org/__init__-in-python/)** is similar to constructors in C++ and Java. It is run as soon as an object of a class is instantiated. The method is useful to do any initialization you want to do with your object. Now let us define a class and create some objects using the self and __init__ method.

### Creating a class and object with class and instance attributes

```python
class Dog:

	# class attribute
	attr1 = "mammal"

	# Instance attribute
	def __init__(self, name):
		self.name = name

# Driver code
# Object instantiation
Rodger = Dog("Rodger")
Tommy = Dog("Tommy")

# Accessing class attributes
print("Rodger is a {}".format(Rodger.__class__.attr1))
print("Tommy is also a {}".format(Tommy.__class__.attr1))

# Accessing instance attributes
print("My name is {}".format(Rodger.name))
print("My name is {}".format(Tommy.name))
```

**Output**

```
Rodger is a mammal
Tommy is also a mammal
My name is Rodger
My name is Tommy
```

### Creating Classes and objects with methods

Here, The Dog class is defined with two attributes:

- attr1 is a class attribute set to the value “mammal”. Class attributes are shared by all instances of the class.
- __init__ is a special method (constructor) that initializes an instance of the Dog class. It takes two parameters: self (referring to the instance being created) and name (representing the name of the dog). The name parameter is used to assign a name attribute to each instance of Dog.The speak method is defined within the Dog class. This method prints a string that includes the name of the dog instance.

The driver code starts by creating two instances of the Dog class: Rodger and Tommy. The __init__ method is called for each instance to initialize their name attributes with the provided names. The speak method is called in both instances (Rodger.speak() and Tommy.speak()), causing each dog to print a statement with its name.

class Dog:

```
# class attribute
attr1 = "mammal"

# Instance attribute
def __init__(self, name):
	self.name = name

def speak(self):
	print("My name is {}".format(self.name))

```

# Driver code

# Object instantiation

Rodger = Dog("Rodger")
Tommy = Dog("Tommy")

# Accessing class methods

Rodger.speak()
Tommy.speak()

**Output**

```
My name is Rodger
My name is Tommy

```

# Python Inheritance

Inheritance is the capability of one class to derive or inherit the properties from another class. The class that derives properties is called the derived class or child class and the class from which the properties are being derived is called the base class or parent class. The benefits of inheritance are:

- It represents real-world relationships well.
- It provides the reusability of a code. We don’t have to write the same code again and again. Also, it allows us to add more features to a class without modifying it.
- It is transitive in nature, which means that if class B inherits from another class A, then all the subclasses of B would automatically inherit from class A.

### **Types of Inheritance**

- **Single Inheritance**: Single-level inheritance enables a derived class to inherit characteristics from a single-parent class.
- **Multilevel Inheritance:** Multi-level inheritance enables a derived class to inherit properties from an immediate parent class which in turn inherits properties from his parent class.
- **Hierarchical Inheritance:** Hierarchical-level inheritance enables more than one derived class to inherit properties from a parent class.
- **Multiple Inheritance:** Multiple-level inheritance enables one derived class to inherit properties from more than one base class.

### Inheritance in Python

In the above article, we have created two classes i.e. Person (parent class) and Employee (Child Class). The Employee class inherits from the Person class. We can use the methods of the person class through the employee class as seen in the display function in the above code. A child class can also modify the behavior of the parent class as seen through the details() method.

```python
# Python code to demonstrate how parent constructors
# are called.

# parent class
class Person(object):

	# __init__ is known as the constructor
	def __init__(self, name, idnumber):
		self.name = name
		self.idnumber = idnumber

	def display(self):
		print(self.name)
		print(self.idnumber)
		
	def details(self):
		print("My name is {}".format(self.name))
		print("IdNumber: {}".format(self.idnumber))
	
# child class
class Employee(Person):
	def __init__(self, name, idnumber, salary, post):
		self.salary = salary
		self.post = post

		# invoking the __init__ of the parent class
		Person.__init__(self, name, idnumber)
		
	def details(self):
		print("My name is {}".format(self.name))
		print("IdNumber: {}".format(self.idnumber))
		print("Post: {}".format(self.post))

# creation of an object variable or an instance
a = Employee('Rahul', 886012, 200000, "Intern")

# calling a function of the class Person using
# its instance
a.display()
a.details()
```

**Output**

```
Rahul
886012
My name is Rahul
IdNumber: 886012
Post: Intern
```

# Python Polymorphism

Polymorphism simply means having many forms. For example, we need to determine if the given species of birds fly or not, using polymorphism we can do this using a single function.

### Polymorphism in Python

This code demonstrates the concept of inheritance and method overriding in Python classes. It shows how subclasses can override methods defined in their parent class to provide specific behavior while still inheriting other methods from the parent class.

```python
class Bird:

	def intro(self):
		print("There are many types of birds.")

	def flight(self):
		print("Most of the birds can fly but some cannot.")

class sparrow(Bird):

	def flight(self):
		print("Sparrows can fly.")

class ostrich(Bird):

	def flight(self):
		print("Ostriches cannot fly.")

obj_bird = Bird()
obj_spr = sparrow()
obj_ost = ostrich()

obj_bird.intro()
obj_bird.flight()

obj_spr.intro()
obj_spr.flight()

obj_ost.intro()
obj_ost.flight()
```

**Output**

```
There are many types of birds.
Most of the birds can fly but some cannot.
There are many types of birds.
Sparrows can fly.
There are many types of birds.
Ostriches cannot fly.

```

# Python Encapsulation

Encapsulation is one of the fundamental concepts in object-oriented programming (OOP). It describes the idea of wrapping data and the methods that work on data within one unit. This puts restrictions on accessing variables and methods directly and can prevent the accidental modification of data. To prevent accidental change, an object’s variable can only be changed by an object’s method. Those types of variables are known as private variables.

A class is an example of encapsulation as it encapsulates all the data that is member functions, variables, etc.

![https://media.geeksforgeeks.org/wp-content/uploads/20191013164254/encapsulation-in-python.png](https://media.geeksforgeeks.org/wp-content/uploads/20191013164254/encapsulation-in-python.png)

### Encapsulation in Python

In the above example, we have created the c variable as the private attribute. We cannot even access this attribute directly and can’t even change its value.

```python
# Python program to
# demonstrate private members
# "__" double underscore represents private attribute. 
# Private attributes start with "__".

# Creating a Base class
class Base:
	def __init__(self):
		self.a = "GeeksforGeeks"
		self.__c = "GeeksforGeeks"

# Creating a derived class
class Derived(Base):
	def __init__(self):

		# Calling constructor of
		# Base class
		Base.__init__(self)
		print("Calling private member of base class: ")
		print(self.__c)

# Driver code
obj1 = Base()
print(obj1.a)

# Uncommenting print(obj1.c) will
# raise an AttributeError

# Uncommenting obj2 = Derived() will
# also raise an AtrributeError as
# private member of base class
# is called inside derived class
```

**Output**

```
GeeksforGeeks
```

# Data Abstraction

It hides unnecessary code details from the user. Also,  when we do not want to give out sensitive parts of our code implementation and this is where data abstraction came.

Data Abstraction in Python can be achieved by creating abstract classes.