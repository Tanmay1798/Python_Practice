# Python

1) What is Python?
--  Python is an Interpreted, Object-Oriented, High Level and Dynamic typing language.

2) Who introduced Python?
--  "Guido Van Rossum" introduced python in 1991. He is a Dutch Programmer.

3) Features of Python?

 . Easy to learn and Maintain

 . A broad standard library 
 
 . Open source

 . Portable

 . Object-oriented

 . Easy to use


4) Where to use Python?

 . System Programming

 . Web Application Development 
 
 . Software Development
 
 . Data Analysis
 
 . AL (Artificial Intelligence)
 
 . ML (Machine Learning)
 
 . IOT

_________________________________________________________________

# VARIABLE
Variables are names that can be assigned a value and then used to refer to that value throughout your code.
Rules:-
1) Variable names should start with letter (a-z).
2) A variable can start with "_"(underscore) also.
3) In variable we can't use special character.
4) We can use number but not at the beginning.
5) Keywords are not allowed as keyword.

________________________________________________________________

# Interpreter vs Compiler
 
INTERPRETER
1) Translate program one statement at a time.
2) Continues translating the program until the first error is met in which case it stops. Hence debugging is easy.
3) Programming language like Python , Ruby , etc. use Interpreter.

COMPILER
1) Scans the entire program and translate it as a whole into machine code.
2) It generates the error message only after scanning the whole program. Hence, debugging is hard as compared to Interpreter.
3) Programming language like C , C++ , Java , etc. use Compiler.

__________________________________________________________________

# STATEMENT

Instructions that you write in your code and that a python interpreter can execute are called "Statement".
In Python, the end of a statement is marked by a newline character. But we can make a statement extend over multiple lines with the line continuation character ().
eg.   a = 10
      print(a)
      
      output = 10
in which a = 10 & print(a) both are statements.


# COMMENT

Instructions that you write in your code and that python interpreter ignores are called "Comment".

Comments are very important while writing a program. They describe what is going on inside a program, so that a person looking at the source code does not have a hard time figuring it out.
You might forget the key details of the program you just wrote in a month's time. So taking the time to explain these concepts in the form of comments is always fruitful.In Python, we use the hash (#) symbol to start writing a comment.
#This is a comment #print out Hello print('Hello')
Multi-line comments:-
We can have comments that extend up to multiple lines. One way is to use the hash(#) symbol at the beginning of each line.
eg """This is also a perfect example of multi-line comments"""

Denoted by 3 type
1) '#' Hash sign
2) ' ' ' --------------
    ----------- ' ' ' .
3) " " " --------------
    ----------- " " " .

# KEYWORD
Keywords are the reserved words in python. These reserved words cannot be used as function names , variable names , or any other identifiers.


eg:-
and | as | break| class | continue | def |del |elif | else | except | False | finally |for | from | global | if| import | in | is | lamba | None | nonlocal | not | or | pass | raise | return | True | try | while | with | yield


# INDENTATION
Indentation in Python refers to the (space and tab) that are used at the beginning of a statement or code we write.
1) Using indentation for a bunch of code is extremely elegant and contributes a lot to the clarity of any python program.
2) Our code starts looking well organized and more readable.

______________________________________________________________________

# DYNAMIC TYPING
In python, variables are reserved memory locations to store values. Python is a dynamically typed language in which it is not required to mention the type of a variable while declaring. It performs type checking at run time.

eg:- a = 10

# STATIC TYPING 
In statically typed programming languages, which is required to mention the type of variable while declaring. It performs type checking at compile time.

eg:- int a = 10

_________________________________________________________________________

# DATA TYPES

1) Integer
2) Float
3) Complex
4) String
5) List
6) Tuple
7) Set
8) Dictonary
9) Boolean

_________________________________________________________________________

# OPERATORS

# ARITHMETIC OPERATORS 
1) Addition ( + )
2) Subtraction ( - )
3) Multiplication ( * )
4) Division ( / )
5) Floor Division ( // )  {Floor Divison means division of operation where result is quotient in which digits are removed after decimal point.}
6) Modulus ( % )
7) Exponent ( ** ) 


