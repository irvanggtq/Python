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

# Operation List

### **Range of Indexes**
1. Range of Indexes
   
   To specify a range of indexes by specifying where to start and where to end the range. When specifying a range, the return value will be a new list with the specified items.

2. Range of Negative Indexes

   To start the search from the end of the list, you can use specify negative indexes.

3. Range of Indexes with 3 Parameters
   - parameter 1 (start): An index specifying at which position to start (included).
   - parameter 2 (stop) : An index specifying at which position to stop (not included).
   - parameter 3 (step) : An integer number specifying the incrementation.

### **Len**

   To determine how many items a list has, use the **len()** function.

### **Replace**
To change or replace the value of a specific item, refer to the index number.

### **Add List Items**
- append()
- extend()
- insert()

### **Remove List Items**
- del
- remove()
- pop()

### **Index**
The **index()** method returns the position at the first occurrence of the specified value.

### **Count**
The **count()** method returns the number of elements with the specified value.

### **Sort List**
- sort()
- sort(reverse = True)
- reverse()

