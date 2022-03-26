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
eg.   a = 10
      print(a)
      
      output = 10
in which a = 10 & print(a) both are statements.


# COMMENT

Instructions that you write in your code and that python interpreter ignores are called "Comment".
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

 A      B      A&B    A|B    A^B   NOT A   NOT B
 
True   True   True   True   False  False   False

True   False  False  True   True   False   True

False  True   False  True   False  True    False

False  False  False  False  True   True    True


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

__________________________________________________________________________________

# STRING

String represents group of characters which enclosed either in single quotes or double quotes.
String in python are immutable meanns the value of the object cannot be changed.
If string occupies several lines then we can use triple single quotes or triple double quotes.

eg :-
a = "Tanmay" 
b = 'Tanmay'


# Indexing and Slicing

# String Format

# STRING METHODS
-----------------
# 1) For Change Case
# A. capitalize()
The capitalize() method returns the copy of the string with its first character capitalized and the rest of the letters lowercased.

 Syntax: string.capitalize()

Note:
1.The method only capitalizes the first letter of the string. The rest of the letters are lowercased even if they are capital in the original string.
2. If the first letter is non-alphabetic, then the method doesn't convert it to a capital letter, but it converts all other letters to lowercase.



# B. casefold()
The casefold() method returns a string where all the characters are in lower case. It is similar to the lower() method, but the casefold() method converts more characters into lower case.

 syntax: str.casefold()

Note:
1. Symbols and Letters are not affected by the casefold() method. If the string is in lower cases then casefold() method will return original string.



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