# RELATIONAL OPERATORS
1) Greater than ( > )
2) Less than ( < )
3) Equal to ( == )
4) Not equal to ( != )
5) Greater than or equal to ( >= )
6) Less than or equal to ( <= )


# ASSIGN OPERATORS
1) Assign ( = )
2) Add and Assign ( += )
3) Subtract and assign ( -= )
4) Multiplication and assign ( *= )
5) Division and assign ( /= )
6) Floor Division and assign ( //= )
7) Modulus and assign ( %= )
8) Exponent and assign ( **= )


# LOGICAL OPERATORS
1) and ->  The logical "and" operator returns True if both expression are true or else return False. 
2) or  ->  The logical "or" operator returns True if one expression is true or else return False. 
3) not ->  The logical "not"  operator returns True if expression is False. 
 

# MEMBERSHIP OPERATORS
1) in -> variable is present in sequence.
2) not in  -> variable is not present in sequence.


# IDENTITY OPERATORS 
1) is -> variable is pointing to same object.
2) not is -> variable is not pointing to same object.


# BITWISE OPERATORS
1) & -> Bitwise and
2) | -> Bitwise 0r
3) ^ -> Bitwise xor 


# TRUTH TABLE

![G2](https://user-images.githubusercontent.com/83057230/169220444-bb480e62-d4b7-49e8-8926-4a72c67b0ff2.png)



_________________________________________________________________________

# NUMERIC DATA TYPES
Numeric data type in Python is generally in three formats, namely Integer, Float, and Complex.

We can create an integer variable using the two ways:
1. Directly assigning an integer value to a variable

eg :-
a = 10
print(type(a))

output = <class 'int'>

2. Using an int() or float() class.

eg :-
a = int(25)
print(a)
print(type(a))

ouput = 25 
        <class 'int'>
        
# TYPE CASTING

Ther are two types "Implicit" And "Explicit".
# 1. Implicit Type Conversion 
Compatible data types are in general two numeric data types like int and float. It will
convert the smaller data type to larger one to prevent any data loss. 

For eg:- int data will be converted to float.

# 2. Explicit Type Conversion
Explicit Type Conversion, users convert the data type of an object to the required
data type.

Key Points to Remember:-
Type Conversion is the conversion of object from one data type to another data type.

Implicit Type Conversion is automatically performed by the Python interpreter.

Python avoids the loss of data in Implicit Type Conversion.

Explicit Type Conversion is also called Type Casting, the data types of objects are converted using predefined functions by the user.

In Type Casting, loss of data may occur as we enforce the object to a specific data type.

__________________________________________________________________________________

# STRING

The string represents a group of characters enclosed either in single quotes or double-quotes.
String in python is immutable means the value of the object cannot be changed.
If the string occupies several lines then we can use triple single quotes or triple double-quotes.

eg :-
a = "Tanmay" 
b = 'Tanmay'


# Indexing and Slicing
 >Indexing

Indexing means referring to an element of an iterable by its position within the iterable. Each of a string’s characters corresponds to an index number and each character can be accessed using its index number. We can access characters in a String in Two ways :

Accessing Characters by Positive Index Number
Accessing Characters by Negative Index Number

1. Accessing Characters by Positive Index Number:

In this type of Indexing, we pass a Positive index(which we want to access) in square brackets. The index number starts from index number 0 (which denotes the first character of a string).

2. Accessing Characters by Negative Index Number: 

In this type of Indexing, we pass the Negative index(which we want to access) in square brackets. Here the index number starts from index number -1 (which denotes the last character of a string).

![Index-in-Python-1024x508](https://user-images.githubusercontent.com/83057230/169007577-97b85cb4-56a2-47e5-86ee-26b527321fc1.png)


> Slicing

Slicing in Python is a feature that enables accessing parts of the sequence. In slicing a string, we create a substring, which is essentially a string that exists within another string. We use slicing when we require a part of the string and not the complete string.

string[start : end : step]

start : We provide the starting index.

end : We provide the end index(this is not included in substring).

step : It is an optional argument that determines the increment between each index for slicing.

# String Format

String formatting is the process of infusing things in the string dynamically and presenting the string. There are four different ways to perform string formatting:-

1. Formatting with % Operator.
2. Formatting with format() string method.
3. Formatting with string literals, called f-strings.
4. Formatting with String Template Class


@ 1. Formatting string using % Operator

It is the oldest method of string formatting. Here we use the modulo % operator. The modulo % is also known as the “string-formatting operator”.

>Example:  

print("The mangy, scrawny stray dog %s gobbled down" +
      "the grain-free, organic dog food." %'hurriedly')


>Output:   

The mangy, scrawny stray dog hurriedly gobbled down the grain-free, organic dog food. 


--> You can also inject multiple strings at a time and can also use variables to insert objects in the string.

>Example:

x = 'looked'
print("Misha %s and %s around"%('walked',x))


>Output: 

Misha walked and looked around.


--> ‘%s’ is used to inject strings similarly ‘%d’ for integers, ‘%f’ for floating-point values, and ‘%b’ for binary format. For all formats, and conversion methods visit the official documentation.

>Example:

print('Joe stood up and %s to the crowd.' %' spoke')

print('There are %d dogs.' %4)


>Output: 

Joe stood up and spoke to the crowd.

There are 4 dogs.


>Float precision with the placeholder method:

Floating-point numbers use the format %a.bf. Here, a would be the minimum number of digits to be present in the string; these might be padded with white space if the whole number doesn’t have this many digits. Close to this, bf represents how many digits are to be displayed after the decimal point. 

> Example:

print('The value of pi is: %5.4f' %(3.141592))

> Output:

The value of pi is: 3.1416


--> You can use multiple format conversion types in a single print statement.


-----------

@ 2. Formatting string using format() method

Format() method was introduced with Python3 for handling complex string formatting more efficiently. Formatters work by putting in one or more replacement fields and placeholders defined by a pair of curly braces { } into a string and calling the str. format(). The value we wish to put into the placeholders and concatenate with the string passed as parameters into the format function. 

> Syntax: ‘String here {} then also {}’.format(‘something1′,’something2’)


> Example  :

print('We all are {}.'.format('equal'))

print('{2} {1} {0}'.format('directions','the', 'Read'))
                           
print('a: {a}, b: {b}, c: {c}'.format(a = 1,b = 'Two',c = 12.3))  
  
  
> Output :

We all are equal.
 
Read the directions.
  
a: 1, b: Two, c: 12.3  
  
  
--> We can reuse the inserted objects to avoid duplication:  

> Example  :

print('The first {p} was alright, but the {p} {p} was tough.'.format(p = 'second'))

> Output :

The first second was alright, but the second second was tough. 


--> Float precision with the.format() method:

>Syntax: {[index]:[width][.precision][type]}

![G1](https://user-images.githubusercontent.com/83057230/169017996-4e7dfe00-710f-42c2-a8c5-69ce44262b4c.png)

---------------

@ 3. Formatted String using F-strings

PEP 498 introduced a new string formatting mechanism known as Literal String Interpolation or more commonly as F-strings (because of the leading f character preceding the string literal). The idea behind f-strings is to make string interpolation simpler.

To create an f-string, prefix the string with the letter “ f ”. The string itself can be formatted in much the same way that you would with str.format(). F-strings provide a concise and convenient way to embed python expressions inside string literals for formatting.

> Example 1:

name = 'Ele'
 
print(f"My name is {name}.")

> Output :

My name is Ele.

> Example 2:
    
a = 5
 
b = 10
 
print(f"He said his age is {2 * (a + b)}.")

> Output :                           
                           
He said his age is 30.                           

------------------

@ 4. Formatting with String Template Class

In the String module, Template Class allows us to create simplified syntax for output specification. The format uses placeholder names formed by $ with valid Python identifiers (alphanumeric characters and underscores). Surrounding the placeholder with braces allows it to be followed by more alphanumeric letters with no intervening spaces. Writing $$ creates a single escaped $:

> Python String Template:

The Python string Template is created by passing the template string to its constructor. It supports $-based substitutions. This class has 2 key methods: 

1.substitute(mapping, **kwds):

This method performs substitutions using a dictionary with a process similar to key-based mapping objects. keyword arguments can also be used for the same purpose. In case the key-based mapping and the keyword arguments have the same key, it throws a TypeError. If keys are missing it returns a KeyError.

2.safe_substitute(mapping, **kwds):

The behavior of this method is similar to that of the substitute method but it doesn’t throw a KeyError if a key is missing, rather it returns a placeholder in the result string. 

> Example 1: 

from string import Template

t = Template('x is $x')

print (t.substitute({'x' : 1}))

> Output:  

x is 1


> Example 2: 

t = Template('I am $name from $city')

print('Template String =', t.template)

> Output: 

Template String = I am $name from $city 


-->Escaping $ Sign

-->The $$ can be used to escape $ and treat as part of the string. 

> Example:

template = Template('$$ is the symbol for $name')

string = template.substitute(name='Dollar')

print(string)

> Output: 

$ is the symbol for Dollar 

-------------

# STRING METHODS

# 1) For Change Case
# A. capitalize()
The capitalize() method returns the copy of the string with its first character capitalized and the rest of the letters lowercased.

 Syntax: string.capitalize()

Note:
1. The method only capitalizes the first letter of the string. The rest of the letters are lowercased even if they are capital in the original string.
2. If the first letter is non-alphabetic, then the method doesn't convert it to a capital letter, but it converts all other letters to lowercase.



# B. casefold()
The case folds() method returns a string where all the characters are in lower case. It is similar to the lower() method, but the casefold() method converts more characters into lower cases.

 syntax: str.casefold()

Note:
1. Symbols and Letters are not affected by the case fold() method. If the string is in lower cases then the casefold() method will return the original string.



# C. upper()
The upper() method returns a string in the upper case. Symbols and numbers remain unaffected.

The main difference between the capitalize() and the upper() method is that the capitalize() method will capitalize only the first character of the string, whereas the upper() will convert all characters in the upper case.

 syntax: str.upper()

Note:
1. The upper() method will ignore numbers and symbols.



# D. lower()
The lower() method returns the copy of the original string wherein all the characters are converted to lowercase. If no uppercase characters present, it returns the original string. Symbols and numbers remain unaffected by this function.

 syntax: str.lower()

Note:
The lower() method will ignore numbers and symbols.



# E. swapcase()
The swapcase() method returns a copy of the string with uppercase characters converted to lowercase and vice versa. Symbols and letters are ignored.

 syntax: str.swapcase()



# F. title()
The title() method returns a string where each word starts with an uppercase character, and the remaining characters are lowercase. If the word contains a number or a symbol, the first letter after that will be converted to upper case.

 syntax: str.title()

Note:
1. The numeric string and symbols are ignored. However, if an alphabet comes immediately after a number, then it converts it to uppercase.







# 2) For FIND
# A. find()
The find() method returns the index of the first occurence of a substring in the given string (case-sensitive). If the substring is not found it returns -1. Returns an integer value indicating an index of the first occurence of the specified substring.

Syntax: str.find(substr, start, end)

1. substr: (Required) The substring whose index has to be found.
2. start: (Optional) The starting index position from where the searching should start in the string. Default is 0.
3. end: (Optional) The ending index position untill the searching should happen. Default is end of the string.

Note:
1. The find() method returns an index of the first occurence only.
2. The find() method performs case-sensitive search. It returns -1 if a substring is not found.



# B. index()
The index() method returns the index of the first occurence of a substring in the given string. It is same as the find() method except that if a substring is not found, then it raises an exception. An integer value indicating an index of the specified substring.

Syntax: str.index(substr, start, end)

Note:
1. The index() method returns an index of the first occurance only.
2. The index() method performs case-sensitive search. It throws ValueError if a substring not found.



# C. rfind()
The rfind() method returns the highest index of the specified substring (the last occurrence of the substring) in the given string. If the substring is not found, then it returns -1. Returns an integer value indicating an index of the last occurence of the specified substring.

Syntax: str.rfind(substr, start, end)

Note:
1. The rfind() method returns an index of the last occurance only.
2. The rfind() method performs case-sensitive search. It returns -1 if a substring is not found.



# D. rindex()
The rindex() method is same as the rfind() that returns the index of the last occurence of a substring in the given string. However, unlike the rfind() method, it raises ValueError if the substring is not found.An integer value indicating an index of the last occurence of the specified substring.

Syntax: str.rindex(substr, start, end)

Note:
1. The rindex() method returns an index of the last occurance only.
2. The rindex() method performs case-sensitive search. It raises ValueError if a substring is not found. However, the rfind() method returns -1 if substring not found.





# 3) For Checking Starting and Ending
# A. startswith()
The startswith() method returns True if a string starts with the specified prefix. If not, it returns False. A tuple of prefixes can also be specified to look for.
Returns True if a string prefixed with the specified prefix; otherwise, returns False.

Syntax: str.startswith(prefix, start, end)

prefix : Required. String or tuple of strings to look for.

start : Optional. The index position of the character in the string from which the search should start.

end : Optional. The index position of the character in the string at which the search should end.

Note:
1. The startswith() search is case-sensitive.
2. The start and end parameters limit the checking of a prefix in a string as indexes. An index starts from 0, i.e. first char's index is 0, second char's index is 1, and so on. If the end parameter is not specified, then it search till the end of a string.



# B. endswith()
The endswith() function returns True if a string ends with the specified suffix (case-sensitive), otherwise returns False. A tuple of string elements can also be passed to check for multiple options. If a string ends with any element of the tuple then the endswith() function returns True.

It checks for suffix from starting index to ending index position. Index starts from 0. By default, it checks the whole string if starting and ending index is not specified.

Syntax: str.endswith(suffix, start, end)

suffix : (Required) String or tuple of strings to look for.

start : (Optional) Starting index at which search should start. Defaults to 0.

end : (Optional) Ending index at which the search should end. Defaults to the last index of a string.

Note:
1. The endswith() function will always return True if an empty string is passed as a parameter.

# 4) For Remove Space
# A. strip()
The strip() method returns a copy of the string by removing both the leading and the trailing characters. By default, it removes leading whitespaces if no argument passed. 
Returns a string.

Syntax: str.strip(character)

characters: (Optional) a string to be removed from the starting and ending of a string. By default, it removes all leading and trailing whitespaces if no argument is specified.

Note:

1.You can specify one or more characters as a string to be removed from the string in any order.



# B. rstrip()
The rstrip() method returns a copy of the string by removing the trailing characters specified as argument. If the characters argument is not provided, all trailing whitespaces are removed from the string.
Trailing characters are those characters which occur at the end of the string (rightmost part of the string).

Syntax : str.rstrip(characters)

characters: (optional) A char or string to be removed from the end of the string.

Note:

1. You can specify one or more characters as a string to be removed from the string in any order.



# C. lstrip()
The lstrip() method returns a copy of the string by removing leading characters specified as an argument. By default, it removes leading whitespaces if no argument passed.

Leading characters occur at the start of the string (leftmost part of the string).

Syntax: str.lstrip(Characters)

characters: (optional) A char or string to be removed from the starting of the string.

Note:
1. You can specify one or more characters as a string to be removed from the string in any order.


# 5) For Split and Remove Split
# A. split()
The split() method splits the string from the specified separator and returns a list object with string elements. The default separator is any whitespace character such as space, \t, \n, etc. Returns a list object with string elements.

Syntax: str.split(separator, maxsplit)
1. separator: (optional) The delimiter string. The default separator is any whitespace character such as space, \t, \n, etc.
2. maxsplit: (optional) Defines the maximum number of splits that can be done. Thus, the list can contain at most maxsplit + 1 elements. The default maxsplit is -1 that means unlimited splits.

Note:
1. If the specified seperator does not exist, then it returns a list with the whole string as an element.
2. The split() method will raise the ValueError if a separator is an empty string ''.



# B. rsplit()

The rsplit() method is same as split method that splits a string from the specified separator and returns a list object with string elements. The default separator is any whitespace character such as space, \t, \n, etc.

The only difference between the split() and rsplit() is when the maxsplit parameter is specified. If the maxsplit parameter is specified, then the rsplit() method starts splitting a string from the right side (from the last character), whereas the split() method starts splitting from the left side (from the first character).

Returns a list object with string elements.

Syntax: str.rsplit(separator, maxsplit)

separator: (optional) The delimiter string. The default separator is any whitespace character such as space, \t, \n, etc.

maxsplit: (optional) Defines the maximum number of splits that can be done. Thus, the list can contain at most maxsplit + 1 elements. The default maxsplit is -1 that means unlimited splits.

Note:
1. If the specified seperator does not exist, then it returns a list with the whole string as an element.
2. The rsplit() method will raise the ValueError if a separator is an empty string ''.




# 6) For Join
# A. join()
The join() method returns a string, which is the concatenation of the string (on which it is called) with the string elements of the specified iterable as an argument. Returns a string.

Syntax: str.join(iterable)

iterable: (Required) An iterable object such as list, tuple, string, set, dict.


The elements of an iterable must be string elements, otherwise it will raise a TypeError.
The join() method concatenates the keys. If keys are not strings, then it will raise a TypeError.




-------------------------------------------------------------------------------
_______________________________________________________________________________

# DATA STRUCTURE

# LIST 

List is a collection of different values or different types of items.

propwerties of list :-
1. Mutable

The list is a data type that is mutable. Once a list has been created: Elements can be modified. Individual values can be replaced.

2. Ordered

When we say that lists are ordered, it means that the items have a defined order, and that order will not change.

3. Heterogenous

The items stored can be of any type numeric, string, boolean, objects, etc which makes it heterogeneous. This means that a list can have any type of data and we can iterate over this list using any type of loop.

4. Duplicate

Since lists are indexed, lists can have items with the same value
CREATE LIST :

The list can be created using either the list constructor or using square brackets '[]'.

eg.   a = [1,2,3]
      
# Accessing items of a List

The item in a list can be accessed through Indexing and Slicing.

# indexing

1. Positive or forward indexing
for eg.  list1[0] , list1[5]

2. Negative or backward indexing
for eg.  list1[-2] , list1[-12]


# slicing

list1[_:_:_] = list1[start:end:step]


# List Methods

# UPDATE & DELETE From List

# Add List Items

# 1. insert()
To insert a new list item, without replacing any of the existing values, we can use the insert() method.

a=["apple","banana","cherry"]
a.insert(2,"watermelon")
print(a)

output :- ['apple', 'banana', 'watermelon', 'cherry']


# 2. append()
Accept only one parameter and it at the end of the list.

a = ["apple","banana","cherry"]
a.append("watermelon")
print(a)

output :- ['apple', 'banana', 'cherry', 'watermelon']


# 3. extend()
Accept the list of elements and add them at the end of the list. we can even add another list by using this method.

a = ["apple","banana","cherry"]
a.extend(["watermelon","kiwi"])
print(a)

output :- ['apple', 'banana', 'cherry', 'watermelon', 'kiwi']



# Remove List Items

# 1. remove()
The remove() method removes the specified item.

a=["apple","banana","cherry"]
a.remove("banana")
print(a)

output :- ['apple', 'cherry']


# 2. pop()
The pop() method removes the specified index.

a=["apple","banana","cherry"]
a.pop(1)
print(a)

output :- ['apple', 'cherry']

Note :- If you do not specify the index, the pop() method removes the last item.


# 3. del
The del keyword also removes the specified index.

a = ["apple","banana","cherry"]
del a[1]
print(a)

output :- ['apple', 'cherry']

Note :- #The del keyword can also delete the list completely.

list1=["apple","banana","cherry"]
del list1


# 4. clear()
The clear() method empties the list. The list still remains, but it has no content.

list2 = ["apple","banana","cherry"]
list2.clear()
print(list2)

output :- []



# Concatenate of two lists

The concatenation of two lists means merging of two lists.

1. using '+' operator

2. using extend()


# 1. Using  "+" operator

my_list1 = [1,2,3]
my_list2 = [4,5,6]

my_list3 = my_list1+ my_list2
print(my_list3)

Output :- [1, 2, 3, 4, 5, 6]


# 2. using extend()

a = ["apple","banana","cherry"]
b = [1,2,3]
a.extend(b)
print(a)

Output :- ['apple', 'banana', 'cherry', 1, 2, 3]




# Copying a List

1. using '=' operator # deep copying(The changes that we make in the original list will be reflected in the newlist.)

2. Using the copy() method

3. using the list() method
