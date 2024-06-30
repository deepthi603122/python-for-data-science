# Variables
Variables in Python are used to store data that can be used and manipulated throughout your program. You don't need to declare the type of variable; Python infers it automatically.

x = 5<br>
y = "Hello, World!"<br>
z = 3.14<br>
<h1>Operators</h1>
Operators are used to perform operations on variables and values.

<h3>Arithmetic Operators</h3>
a = 10<br>
b = 3<br>
print(a + b)  # Addition<br>
print(a - b)  # Subtraction<br>
print(a * b)  # Multiplication<br>
print(a / b)  # Division<br>
print(a % b)  # Modulus<br>
print(a ** b) # Exponentiation<br>
print(a // b) # Floor division<br>
<h3>Comparison Operators</h3>
print(a == b)  # Equal<br>
print(a != b)  # Not equal<br>
print(a > b)   # Greater than<br>
print(a < b)   # Less than<br>
print(a >= b)  # Greater than or equal to<br>
print(a <= b)  # Less than or equal to<br>
<h3>Logical Operators</h3>
x = True<br>
y = False<br>
print(x and y) # Logical AND<br>
print(x or y)  # Logical OR<br>
print(not x)   # Logical NOT<br>
# Strings
Strings are sequences of characters, enclosed in single or double quotes.

python
s = "Hello, World!"
print(s.upper())         # Convert to uppercase<br>
print(s.lower())         # Convert to lowercase<br>
print(s[0])              # Access first character<br>
print(s[0:5])            # Slice the string<br>
print(s.replace("Hello", "Hi"))  # Replace substring<br>
# Lists
Lists are ordered collections that are mutable (can be changed).

python
my_list = [1, 2, 3, 4, 5]<br>
print(my_list)<br>
my_list.append(6)        # Add an item<br>
print(my_list)<br>
print(my_list[2])        # Access third item<br>
my_list[1] = 22          # Change second item<br>
print(my_list)<br>
# Tuples
Tuples are ordered collections that are immutable (cannot be changed).

my_tuple = (1, 2, 3, 4, 5)<br>
print(my_tuple)<br>
print(my_tuple[1])       # Access second item<br>
# Sets
Sets are unordered collections with no duplicate elements.

my_set = {1, 2, 3, 4, 5}<br>
print(my_set)<br>
my_set.add(6)            # Add an item<br>
print(my_set)<br>
my_set.remove(3)         # Remove an item<br>
print(my_set)<br>
# Dictionaries
Dictionaries are collections of key-value pairs.

my_dict = {"name": "Alice", "age": 25, "city": "New York"}<br>
print(my_dict)<br>
print(my_dict["name"])   # Access value by key<br>
my_dict["age"] = 26      # Change value<br>
print(my_dict)<br>
my_dict["country"] = "USA"  # Add a new key-value pair<br>
print(my_dict)<br>
These are basic introductions to each of these concepts in Python. Each of these can be explored in much more detail depending on your needs.
