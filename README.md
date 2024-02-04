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


### DAY 7:

#### Break and Continue Statements:
The break and continue statements are often useful in a while loop as well as in a for loop. The break statement exits from the loop and transfers the execution from the loop to the statement that is immediately following the loop. The continue statement causes execution to immediately continue at the start of the loop, it skips the execution of the remaining body part of the loop.

Example:

	count = 2
	while True:
		print count
		count = count + 2
		if count >= 12:
 			break 				# breaks the loop

Output:

2 

4

6

8

10

Example:

	for i in range(1,10):
	if i % 2 != 0:
 		continue 			# if condition becomes true, it skips the print part
		print i

Output:

2 

4

6

8


#### Recursive Function:
Recursion is the process of repeating something in a self-similar way. In the programming context, the meaning of recursion remains the same. Here, if a function, procedure or method calls itself, it is called recursive.

Example:

	def fact(x):
		if x==1:
			return 1
		else:
			return(x*fact(x-1))
	fact(3)

Output:

6


### DAY 8:

#### Tuples:
Tuples are the sequence or series values of different types separated by commas (,). Just like strings and lists, values in tuples can also be accessed by their index values, which are integers starting from 0.
The main difference between lists and tuples is that tuples are immutable. We cannot edit the elements of a tuple neither can we add new items to it once it is created.

In order to create a tuple, all the items or elements are placed inside parentheses separated by commas and assigned to a variable.


#### Tuple Assignment:
Tuple allows the assignment of values to a tuple of variables on the left side of the assignment from the tuple of values on the right side of the assignment.
The number of variables in the tuple on the left of the assignment must match the number of elements/items in the tuple on the right of the assignment.

Example:

	Anil = (‘221’,’Anil’,’Rahul’,’Delhi’,1971,’Jaipur Gwalior’)
	(id,fst_name,lst_name,city,year_of_birth,birth_place) = Anil
	print id
	print fst_name

Output:

221

John


### DAY 9:

#### Dictionaries:
Dictionary is an unordered collection of items or elements. All other compound data types in Python have only values as their elements or items whereas the dictionary has a key: value pair. Each value is associated with a key. Keys can be of any data type.

To create a dictionary the key and its value are separated by a colon (:) between them. The items or elements in a dictionary are separated by commas and all the elements must be enclosed in curly braces. The values in a dictionary can be duplicated, but the keys in the dictionary are unique.

In order to access the elements from a dictionary, we can use the value of the key enclosed in square brackets. Python also provides a get() method that is used with the key in order to access the value. There is a difference in both the accessing methods.

Example:

	dict1 = {‘name’ : ‘John’, ‘age’ : 27}
	dict1[‘name’]

Output:

‘John’

Dictionaries in Python are mutable. The values in a dictionary can be changed, added or deleted. If the key is present in the dictionary, then the associated value with that key is updated or changed; otherwise a new key: value pair is added.

Example:

	dict1 = {‘name’ : ‘John’, ‘age’ : 27}
	dict1[‘age’] = 30 # updating a value
	print dict1
	dict1[‘address’] = ‘Alaska’ # adding a key: value
	print dict1

Output:

{‘age’: 30, ‘name’: ‘John’} 

{‘age’: 30, ‘name’: ‘John’, ‘address’: ‘Alaska’}

The items or elements from a dictionary can be removed or deleted by using pop()method. pop()method removes that item from the dictionary for which the key is provided. It also returns the value of the item. 

Furthermore, there is a popitem()method in Python. popitem()method is used to remove or delete and return an arbitrary item from the dictionary.

The clear() method removes all the items or elements from a dictionary at once. When this operation is performed, the dictionary becomes an empty dictionary.

Python also provides a del keyword, which deletes the dictionary itself. When this operation is performed, the dictionary is deleted from the memory and it ceases to exist.


### DAY 10:

#### Sets:
In Python there is one data type which is an unordered collection of data known as Set. A Set does not contain any duplicate values or elements.

Union, Intersection, Difference and Symmetric Difference are some operations which are performed on sets.

Union:

Union operation performed on two sets returns all the elements from both the sets. It is performed by using & operator.

Intersection: 

Intersection operation performed on two sets returns all the element which are common or in both the sets. It is performed by using | operator.

Difference: 

Difference operation performed on two sets set1 and set2 returns the elements which are present on set1 but not in set2. It is performed by using – operator.

Symmetric Difference: 

Symmetric Difference operation performed on two sets returns the element which are present in either set1 or set2 but not in both. It is performed by using ^ operator.

Example:

	set1 = set([1, 2, 4, 1, 2, 8, 5, 4])
	set2 = set([1, 9, 3, 2, 5])
	intersection = set1 & set2
	union = set1 | set2
	difference = set1 - set2
	symm_diff = set1 ^ set2
	print(intersection)
	print(union)
	print(difference)
	print(symm_diff)

Output:

set([1, 2, 5])

set([1, 2, 3, 4, 5, 8, 9])

set([8, 4])

set([3, 4, 8, 9])


HackerRank: Solved challenges using functions on HackerRank.


### DAY 11:

#### Modules:
Modules are simply files with the “.py” extension containing Python code that can be imported inside another Python Program. In simple terms, we can consider a module to be the same as a code library or a file that contains a set of functions that we want to include in your application.

The module contains the following components:
•	Definitions and implementation of classes,
•	Variables
•	Functions that can be used inside another program.

To create a module, we have to save the code that we wish in a file with the file extension “.py”. Then, the name of the Python file becomes the name of the module.

Example:

A function is created with the name “welcome” and save this file with the name mymodule.py i.e. name of the file, and with the extension “.py”.
We saved the following code in a file named mymodule.py

	def welcome(name):
  		print("Hello, " + name+,” !”)

To incorporate the module into our program, we will use the import keyword, and to get only a few or specific methods or functions from a module, we use the from keyword.

	import mymodule
	mymodule.welcome("Titli Ghoshl")

Output:

Hello, Titli Ghosh !

HackerRank: Solved challenges using functions on HackerRank.





