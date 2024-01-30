# DailyLearnings_in_PYTHON_and_AIML-

## PYTHON NOTES

### DAY 1:

#### Introduction to Python:

Python was created by Guido van Rossum and first released on February 20, 1991.
The name of the Python programming language comes from an old BBC television comedy sketch series called Monty Python’s Flying Circus.
Python is a widely used, interpreted, object-oriented, high level language with dynamic semantics. It is used for general purpose programming.


#### Advantages of using Python in programming:

•	Python is easy to read and understand. The syntax is straightforward and has no complex structures like C++ or Java. It uses English keywords and there is no need of delimiters. 

•	We need to write fewer lines of code to develop applications compared to other programming languages. So it is easy to update and maintain the code thus saving time and effort.

•	Python supports multiple programming paradigms like object-oriented, procedural and functional programming.

•	It has an extensive and robust library. There are multiple packages and modules to enhance its functionality.

•	Python is an open source language that helps developers significantly reduce development costs. Several open source frameworks, libraries and other development tools are available.


#### Disadvantages of using Python in programming:

•	Python is an interpreted language. The interpreter executes codes relatively slower than a compiler. So its execution speed is lower compared to compiled languages like Java and C++.

•	Python’s data structures require more memory space. So there is large memory consumption.

•	The python database access layer is a little primitive and underdeveloped. So it is insecure and involves security risks.

•	Since Python is a dynamically typed language, the interpreter automatically interprets the data type of a variable based on the value assigned to it, thus resulting in runtime errors.


#### Applications of Python:

•	Web Server Programming

•	Prototyping

•	Game development (using GUI libraries)

•	Data Science and Machine Learning




### DAY 2:


#### Python Programming:

