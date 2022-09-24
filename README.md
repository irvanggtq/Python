# Description

## **Data Type**

The concept of data type is crucial in programming language.
Different types of data can be stored in variables, and different types can perform various functions.
The following categories of data types are included by default in Python:

1. Numbers (int, float, complex):

   -	int is not for decimal numbers.
   -	float is for decimal numbers.
   - complex is for imaginary numbers.

2. Sequence type (string, list, tuple):

    - String (str) is  a data structure of words that stores a sequence of elements, typically characters.
    - List  is items are ordered, changeable, not have to get the same data type, and allow duplicate values. In Python order starts 0 first.
    - Tuple is a collection of objects which ordered and immutable. Tuples are sequences, just like lists. The differences between tuples and lists are,the tuples cannot     be changed unlike lists and tuples use parentheses, whereas lists use square brackets.

3. Boolean (bool): a data type that has only two values, namely true or false

4. Set is an unordered collection of items. Every set element is unique (no duplicates) and must be immutable (cannot be changed).
   However, a set itself is mutable. We can add or remove items from it.
   Sets can also be used to perform mathematical set operations like union, intersection, symmetric difference, etc.

5. Dictionary is an unordered collection of items. Each item of a dictionary has a key/value pair.
   Dictionaries are optimized to retrieve values when the key is known.

## Operation List

### **Range of Indexes**
1. Range of Indexes
   
   To specify a range of indexes by specifying where to start and where to end the range. When specifying a range, the return value will be a new list with the specified items.

2. Range of Negative Indexes

   To start the search from the end of the list, you can use specify negative indexes.

3. Range of Indexes with 3 Parameters
   - parameter 1 (start) : An index specifying at which position to start (included).
   - parameter 2 (stop) : An index specifying at which position to stop (not included).
   - parameter 3 (step) : An integer number specifying the incrementation.

### **Len**

   - To determine how many items a list has, use the **len()** function.

### **Replace**
- To change or replace the value of a specific item, refer to the index number.

### **Add List Items**
- append()
- extend()
- insert()

### **Remove List Items**
- del
- remove()
- pop()

### **Index**
- The **index()** method returns the position at the first occurrence of the specified value.

### **Count**
- The **count()** method returns the number of elements with the specified value.

### **Sort List**
- sort()
- sort(reverse = True)
- reverse()

# Number, Character, and String Transformations

### **String Slicing**
String slicing is the process of obtaining a portion (substring) of a string by using its indices.

### **Number, Character, and String Transformations**
There are several functions to perform transformations on numbers, strings and characters, such as:
upper()
- lower()
- rstrip()
- lstrip()
- strip()
- startswith()
- endswith()

### **Character, and String Transformations**
- startswith()
- endswith()

### **Conversion between data types**
- To convert integer to float in python, you can use the float() with the int passed as argument to it.
- To convert float to integer in python, you can use the int() with the float passed as argument to it.

### **Replacing String Elements**
- The replace() method replaces a specified phrase with another specified phrase.

# Input Output in Python
There are some ways to enter variables on the string, such as:
- Directly merge variables in the print() statement
- Displaying text(string) can use the format string mechanism
- Using the '%' operator coupled with 'specifier argument' 
Python also allows for user input. That means we are able to ask the user for input. 
There are some implementation about input() code

# Operation String 

## Check String in Python
- The **isupper()** method returns True if all the characters are in upper case, otherwise False.
- The **islower()** method returns True if all the characters are in lower case, otherwise False.
- The **isalpha()** method returns True if all the characters are alphabet letters (a-z).
- The **isalnum()** method returns True if all the characters are alphanumeric, meaning alphabet letter (a-z) and numbers (0-9).
- The **isdecimal()** method returns True if all the characters are decimals (0-9).
- The **isspace()** method returns True if all the characters in a string are whitespaces, otherwise False.
- The **istitle()** method returns True if all words in a text start with a upper case letter, and the rest of the word are lower case letters, otherwise False.

## Formatting in String
### 1.	Fill
- The **zfill()** method adds zeros (0) at the beginning of the string, until it reaches the specified length.
- If the value of the len parameter is less than the length of the string, no filling is done.
### 2.	Center align
- The **center()** method will center align the string, using a specified character (space is default) as the fill character. 
- _Syntax_: _string.center(length, character)_.
### 3.	Left align
- The **ljust()** method will left align the string, using a specified character (space is default) as the fill character.
- _Syntax_: _string.ljust(length, character)_.
### 4.	Right align
- The **rjust()** method will right align the string, using a specified character (space is default) as the fill character.
- _Syntax_: _string.rjust(length, character)_.
### 5.	Raw string
- Raw string, when you want to type symbol in string but won't read as function using "r" or (\) if you want insert escape char/symbol.