Once Python starts, the python interpreter prompt can be seen, i.e., “>>>” which is also known as python chevron prompt. The “>>>”indicates that Python interpreter is waiting for an expression or command. The interactive environment where we interact with the Python interpreter is called the console or command shell.
Comments:    Python uses the hash character (#) for comments. Putting # before a text ensures that the text will not be parsed by the interpreter. It is single line comment. For multi-line comment enclose the lines within (‘‘‘  ’’’).
Identifier: It is the name given to a variable, function, class, module or other object. An identifier can begin with an alphabet (A – Z or a – z), or an underscore (_) and can include any number of letters, digits, or underscores. Spaces are not allowed. Python will not accept @, $ and % as identifiers. Furthermore, Python is a case-sensitive language.

#### Variables: 
Variables are used to store data values. Python is dynamically typed, meaning the data type need not to be declared explicitly.

1. Declaring a variable: In Python, variables need not to be explicitly declared for reserving memory spaces. Python Interpreter automatically does the declaration process while initializing it.

2. Initializing the variable: The format is 
Variable = expression


#### Data types:

1.	Numeric: It can be broadly divided into integers and floating point numbers. Python does not have any upper bound on the size of the integers.

2.	String: String is a sequence of alphabets, numerals and special characters. Single quotes or double quotes represent a string. 1st character of a string has index 0.
Several operations can be performed on a string like slice operator ([] and [:]), concatenation operator (+), repetition operator (*), etc. 

3.	List: It is an ordered and indexable sequence of both homogeneous and heterogeneous types of items. Lists are mutable.

first  = [1,”two”,3.5,”four”]

4.	Tuple: It is similar to a list. The tuples are enclosed within parenthesis. Tuples are immutable. They are read only lists.

third= (2,”three”, 4.6)

5.	Dictionary: It is the same as the hash table. It is an ordered collection of key-value pairs. Keys and values can be of any type.

dict1= {1:”first”, “second”:2}

dict1 [3] =”third”

6.	Boolean: Data can be stored in the form of ‘Yes’ or ‘No’. ‘Yes’ is equivalent to ‘True’ and ‘No’ is equivalent to ‘False’.

7.	Sets: It is an unordered collection of data. It does not contain any redundant value. Union (|), Intersection (&), Difference (-) and Symmetric Difference (^) are some operations performed on sets.



### DAY 3:


#### Basic Operations:
1.	Arithmetic: These include addition (+), subtraction (-), multiplication (*), division (/), exponent (**), modulus (%), floor division (//).

2.	Comparison: These include equality (==), inequality (!= or <>), greater than (>), less than (<), greater than equals to (>=), less than equals to (<=).

3.	Assignment: The operations include:

=    Stores right side operand in left side operand.

+=    Add right side operand to left side operand and store the result in left side operand.

-=     Subtract right side operand from left side operand and store the result in left side operand.

*=     Multiply right side operand with left side operand and store the result in left side operand.

/=      Divide left side operand by right side operand and store the result in left side operand.

%=    Find the modulus and store the remainder in left side operand.

**=    Find the exponential and store the result in left side operand.

//=      Find the floor division and store the result in left side operand. 

4.	Bitwise operations: These include Bitwise AND (&), Bitwise OR (|), Bitwise XOR (^), Bitwise inverse (~), left shift (<<), right shift (>>).

5.	Logical operations: These include logical AND (and), logical OR (or), logical NOT (not). The result and the operands are always Boolean values.

6.	Membership: These include 2 operations : 

in: returns true if item is present in the list or sequence else returns false.

not in: return true if item not present in the list or sequence else returns false.

7.	Identity: These include 2 operations:

is: returns true if the operands are same else returns false.

not is: returns true if the operands are not same else returns false.




#### Control structures (if statements, loops).

The for Loop:
	
 The for loop is an iterator-based for loop. It goes through the elements in any ordered sequence list, i.e. strings, lists, tuples, dictionary, etc. In each iteration a loop variable is set to a value.

Syntax:	

    for x in y:
      block

Example: 	

    for x in range(7):
		print(x)

The while Loop:
	
 The while loop is used when we want to repeat a piece of code ‘n’ number of times or forever. We have to give a conditional statement that will tell the interpreter when the loop will stop.

Syntax:	

    while condition:
      block	

Example: 	

    count=0
    while count<6:
      print count
	  count+=1


The if elif else Statement: 
	
 The if statement is known as the decision making statement. With an if clause a condition is provided. If the condition is True then the block if statement written in the if clause will be executed. 
We can check multiple statements for True with the help of elif statement and execute a block of code written just below the elif statement. There can be any number of elif statements.
An else statement can be combined with an if statement. It contains the block of code that executes if the conditional expression in the if statement and the elif statement/-s resolves to False value. It is an optional statement.

Syntax: 	

    if condition1:
		block1
	elif condition2:
		block2
	else:
		block3



### DAY 4:

#### Lists:
A list is a collection of items or elements; the sequence of data in a list is ordered. The elements or items in a list can be accessed by their positions, i.e., indices.
Lists are mutable. The value of any element inside the list can be changed at any point of time. The elements of the list are accessible with their index value. The index always starts with 0 and ends with n-1, if the list contains n elements.

Traversing a list means accessing all the elements or items of the list. Traversing can be done by using any conditional statement of Python, but it is preferable to use for loop.
		
    list1= [‘a’,’b’,’c’,’d’]
    for x in list:
    print x

Deleting Elements from List:

1.	pop Operator: If we know the index of the element that we want to delete, then we can use the pop operator.

         List1 = [10,20,30,40]
         a = list.pop(2)
         print list
       
        Output: [10,20,40]

  	 2. del Operator: The del operator deletes the value on the provided index, but it does not store the value for further use.

            list = [‘w’,‘x’,’y’,’z’]
            del list(1)
            print list

            Output: [‘w’, ‘y’, ‘z’]

3. remove Operator: We use the remove operator if we know the item that we want to remove or delete from the list (but not the index).

        list = [10,20,30,40]
        list.remove(10)
        print list

        Output: [20,30,40]

append Method can add a new element or item to an existing list.

HackerRank: Started solving challenges on HackerRank.


### DAY 5:

#### Strings:
Strings are created by enclosing various characters within quotes. Python does not distinguish between single quotes and double quotes.

len() is a built-in function in Python. When used with a string, len() returns the length or the number of characters in the string.

A piece or subset of a string is known as slice. Slice operator is applied to a string with the use of square braces ([]). Operator [n:m] will give a substring which consists of letters between n and m indices, including letter at index n but excluding that at m, i.e. letter from nth index to (m-1)th index. Similarly, operator [n:m:s] will give a substring which consists of letters from nth index to (m-1)th index, where s is called the step value, i.e. after letter at n, that at n+s will be included, then n+2s, n+3s, etc.

    var = ‘Hello Python’
    print var[0:4]
    Output: Hell 
    print var[6:12]
    
    Output: Python

    alphabet = “abcdefghij”
    print alphabet[1:8:3]
    Output: beh 
    print alphabet[1:8:2]
    
    Output: bdfh

Strings are immutable which means that we cannot change any element of a string. If we want to change an element of a string, we have to create a new string.

Traversing can be done by using any conditional statement.

HackerRank: Solved challenges of Strings and Lists on HackerRank.


### DAY 6:

#### Functions:
Functions are self-contained programs that perform some particular tasks. Once a function is created by the programmer for a specific task, this function can be called anytime to perform that task. Suppose, we want to perform a task several times, in such a scenario, rather than writing code for that particular task repeatedly, we create a function for that task and call it when we want to perform the task.

Built-in functions are the functions already defined in the Python programming language; we can directly call them to perform a specific task like type conversion, math functions, help function, etc.

User-defined functions:

To use their own functions in Python, users have to define the function first; this is known as Function Definition. In a function definition, users have to define a name for the new function and also the list of the statements that will execute when the function will be called.

The block of the function starts with a keyword def after which the function name is written followed by parentheses. We can also give some input parameters or arguments to a function by placing them within these parentheses. The parameters can also be defined within these parentheses. The block of statements always starts with a colon (:). After writing the code statements, the block is ended with a return statement whose syntax is return [expression].

Syntax:

    def functionname(parameters):
    “function_docstring”
    statement(s)
    return [expression]

Parameters and arguments are the values or expressions passed to the functions between parentheses (()). 

A function is called using the name with which it was defined earlier, followed by a pair of parentheses (()). All parameters (arguments) which are passed in functions are always passed by reference in Python. This means that if the values of the parameters are changed in the function, it will also reflect the change in the calling function.

HackerRank: Solved challenges using functions on HackerRank.



