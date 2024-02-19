# DailyLearnings_in_PYTHON_and_AIML-

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


### DAY 12:

Numpy is a general-purpose array-processing package. It provides a high-performance multidimensional array object and tools for working with these arrays. The array object in NumPy is called ndarray, it provides a lot of supporting functions that make working with ndarray very easy.

Arrays are very frequently used in data science, where speed and resources are very important.

NumPy arrays are stored at one continuous place in memory unlike lists, so processes can access and manipulate them very efficiently.
This behavior is called locality of reference in computer science.
This is the main reason why NumPy is faster than lists. 

#### Installation :

In the terminal of the computer, writing the following command to install NumPy:

	pip install numpy

Once NumPy is installed, import it in your applications by adding the import keyword:

	import numpy as np


Creating array:

We can create a NumPy ndarray object by using the array() function: 

	import numpy as np
	arr = np.array([1, 2, 3, 4, 5])
	print(arr)

Output:

[1  2  3  4  5]

#### 2-D Arrays:

An array that has 1-D arrays as its elements is called a 2-D array.
These are often used to represent matrix or 2nd order tensors.
import numpy as np

	arr = np.array([[1, 2, 3], [4, 5, 6]])
	print(arr)

Output:

[ [1  2  3]

  [4  5  6] ]


Array indexing is the same as accessing an array element.
You can access an array element by referring to its index number.
The indexes in NumPy arrays start with 0, meaning that the first element has index 0, and the second has index 1 etc.

To access elements from 2-D arrays we can use comma separated integers representing the dimension and the index of the element.
Think of 2-D arrays like a table with rows and columns, where the dimension represents the row and the index represents the column.

Use negative indexing to access an array from the end.

NumPy has some extra data types, and refer to data types with one character, like i for integers, u for unsigned integers etc.
Below is a list of all data types in NumPy and the characters used to represent them.
•	i - integer

•	b - boolean

•	u - unsigned integer

•	f - float

•	c - complex float

•	m - timedelta

•	M - datetime

•	O - object

•	S - string

•	U - unicode string

•	V - fixed chunk of memory for other type ( void )

The NumPy array object has a property called dtype that returns the data type of the array:

	import numpy as np
	arr = np.array([1, 2, 3, 4])
	print(arr.dtype)

Output: int64

We use the array() function to create arrays, this function can take an optional argument: dtype that allows us to define the expected data type of the array elements:

	import numpy as np
	arr = np.array([1, 2, 3, 4], dtype='S')
	print(arr)
	print(arr.dtype)

Output:

[b'1' b'2' b'3' b'4']

|S1

The main difference between a copy and a view of an array is that the copy is a new array, and the view is just a view of the original array.

The copy owns the data and any changes made to the copy will not affect original array, and any changes made to the original array will not affect the copy.

The view does not own the data and any changes made to the view will affect the original array, and any changes made to the original array will affect the view.

	import numpy as np
 
	arr = np.array([1, 2, 3, 4, 5])
	x = arr.copy()
	y = arr.view()
	arr[0] = 42
	
	print(arr)
	print(x)
	print(y)

Output:

[42  2  3  4  5]

[1 2 3 4 5]

[42  2  3  4  5]

NumPy arrays have an attribute called shape that returns a tuple with each index having the number of corresponding elements.

	import numpy as np
	
	arr = np.array([[1, 2, 3, 4], [5, 6, 7, 8]])
	print(arr.shape)

Output:
(2, 4)

### Solving HackerRank Problems:

#### Q.1)You are given a NxM integer array matrix with space separated elements (N = rows and M = columns).Your task is to print the transpose and flatten results.

	import numpy as np
	
	arr1=list(map(int,input().split()))
	
	arr2=[]
	for i in range(arr1[0]):
	    arr3=list(map(int,input().split()))
	    arr2.append(arr3)
	
	nparray=np.array(arr2)
	print(np.transpose(nparray))
	print(nparray.flatten())

 ![image](https://github.com/titli17/DailyLearnings_in_PYTHON_and_AIML-/assets/96014974/bdf748f0-21f1-49f2-9c0b-0057a801b0cd)

 
#### Q.2)You are given two integer arrays of size NxP and MxP ( N&M  are rows,and P is the column). Your task is to concatenate the arrays along axis 0.

	import numpy as np
	
	list1=list(map(int,input().split()))
	
	arr1=[]
	arr2=[]
	for i in range(list1[0]):
	    arr3=list(map(int,input().split()))
	    arr1.append(arr3)
	    
	for i in range(list1[1]):
	    arr3=list(map(int,input().split()))
	    arr2.append(arr3)
	    
	array1=np.array(arr1)
	array2=np.array(arr2)
	
	print(np.concatenate((array1,array2),axis=0))

 ![image](https://github.com/titli17/DailyLearnings_in_PYTHON_and_AIML-/assets/96014974/bf46ec55-e10d-4e65-a191-90198b32e166)



### DAY 13:

#### Commonly used arithmetic operations in NumPy:

Addition------	+	add()

Subtraction------	-	subtract()

Multiplication------	*	multiply()

Division------	/	divide()

Exponentiation------	**	power()

Modulus------		%	mod()


	import numpy as np
	
	first_array = np.array([1, 3, 5, 7])
	second_array = np.array([2, 4, 6, 8])
	
	result1 = first_array + second_array
	print("Using the + operator:",result1) 
	
	result2 = np.add(first_array, second_array)
	print("Using the add() function:",result2)

Output:

Using the + operator: [ 3  7 11 15]

Using the add() function: [ 3  7 11 15]

#### Some of the most commonly used functions in NumPy:

Array Creation Functions------>		np.array(), np.zeros(), np.ones(), np.empty(), etc.

Array Manipulation Functions------>		np.reshape(), np.transpose(), etc.

Array Mathematical Functions------>		np.add(), np.subtract(), np.sqrt(), np.power(), etc.

Array Statistical Functions------>		np.median(), np.mean(), np.std(), and np.var().

Array Input and Output Functions------>	np.save(), np.load(), np.loadtxt(), etc.

#### Reshaping Arrays:

Reshaping means changing the shape of an array.
The shape of an array is the number of elements in each dimension.
By reshaping we can add or remove dimensions or change number of elements in each dimension.

	import numpy as np
	
	arr = np.array([1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12])
	newarr = arr.reshape(4, 3)
	print(newarr)

Output:

[[ 1  2  3]

 [ 4  5  6]
 
 [ 7  8  9]
 
 [10 11 12]]

Flattening array means converting a multidimensional array into a 1D array.
We can use reshape(-1) to do this.

	import numpy as np
	
	arr = np.array([[1, 2, 3], [4, 5, 6]])
	newarr = arr.reshape(-1)
	print(newarr)

Output:

[1  2  3  4  5  6]


#### Iterating Arrays:

Iterating means going through elements one by one.
As we deal with multi-dimensional arrays in numpy, we can do this using basic for loop of python.

import numpy as np

	arr = np.array([[1, 2, 3], [4, 5, 6]])
	for x in arr:
		print(x)
  
Output:

[1 2 3]

[4 5 6]


To return the actual values, the scalars, we have to iterate the arrays in each dimension.

import numpy as np

	arr = np.array([[1, 2, 3], [4, 5, 6]])
	for x in arr:
		for y in x:
			print(y)

Output:

1

2

3

4

5

6

#### Enumerated Iteration:

Enumeration means mentioning sequence number of somethings one by one.
Sometimes we require corresponding index of the element while iterating, the ndenumerate() method can be used for those usecases.

import numpy as np

	arr = np.array([1, 2, 3])
	for idx, x in np.ndenumerate(arr):
		print(idx, x)

Output:

(0,) 1

(1,) 2

(2,) 3

#### Joining NumPy Arrays:

Joining means putting contents of two or more arrays in a single array.

	import numpy as np

	arr1 = np.array([1, 2, 3])
	arr2 = np.array([4, 5, 6])
	arr = np.concatenate((arr1, arr2))
	print(arr)

Output:

[1  2  3  4  5  6]


	import numpy as np
	
	arr1 = np.array([[1, 2], [3, 4]])
	arr2 = np.array([[5, 6], [7, 8]])
	arr = np.concatenate((arr1, arr2), axis=1)
	print(arr)

Output:

[[1 2 5 6]

 [3 4 7 8]]

### Solving HackerRank Problems:

#### Q.1)You are given two integer arrays,  and  of dimensions X.Your task is to perform the following operations:

Add (A + B)

Subtract (A - B)

Multiply (A * B)

Integer Division (A / B)

Mod (A % B)

Power (A ** B)

	import numpy as np
	
	list1=list(map(int,input().split()))
	l1=[]
	for i in range(list1[0]):
	    list2=list(map(int,input().split()))
	    l1.append(list2)
	    
	l2=[]
	for i in range(list1[0]):
	    list3=list(map(int,input().split()))
	    l2.append(list3)
	
	A=np.array(l1)
	B=np.array(l2)
	
	print(A+B)
	print(A-B)
	print(A*B)
	print(np.floor_divide(A,B))
	print(A%B)
	print(A**B)
	
![image](https://github.com/titli17/DailyLearnings_in_PYTHON_and_AIML-/assets/96014974/b496ef46-8050-4208-8137-233202dc92a4)

#### Q.2)You are given two arrays A and B. Both have dimensions of NxN.Your task is to compute their matrix product.

	import numpy as np
	
	l=int(input())
	
	l1=[]
	l2=[]
	
	for i in range(l):
	    arr=list(map(int,input().split()))
	    l1.append(arr)
	    
	for i in range(l):
	    arr=list(map(int,input().split()))
	    l2.append(arr)
	    
	A=np.array(l1)
	B=np.array(l2)
	
	print(np.dot(A,B))

![image](https://github.com/titli17/DailyLearnings_in_PYTHON_and_AIML-/assets/96014974/2b78c239-df1d-45ce-bafd-9117cbd83995)


### DAY 14:

#### TREES:

A tree is a nonlinear hierarchical data structure that consists of nodes connected by edges.

#### Terminologies:

The first node in a tree is called the root node.

A link connecting one node to another is called an edge.

A parent node has links to its child nodes. Another word for a parent node is internal node.

A node can have zero, one, or many child nodes.

A node can only have one parent node.

Nodes without links to other child nodes are called leaves, or leaf nodes.

The tree height is the maximum number of edges from the root node to a leaf node. The height of the tree above is 2.

The height of a node is the maximum number of edges between the node and a leaf node.

The tree size is the number of nodes in the tree.


#### BINARY TREES:

It is either empty or has finite collection of elements. It has atmost 2 subtrees. The subtrees of each element are ordered.

Types of Binary Trees:

A balanced Binary Tree has at most 1 in difference between its left and right subtree heights, for each node in the tree.

A complete Binary Tree has all levels full of nodes, except the last level, which is can also be full, or filled from left to right. The properties of a complete Binary Tree means it is also balanced.

A full Binary Tree is a kind of tree where each node has either 0 or 2 child nodes.

A perfect Binary Tree has all leaf nodes on the same level, which means that all levels are full of nodes, and all internal nodes have two child nodes.The properties of a perfect Binary Tree means it is also full, balanced, and complete.


Traversal:

Breadth First Search (BFS) is when the nodes on the same level are visited before going to the next level in the tree. This means that the tree is explored in a more sideways direction.

Depth First Search (DFS) is when the traversal moves down the tree all the way to the leaf nodes, exploring the tree branch by branch in a downwards direction.

There are three different types of DFS traversals:

##### 1.pre-order:

Process the root.

Traverse the left sub tree of root in pre-order

Traverse the right sub tree of root in pre-order


##### 2.in-order:

Traverse the left sub tree of root in pre-order

Process the root

Traverse the right sub tree of root in pre-order


##### 3.post-order:

Traverse the left sub tree of root in pre-order

Traverse the right sub tree of root in pre-order

Process the root


![image](https://github.com/titli17/DailyLearnings_in_PYTHON_and_AIML-/assets/96014974/a2101d16-c588-40a8-921a-80fe9004bd7a)

For this tree 

Pre-order traversal: R,A,C,D,B,E,F,G

In-order traversal: C,A,D,R,E,B,G,F

Post-order traversal: C,D,A,E,G,F,B,R


#### BINARY SEARCH TREES:

A Binary Search Tree is a Binary Tree where every node's left child has a lower value, and every node's right child has a higher value. No 2 elements have the same key.

A clear advantage with Binary Search Trees is that operations like search, delete, and insert are fast and done without having to shift values in memory.


#### AVL TREES:

AVL trees are self-balancing, which means that the tree height is kept to a minimum so that a very fast runtime is guaranteed for searching, inserting and deleting nodes, with time complexity 
O(logn). It was introduced by Adelson-Velskii and Landis.

If T is a non-empty binary tree with Tl and Tr as its left and right sub tree, then T is an AVL tree iff:

1. |hl-hr|<=1, where hl and hr are the heights of Tl and Tr

2. Tl and Tr are also AVL trees.


The node in AVL tree has an additional field bf(balance factor).   

bf = hl-hr

bf = -1 for hl<hr

   = 0  for hl=hr

   = +1 for hl>hr


To restore balance in an AVL Tree, left or right rotations are done, or a combination of left and right rotations.


Left-Left (LL)	

The unbalanced node and its left child node are both left-heavy.	A single right rotation is required.


Right-Right (RR)	

The unbalanced node and its right child node are both right-heavy.	A single left rotation is required.


Left-Right (LR)	

The unbalanced node is left heavy, and its left child node is right heavy.	First do a left rotation on the left child node, then do a right rotation on the unbalanced node.


Right-Left (RL)	

The unbalanced node is right heavy, and its right child node is left heavy.	First do a right rotation on the right child node, then do a left rotation on the unbalanced node.


#### B-Trees:

B-Tree is known as a self-balancing tree as its nodes are sorted in the inorder traversal. In B-tree, a node can have more than two children. B-tree has a height of logM N (Where ‘M’ is the order of tree and N is the number of nodes). And the height is adjusted automatically at each update. In the B-tree data is sorted in a specific order, with the lowest value on the left and the highest value on the right. To insert the data or key in B-tree is more complicated than a binary tree. Some conditions must be held by the B-Tree:

1.All the leaf nodes of the B-tree must be at the same level.

2.Above the leaf nodes of the B-tree, there should be no empty sub-trees.

3.B- tree’s height should lie as low as possible.


#### B+ Trees:

B+ tree eliminates the drawback B-tree used for indexing by storing data pointers only at the leaf nodes of the tree. Thus, the structure of leaf nodes of a B+ tree is quite different from the structure of internal nodes of the B tree. It may be noted here that, since data pointers are present only at the leaf nodes, the leaf nodes must necessarily store all the key values along with their corresponding data pointers to the disk file block, to access them. Moreover, the leaf nodes are linked to providing ordered access to the records. The leaf nodes, therefore form the first level of the index, with the internal nodes forming the other levels of a multilevel index. Some of the key values of the leaf nodes also appear in the internal nodes, to simply act as a medium to control the searching of a record.

#### B-Trees vs B+ Trees:

![image](https://github.com/titli17/DailyLearnings_in_PYTHON_and_AIML-/assets/96014974/76a3fded-0e8c-4fd2-97f6-17807608e502)


Top questions from Tree:

1.Maximum Depth of Binary Tree

2.Check if two trees have same structure

3.Invert/Flip Binary Tree

4.Binary Tree Maximum Path Sum

5.Binary Tree Level Order Traversal

6.Serialize and Deserialize Binary Tree

7.Subtree of Another Tree

8.Construct Binary Tree from Preorder and Inorder Traversal

9.Validate Binary Search Tree

10.Kth Smallest Element in a BST

11.Lowest Common Ancestor of BST

12.Implement Trie (Prefix Tree)

13.Add and Search Word


### DAY 15:

#### General Tree:

#### Creating the Root Node and adding children:

	class TreeNode:
	    def __init__(self, data):
	        self.data = data
	        self.children = []
	
	    def add_child(self, child_node):
	        self.children.append(child_node)
	
	root = TreeNode("Root")
	child1 = TreeNode("Child 1")
	child2 = TreeNode("Child 2")
	
	root.add_child(child1)
	root.add_child(child2)

 The python __init__ method is declared within a class and is used to initialize the attributes of an object as soon as the object is formed. While giving the definition for an __init__(self) method, a default parameter, named ‘self’ is always passed in its argument. This self represents the object of the class itself.
 

 #### Traversal Techniques:

 ##### 1.Breadth First Search (BFS):

	 class TreeNode:
	    def __init__(self, data):
	        self.data = data
	        self.children = []
	
	    def add_child(self, child_node):
	        self.children.append(child_node)
	
	def bfs(root):
	    if root is None:
	        return []
	
	    result = []
	    queue = [root]
	
	    while queue:
	        current_node = queue.pop(0)
	        result.append(current_node.data)
	        for child in current_node.children:
	            queue.append(child)
	
	    return result
	
	# Example usage:
	A=TreeNode("A")
	B=TreeNode("B")
	C=TreeNode("C")
	D=TreeNode("D")
	E=TreeNode("E")
	
	A.add_child(B)
	A.add_child(C)
	B.add_child(D)
	C.add_child(E)
	
	print(bfs(A))

 ##### 2. Depth First Search (DFS):

	 class TreeNode:
	    def __init__(self, data):
	        self.data = data
	        self.children = []
	
	    def add_child(self, child_node):
	        self.children.append(child_node)
	
	def dfs(root):
	    if root is None:
	        return []
	
	    result = []
	
	    def dfs_helper(node):
	        if node is None:
	            return
	        result.append(node.data)
	        for child in node.children:
	            dfs_helper(child)
	
	    dfs_helper(root)
	    return result
	
	# Example usage:
	A=TreeNode("A")
	B=TreeNode("B")
	C=TreeNode("C")
	D=TreeNode("D")
	E=TreeNode("E")
	
	A.add_child(B)
	A.add_child(C)
	B.add_child(D)
	C.add_child(E)
	
	print (dfs(A))

#### Binary Trees:

##### Creating the Root Node and inserting Nodes:

	class TreeNode:
	    def __init__(self, data):
	        self.data = data
	        self.left = None
	        self.right = None  
	
	# Example usage:
	A=TreeNode("22")
	B=TreeNode("12")
	C=TreeNode("30")
	D=TreeNode("8")
	E=TreeNode("20")
	F=TreeNode("25")
	G=TreeNode("40")
	
	
	A.left=B
	A.right=C
	B.left=D
	B.right=E
	C.left=F
	C.right=G


##### Traversals:

##### 1. In-order traversal:

	class TreeNode:
	    def __init__(self, data):
	        self.data = data
	        self.left = None
	        self.right = None
	
	def inorder_traversal(root):
	    result = []
	    if root:
	        result = inorder_traversal(root.left)
	        result.append(root.data)
	        result += inorder_traversal(root.right)
	    return result
	    
	
	# Example usage:
	A=TreeNode("22")
	B=TreeNode("12")
	C=TreeNode("30")
	D=TreeNode("8")
	E=TreeNode("20")
	F=TreeNode("25")
	G=TreeNode("40")
	
	
	A.left=B
	A.right=C
	B.left=D
	B.right=E
	C.left=F
	C.right=G
	
	print(inorder_traversal(A))


Output:

['8', '12', '20', '22', '25', '30', '40']


##### 2. Pre-order traversal:

	class TreeNode:
	    def __init__(self, data):
	        self.data = data
	        self.left = None
	        self.right = None
	
	def preorder_traversal(root):
	    result = []
	    if root:
	        result.append(root.data)
	        result += preorder_traversal(root.left)
	        result += preorder_traversal(root.right)
	    return result
	    
	
	# Example usage:
	A=TreeNode("22")
	B=TreeNode("12")
	C=TreeNode("30")
	D=TreeNode("8")
	E=TreeNode("20")
	F=TreeNode("25")
	G=TreeNode("40")
	
	
	A.left=B
	A.right=C
	B.left=D
	B.right=E
	C.left=F
	C.right=G
	
	print(preorder_traversal(A))

 Output:

['22', '12', '8', '20', '30', '25', '40']


##### 3. Post-order traversal:

	class TreeNode:
	    def __init__(self, data):
	        self.data = data
	        self.left = None
	        self.right = None
	
	def postorder_traversal(root):
	    result = []
	    if root:
	        result += postorder_traversal(root.left)
	        result += postorder_traversal(root.right)
	        result.append(root.data)
	    return result
	    
	
	# Example usage:
	A=TreeNode("22")
	B=TreeNode("12")
	C=TreeNode("30")
	D=TreeNode("8")
	E=TreeNode("20")
	F=TreeNode("25")
	G=TreeNode("40")
	
	
	A.left=B
	A.right=C
	B.left=D
	B.right=E
	C.left=F
	C.right=G
	
	print(postorder_traversal(A))
	
Output:

['8', '20', '12', '25', '40', '30', '22']



#### Binary Search Trees:

##### Creating the Root Node and inserting Nodes:

	class TreeNode:
	    def __init__(self, data):
	        self.data = data
	        self.left = None
	        self.right = None
	
	
	def insert(root,x):
	    if root is None:
	        return (TreeNode(x))
	    else:
	        if(root.data<x):
	            root.right=insert(root.right,x)
	        else:
	            root.left=insert(root.left,x)
	    return root
	
	def postorder_traversal(root):
	    result = []
	    if root:
	        result += postorder_traversal(root.left)
	        result += postorder_traversal(root.right)
	        result.append(root.data)
	    return result
	    
	
	# Example usage:
	A=TreeNode(100)
	
	A=insert(A,20)
	A=insert(A,200)
	A=insert(A,10)
	A=insert(A,30)
	A=insert(A,150)
	A=insert(A,300)
	
	print(postorder_traversal(A))

 Output:

[10, 30, 20, 150, 300, 200, 100]


##### Deleting Nodes:

To delete a node from a binary search tree (BST) in Python, you need to consider different cases:

1.If the node to be deleted is a leaf node (no children), simply remove it from its parent.

2.If the node to be deleted has only one child, replace the node with its child.

3.If the node to be deleted has two children, find the inorder successor (or predecessor), copy its data to the node to be deleted, and then delete the inorder successor (or predecessor).



 ### DAY 16:

 #### Top 50 DSA questions on Arrays:


1.Find a peak element which is not smaller than its neighbours.
	
	'''Given an array arr of n elements that is first strictly increasing and then
	maybe strictly decreasing, find the maximum element in the array.
	
	Note: If the array is increasing then just print the last element will be the
	maximum value.
	
	Example:
	
	Input: array[]= {5, 10, 20, 15}
	Output: 20
	Explanation: The element 20 has neighbors 10 and 15, both of them are less
	than 20.'''
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(n):
	    a=int(input())
	    arr.append(a)
	print("Array :",arr)
	
	for i in range(0,n-1):
	    for j in range(i+1,n):
	        if(arr[i]>arr[j]):
	            a=arr[i]
	            arr[i]=arr[j]
	            arr[j]=a
	
	print("Peak element :",arr[n-1])


2.Find the minimum (or maximum) element of an array.

	'''Given an array, write functions to find the minimum and maximum elements in it. 
	
	The most simplest way to find min and max value of an element is to use
	inbuilt function sort(). So, that value at 0th position will min and
	value at nth position will be max.
	
	Example: [12, 1234, 45, 67, 1]
	
	Minimum element of array: 1
	Maximum element of array: 1234'''
	
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(n):
	    a=int(input())
	    arr.append(a)
	print("Array :",arr)
	
	
	max=min=arr[0]
	for i in range(n):
	    if(arr[i]>max):
	        max=arr[i]
	    if(arr[i]<min):
	        min=arr[i]
	
	print("Max element :",max,"\nMin element :",min)


3.K’th Smallest/Largest Element in Unsorted Array.

	'''Given an array arr[] of size N and a number K, where K is smaller than the
	size of the array. Find the K’th smallest element in the given array. Given
	that all array elements are distinct.
	
	Examples:  
	
	Input: arr[] = {7, 10, 4, 3, 20, 15}, K = 3 
	Output: 7
	
	Input: arr[] = {7, 10, 4, 3, 20, 15}, K = 4 
	Output: 10 '''
	
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(n):
	    a=int(input())
	    arr.append(a)
	print("Array :",arr)
	
	k=int(input("Enter the value of K :"))
	
	for i in range(0,n-1):
	    for j in range(i+1,n):
	        if(arr[i]>arr[j]):
	            a=arr[i]
	            arr[i]=arr[j]
	            arr[j]=a
	
	print("Kth smallest element :",arr[k-1])
	print("Kth largest element :",arr[n-k])
	

4.Array Reverse.

	'''Example:
	
	Input: original_array[] = {1, 2, 3}
	Output: array_reversed[] = {3, 2, 1}'''
	
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(n):
	    a=int(input())
	    arr.append(a)
	
	print("Array :",arr)
	
	arr2=[]
	for i in range(n):
	    arr2.append(arr[-i-1])
	
	print("Reversed array :",arr2)


5.Sorting an array.

	 def merge_sort(arr):
	    if (len(arr)>1):
	        mid=len(arr)//2      
	        l=arr[:mid]
	        r=arr[mid:]
	        merge_sort(l)
	        merge_sort(r)
	 
	        i=0
	        j=0
	        k=0
	        
	        while ((i<len(l))and(j<len(r))):
	            if (l[i]<=r[j]):
	                arr[k]=l[i]
	                i+=1
	            else:
	                arr[k]=r[j]
	                j+=1
	            k+=1
	 
	        while (i<len(l)):
	            arr[k]=l[i]
	            i+=1
	            k+=1
	 
	        while (j<len(r)):
	            arr[k]=r[j]
	            j+=1
	            k+=1
	 
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(0,n):
	    a=int(input())
	    arr.append(a)
	print("Array :",arr)
	merge_sort(arr)
	print("Sorted Array :",arr) 


6.Count number of occurrences (or frequency) in a sorted array.

	'''Given a sorted array arr[] and a number x, write a function that counts the
	occurrences of x in arr[].
	
	Example:
	  Input: arr[] = {1, 1, 2, 2, 2, 2, 3,},   x = 2
	  Output: 4
	  
	  Input: arr[] = {1, 1, 2, 2, 2, 2, 3,},   x = 3
	  Output: 1
	  
	  Input: arr[] = {1, 1, 2, 2, 2, 2, 3,},   x = 1
	  Output: 2
	  
	  Input: arr[] = {1, 1, 2, 2, 2, 2, 3,},   x = 4
	  Output: -1 // 4 doesn't occur in arr[] '''
	
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements in sorted manner :")
	for i in range(n):
	    a=int(input())
	    arr.append(a)
	
	print("Array :",arr)
	
	x=int(input("Enter the value of x :"))
	
	count=0
	for i in range(n):
	    if(arr[i]==x):
	        count+=1
	    if(arr[i]>x):
	        break
	
	print("Number of occurences :",count)
	    

7.Sort an array of 0s, 1s and 2s | Dutch National Flag problem.

	'''Given an array A[] consisting of only 0s, 1s, and 2s. The task is to write a
	function that sorts the given array. The functions should put all 0s first,
	then all 1s and all 2s in last.
	
	This problem is also the same as the famous “Dutch National Flag problem”.
	
	Input: {0, 1, 2, 0, 1, 2}
	Output: {0, 0, 1, 1, 2, 2}
	
	Input: {0, 1, 1, 0, 1, 2, 1, 2, 0, 0, 0, 1}
	Output: {0, 0, 0, 0, 0, 1, 1, 1, 1, 1, 2, 2}'''
	
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(n):
	    a=int(input())
	    arr.append(a)
	print("Array :",arr)
	
	c0=c1=c2=0
	
	for i in range(n):
	    if(arr[i]==0):
	        c0+=1
	    elif(arr[i]==1):
	        c1+=1
	    else:
	        c2+=1
	
	arr1=[]
	for i in range(c0):
	    arr1.append(0)
	for i in range(c1):
	    arr1.append(1)
	for i in range(c2):
	    arr1.append(2)
	
	print("Sorted Array :",arr1)


 ### DAY 17:

 #### Top 50 DSA questions on Arrays continued:

 8.Find Subarray with given sum.

	'''Given an array arr[] of non-negative integers and an integer sum, find a
	subarray that adds to a given sum.
	
	Note: There may be more than one subarray with sum as the given sum, print
	first such subarray. 
	
	Examples: 
	
	Input: arr[] = {1, 4, 20, 3, 10, 5}, sum = 33
	Output: Sum found between indexes 2 and 4
	Explanation: Sum of elements between indices 2 and 4 is 20 + 3 + 10 = 33'''
	
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(n):
	    a=int(input())
	    arr.append(a)
	print("Array :",arr)
	
	s=int(input("Enter the sum :"))
	
	p=0
	for i in range(0,n):
	    su=s-arr[i]
	    p=i
	    if(su!=0):
	        for j in range(i+1,n):
	            if(arr[j]<su):
	                su-=arr[j]
	            elif(arr[j]==su):
	                p=j
	                su-=su
	                break
	            else:
	                break
	    if(su==0):
	        break
	if(i==n-1 and p==n-1 and arr[i]!=s):
	    print("There is no subarray with sum",s)
	else:
	    print("Subarray with given sum :",arr[i:p+1])


 9.Move all negative numbers to beginning and positive to end with constant extra space.

	'''An array contains both positive and negative numbers in random order.
	Rearrange the array elements so that all negative numbers appear before all
	positive numbers.
	
	Examples : 
	
	Input: -12, 11, -13, -5, 6, -7, 5, -3, -6
	Output: -12 -13 -5 -7 -3 -6 11 6 5
	
	'''
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(n):
	    a=int(input())
	    arr.append(a)
	print("Array :",arr)
	
	arr1=[]
	for i in range(n):
	    if(arr[i]<0):
	        arr1.append(arr[i])
	
	for i in range(n):
	    if(arr[i]>=0):
	        arr1.append(arr[i])
	
	print("New array :",arr1)

 10.Union and Intersection of two sorted arrays.

	 '''Given two sorted arrays, find their union and intersection.
	
	Example:
	
	Input: arr1[] = {1, 3, 4, 5, 7}
	        arr2[] = {2, 3, 5, 6} 
	Output: Union : {1, 2, 3, 4, 5, 6, 7} 
	         Intersection : {3, 5}
	
	Input: arr1[] = {2, 5, 6}
	        arr2[] = {4, 6, 8, 10} 
	Output: Union : {2, 4, 5, 6, 8, 10} 
	         Intersection : {6}
	
	'''
	
	def sort(arr,n):
	    for i in range(0,n-1):
	        for j in range(i+1,n):
	            if(arr[i]>arr[j]):
	                a=arr[i]
	                arr[i]=arr[j]
	                arr[j]=a
	    return arr3
	            
	def rem_dupli(arr,n):
	    arr1=[]
	    for i in range(0,n-1):
	        for j in range(i+1,n):
	            if(arr[i]==arr[j]):
	                arr1.append(arr[j])
	                arr.pop(j)
	                n-=1
	            else:
	                break
	    return (arr,arr1)
	
	n1=int(input("Enter the number of elements for 1st array :"))
	arr1=[]
	print("Enter the elements :")
	for i in range(0,n1):
	    a=int(input())
	    arr1.append(a)
	
	n2=int(input("Enter the number of elements for 2nd array :"))
	arr2=[]
	print("Enter the elements :")
	for i in range(0,n2):
	    a=int(input())
	    arr2.append(a)
	
	print("Array 1 :",arr1)
	print("Array 2 :",arr2)
	
	
	arr3=[]
	for i in range(0,n1):
	    arr3.append(arr1[i])
	for i in range(0,n2):
	    arr3.append(arr2[i])
	
	arr4=[]
	
	arr3=sort(arr3,n1+n2)
	arr3,arr4=rem_dupli(arr3,n1+n2)
	
	print("Union :",arr3)
	
	print("Intersection :",arr4)
	
	
11.Program to cyclically rotate an array by one.

	'''Given an array, the task is to cyclically rotate the array clockwise by one
	time. 
	
	Examples:  
	
	Input: arr[] = {1, 2, 3, 4, 5}
	Output: arr[] = {5, 1, 2, 3, 4}
	
	Input: arr[] = {2, 3, 4, 5, 1}
	Output: {1, 2, 3, 4, 5}
	
	'''
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(n):
	    a=int(input())
	    arr.append(a)
	
	arr1=[]
	arr1.append(arr[n-1])
	for i in range(0,n-1):
	    arr1.append(arr[i])
	print("New Array :",arr1)


12.Find the Missing Number.

	'''Given an array arr[] of size N-1 with integers in the range of [1, N], the
	task is to find the missing number from the first N integers.
	
	Note: There are no duplicates in the list.
	
	Examples: 
	
	Input: arr[] = {1, 2, 4, 6, 3, 7, 8}
	Output: 5
	Explanation: Here the size of the array is 7, so the range will be [1, 8].
	The missing number between 1 to 8 is 5.
	'''
	
	def sort(arr,n):
	    for i in range(0,n-1):
	        for j in range(i+1,n):
	            if(arr[i]>arr[j]):
	                a=arr[i]
	                arr[i]=arr[j]
	                arr[j]=a
	    return arr
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(n):
	    a=int(input())
	    arr.append(a)
	print("Array :",arr)
	
	arr=sort(arr,n)
	
	flag=0
	for i in range(0,n):
	    if(arr[i]==i+1):
	        flag=1
	        continue
	    else:
	        flag=0
	        break
	if(flag==0):
	    print("Missing number :",i+1)
	else:
	    print("Missing number :",i+2)
	
	
		
13.Count pairs with given sum.

	'''Given an array of N integers, and an integer K, the task is to find the
	number of pairs of integers in the array whose sum is equal to K.
	
	Examples:  
	
	Input: arr[] = {1, 5, 7, -1}, K = 6
	Output:  2
	Explanation: Pairs with sum 6 are (1, 5) and (7, -1).
	
	Input: arr[] = {1, 5, 7, -1, 5}, K = 6
	Output:  3
	Explanation: Pairs with sum 6 are (1, 5), (7, -1) & (1, 5).     
	
	'''
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(n):
	    a=int(input())
	    arr.append(a)
	
	print("Array :",arr)
	
	k=int(input("Enter the value of K :"))
	
	count=0
	arr3=[]
	for i in range(0,n-1):
	    for j in range(i+1,n):
	        if(arr[i]+arr[j]==k):
	            arr2=[]
	            arr2.append(arr[i])
	            arr2.append(arr[j])
	            arr3.append(arr2)
	            count+=1
	        
	
	print("Number of Pairs :",count)
	for i in range(len(arr3)):
	    print(arr3[i])        
	
	
14.Sort an array using QuickSort.

	def swap(arr,i,j): 
	    t=arr[i]
	    arr[i]=arr[j]
	    arr[j]=t
	
	def partition(arr,low,high): 
	    pivot=arr[high]
	    i=low-1
	    for j in range(low,high): 
	        if(arr[j]<=pivot):
	            i+=1
	            swap(arr,i,j)
	    swap(arr,i+1,high)
	    return (i+1)
	
	def Quicksort(arr,low,high):
	    if (low<high):
	        p=partition(arr,low,high)
	        Quicksort(arr,low,p-1)
	        Quicksort(arr,p+1,high)
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(n):
	    a=int(input())
	    arr.append(a)
	
	print("Array :",arr)
	
	Quicksort(arr,0,n-1)
	print("After sorting :",arr)
	

15.Find common elements in three sorted arrays.

	'''Given three Sorted arrays in non-decreasing order, print all common
	elements in these arrays.
	
	Examples: 
	
	Input: 
	ar1[] = {1, 5, 10, 20, 40, 80} 
	ar2[] = {6, 7, 20, 80, 100} 
	ar3[] = {3, 4, 15, 20, 30, 70, 80, 120} 
	Output: 20, 80
	
	Input: 
	ar1[] = {1, 5, 5} 
	ar2[] = {3, 4, 5, 5, 10} 
	ar3[] = {5, 5, 10, 20} 
	Output: 5, 5
	'''
	
	def sort(arr,n):
	    for i in range(0,n-1):
	        for j in range(i+1,n):
	            if(arr[i]>arr[j]):
	                a=arr[i]
	                arr[i]=arr[j]
	                arr[j]=a
	    return arr
	
	def rem_dupli(arr,n):
	    arr5=[]
	    for i in range(0,n-2):
	        for j in range(i+1,n-1):
	            if(arr[i]==arr[j] and arr[i]==arr[j+1]):
	                arr5.append(arr[i])
	                arr.pop(j)
	                arr.pop(j+1)
	                n-=2
	            else:
	                break
	    return (sort(arr5,len(arr5)))
	                
	
	n1=int(input("Enter the number of elements :"))
	arr1=[]
	print("Enter the elements :")
	for i in range(0,n1):
	    a=int(input())
	    arr1.append(a)
	
	n2=int(input("Enter the number of elements :"))
	arr2=[]
	print("Enter the elements :")
	for i in range(0,n2):
	    a=int(input())
	    arr2.append(a)
	
	n3=int(input("Enter the number of elements :"))
	arr3=[]
	print("Enter the elements :")
	for i in range(0,n3):
	    a=int(input())
	    arr3.append(a)
	
	print("Array 1 :",arr1)
	print("Array 2 :",arr2)
	print("Array 3 :",arr3)
	
	arr4=[]
	for i in range(0,n1):
	    arr4.append(arr1[i])
	for i in range(0,n2):
	    arr4.append(arr2[i])
	for i in range(0,n3):
	    arr4.append(arr3[i])
	
	arr4=sort(arr4,n1+n2+n3)
	
	arr6=rem_dupli(arr4,n1+n2+n3)
	print("Common elements :",arr6)
	
### DAY 17:

 #### Top 50 DSA questions on Arrays continued:

 16.Find the first repeating element in an array of integers.

	'''Given an array of integers arr[], The task is to find the index of first
	repeating element in it i.e. the element that occurs more than once and whose
	index of the first occurrence is the smallest. 
	
	Examples: 
	
	Input: arr[] = {10, 5, 3, 4, 3, 5, 6}
	Output: 5 
	Explanation: 5 is the first element that repeats
	
	Input: arr[] = {6, 10, 5, 4, 9, 120, 4, 6, 10}
	Output: 6 
	Explanation: 6 is the first element that repeats
	'''
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(0,n):
	    a=int(input())
	    arr.append(a)
	print("Array :",arr)
	
	flag=1
	for i in range(0,n-1):
	    for j in range(i+1,n):
	        if(arr[i]==arr[j]):
	            print("First element that repeats itself :",arr[i])
	            flag=0
	            break
	        if(flag==0):
	            break 
	

17.Rearrange array in alternating positive & negative items with O(1) extra space| Set 1

	'''Given an array having positive and negative numbers, our task is to arrange
	them in an alternate fashion such that every positive number is followed by a
	negative number and vice-versa maintaining the order of appearance. The number
	of positive and negative numbers need not to be equal. If there are more
	positive numbers then they have to appear at the end of the array , same
	condition for negative numbers also .
	
	Examples: 
	
	Input:  arr[] = {1, 2, 3, -4, -1, 4}
	Output: arr[] = {-4, 1, -1, 2, 3, 4}
	
	Input:  arr[] = {-5, -2, 5, 2, 4, 7, 1, 8, 0, -8}
	Output: arr[] = {-5, 5, -2, 2, -8, 4, 7, 1, 8, 0}
	'''
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(0,n):
	    a=int(input())
	    arr.append(a)
	print("Array :",arr)
	
	arr1=[]
	arr2=[]
	for i in range(0,n):
	    if(arr[i]<0):
	        arr1.append(arr[i])
	    else:
	        arr2.append(arr[i])
	
	n1=len(arr1)
	n2=len(arr2)
	
	print(n1,n2)
	
	arr3=[]
	if(n1<n2):
	    j=0
	    k=0
	    for i in range(0,2*n1):
	        if(i%2==0):
	            arr3.append(arr1[j])
	            j+=1
	        else:
	            arr3.append(arr2[k])
	            k+=1
	    for i in range(n1,n2):
	        arr3.append(arr2[i])
	elif(n1==n2):
	    j=0
	    k=0
	    for i in range(0,2*n1):
	        if(i%2==0):
	            arr3.append(arr1[j])
	            j+=1
	        else:
	            arr3.append(arr2[k])
	            k+=1
	if(n1>n2):
	    j=0
	    k=0
	    for i in range(0,2*n2):
	        if(i%2==0):
	            arr3.append(arr1[j])
	            j+=1
	        else:
	            arr3.append(arr2[k])
	            k+=1
	    for i in range(n2,n1):
	        arr3.append(arr1[i])
	
	print("New Array :",arr3)

 18.Largest Sum Contiguous Subarray (Kadane’s Algorithm).

	'''Given an array arr[] of size N. The task is to find the sum of the
	contiguous subarray within a arr[] with the largest sum. 
	'''
	
	
	def maxSubarraySum(arr,n):
	    max_so_far=max_ending_here=0
	    for i in range(1,n):
	        max_ending_here=max(arr[i],max_ending_here+arr[i])
	        max_so_far=max(max_so_far,max_ending_here)
	    return(max_so_far)
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(n):
	    a=int(input())
	    arr.append(a)
	print("Array :",arr)
	
	maxsum=maxSubarraySum(arr,n)
	print("Maximum subarray sum in the array is",maxsum,".")
	
19.Find the Factorial of a large number.

	def fact(n):
	    val=1
	    for i in range(1,n+1):
	        val*=i
	    return val
	
	n=int(input("Enter the number :"))
	val=fact(n)
	print("Factorial of",n,"is :",val)
	 
20.Subarray with 0 sum.

	'''Given an array of positive and negative numbers, the task is to find if
	there is a subarray (of size at least one) with 0 sum.
	
	Examples: 
	
	Input: {4, 2, -3, 1, 6}
	Output: true 
	Explanation:
	There is a subarray with zero sum from index 1 to 3.
	
	Input: {4, 2, 0, 1, 6}
	Output: true
	Explanation: The third element is zero. A single element is also a sub-array.
	'''
	
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(n):
	    a=int(input())
	    arr.append(a)
	print("Array :",arr)
	
	s=0
	p=0
	for i in range(0,n):
	    su=s+arr[i]
	    p=i
	    if(su!=0):
	        for j in range(i+1,n):
	            su+=arr[j]
	            if(su==0):
	                p=j
	                break
	    if(su==0):
	        break
	if(i==n-1 and p==n-1 and arr[i]!=0):
	    print("There is no subarray with sum 0.")
	else:
	    print("Subarray with given sum :",arr[i:p+1])

21.Maximum Product Subarray.

	'''Given an array that contains both positive and negative integers, the task
	is to find the product of the maximum product subarray. 
	
	Examples:
	
	Input: arr[] = {6, -3, -10, 0, 2}
	Output:  180
	Explanation: The subarray is {6, -3, -10}
	
	Input: arr[] = {-1, -3, -10, 0, 60}
	Output:   60
	Explanation: The subarray is {60}
	'''
	
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(n):
	    a=int(input())
	    arr.append(a)
	print("Array :",arr)
	
	prod=arr[0]
	for i in range(0,n):
	    r=arr[i]
	    for j in range(i+1,n):
	        prod=max(prod,r)
	        r*=arr[j]
	    prod=max(prod,r)
	
	print("Maximum Product :",prod)

22.Find the Minimum element in a Sorted and Rotated Array.

	'''Given a sorted array arr[] (may be distinct or may contain duplicates) of
	size N that is rotated at some unknown point, the task is to find the minimum
	element in it. 
	
	Examples: 
	
	Input: arr[] = {5, 6, 1, 2, 3, 4}
	Output: 1
	Explanation: 1 is the minimum element present in the array.
	
	Input: arr[] = {1, 2, 3, 4}
	Output: 1
	
	'''
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(0,n):
	    a=int(input())
	    arr.append(a)
	print("Array :",arr)
	
	mini=arr[0]
	for i in range(1,n):
	    mini=min(arr[i],mini)
	print("Minimum element :",mini)

    
23.Maximum sum of i*arr[i] among all rotations of a given array.

	'''Given an array arr[] of n integers, find the maximum that maximizes the sum of the value of i*arr[i] where i varies from 0 to n-1.
	
	Examples:  
	
	Input: arr[] = {8, 3, 1, 2}
	Output: 29
	Explanation: Lets look at all the rotations,
	{8, 3, 1, 2} = 8*0 + 3*1 + 1*2 + 2*3 = 11
	{3, 1, 2, 8} = 3*0 + 1*1 + 2*2 + 8*3 = 29
	{1, 2, 8, 3} = 1*0 + 2*1 + 8*2 + 3*3 = 27
	{2, 8, 3, 1} = 2*0 + 8*1 + 3*2 + 1*3 = 17
	
	Input: arr[] = {3, 2, 1}
	Output: 7
	Explanation: Lets look at all the rotations,
	{3, 2, 1} = 3*0 + 2*1 + 1*2 = 4
	{2, 1, 3} = 2*0 + 1*1 + 3*2 = 7
	{1, 3, 2} = 1*0 + 3*1 + 2*2 = 7
	'''
	
	def summation(arr,n):
	    res=0
	    for i in range(0,n):
	        res+=(arr[i]*i)
	    return res
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(0,n):
	    a=int(input())
	    arr.append(a)
	print("Array :",arr)
	
	res1=summation(arr,n)
	for i in range(1,n):
	    arr1=[]
	    for j in range(i,n):
	        arr1.append(arr[j])
	    for j in range(0,i):
	        arr1.append(arr[j])
	    res=summation(arr1,n)
	    res1=max(res1,res)
	
	print("Maximum sum :",res1)
	
24.Minimum number of jumps to reach end (Jump Game).
	
	'''Given an array arr[] where each element represents the max number of steps
	that can be made forward from that index. The task is to find the minimum
	number of jumps to reach the end of the array starting from index 0.
	
	Examples: 
	
	Input: arr[] = {1, 3, 5, 8, 9, 2, 6, 7, 6, 8, 9}
	Output: 3 (1-> 3 -> 9 -> 9)
	Explanation: Jump from 1st element to 2nd element as there is only 1 step.
	Now there are three options 5, 8 or 9. If 8 or 9 is chosen then the end node
	9 can be reached. So 3 jumps are made.
	
	Input:  arr[] = {1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1}
	Output: 10
	Explanation: In every step a jump is needed so the count of jumps is 10.
	'''
	
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the steps :")
	for i in range(0,n):
	    a=int(input())
	    arr.append(a)
	print("Array :",arr)
	
	i=0
	a=0
	count=0
	while(i<n):
	    a+=arr[i]
	    count+=1
	    if(a>=n):
	        break
	    i=arr[a]
	    
	print("Number of jumps :",count)




### DAY 18:

 #### Top 50 DSA questions on Arrays continued:

25.The Stock Span Problem.

	'''The stock span problem is a financial problem where we have a series of N
	daily price quotes for a stock and we need to calculate the span of the stock’s
	price for all N days. The span Si of the stock’s price on a given day i is
	defined as the maximum number of consecutive days just before the given day,
	for which the price of the stock on the current day is less than or equal to
	its price on the given day. 
	
	Examples:
	
	Input: N = 7, price[] = [100 80 60 70 60 75 85]
	Output: 1 1 1 2 1 4 6
	Explanation: Traversing the given input span for 100 will be 1, 80 is smaller
	than 100 so the span is 1, 60 is smaller than 80 so the span is 1, 70 is
	greater than 60 so the span is 2 and so on. Hence the output will be
	1 1 1 2 1 4 6.
	
	Input: N = 6, price[] = [10 4 5 90 120 80]
	Output:1 1 2 4 5 1
	Explanation: Traversing the given input span for 10 will be 1, 4 is smaller
	than 10 so the span will be 1, 5 is greater than 4 so the span will be 2 and
	so on. Hence, the output will be 1 1 2 4 5 1.
	
	
	'''
	
	n=int(input("Enter the number of days :"))
	arr=[]
	print("Enter the stock prices :")
	for i in range(0,n):
	    a=int(input())
	    arr.append(a)
	print("Stock Prices :",arr)
	
	arr1=[]
	for i in range(0,n):
	    if(i==0):
	        span=1
	    else:
	        if(arr[i]<arr[i-1]):
	            span=1
	        else:
	            count=1
	            for j in range(i-1,-1,-1):
	                if(arr[j]<arr[i]):
	                    count+=1
	                else:
	                    break
	            span=count
	    arr1.append(span)
	
	print("Span :",arr1)


26.Find first non-repeating element in a given Array of integers.

	'''Given an array of integers of size N, the task is to find the first
	non-repeating element in this array. 
	
	Examples:
	
	Input: {-1, 2, -1, 3, 0}
	Output: 2
	Explanation: The first number that does not repeat is : 2
	
	Input: {9, 4, 9, 6, 7, 4}
	Output: 6
	'''
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(0,n):
	    a=int(input())
	    arr.append(a)
	print("Array :",arr)
	
	arr1=[]
	arr2=[]
	for i in arr:
	    if i not in arr1:
	        arr1.append(i)
	    else:
	        arr2.append(i)
	
	for i in range(0,len(arr1)):
	    flag=1
	    for j in range(0,len(arr2)):
	        if(arr1[i]==arr2[j]):
	            flag=0
	            break
	        else:
	            flag=1
	    if(flag==1):
	        break
	
	print("First non-repeating element :",arr1[i])
	
	
27.Find the row with maximum number of 1s.

	'''Given a boolean 2D array, where each row is sorted. Find the row with the
	maximum number of 1s. 
	
	Example:  
	
	Input matrix :          0 1 1 1
	                        0 0 1 1
	                        1 1 1 1  // this row has maximum 1s
	                        0 0 0 0
	Output: 2
	'''
	
	
	r=int(input("Enter the number of rows :"))
	c=int(input("Enter the number of columns :"))
	print("Enter the elements :")
	arr=[]
	for i in range(0,r):
	    arr1=[]
	    for j in range(0,c):
	        a=int(input())
	        arr1.append(a)
	    arr.append(arr1)
	
	print("Matrix :")
	for i in range(0,r):
	    for j in range(0,c):
	        print(arr[i][j],end=" ")
	    print("\n")
	
	flag=0
	a=[]
	p=r
	for i in range(0,c):
	    for j in range(0,p):
	        if(arr[j][i]==1):
	            a.append(j)
	            p=i
	            flag=1
	            
	    if(flag==1):
	        break
	print("Row with maximum number of 1's : ",end="")
	for i in range(0,len(a)):
	    print(a[i],end=" ")


28.Find whether an array is subset of another array.

	'''Given two arrays: arr1[0..m-1] and arr2[0..n-1]. Find whether arr2[] is a
	subset of arr1[] or not. Both arrays are not in sorted order. It may be
	assumed that elements in both arrays are distinct.
	
	Examples: 
	
	Input: arr1[] = {11, 1, 13, 21, 3, 7}, arr2[] = {11, 3, 7, 1} 
	Output: arr2[] is a subset of arr1[]
	
	Input: arr1[] = {1, 2, 3, 4, 5, 6}, arr2[] = {1, 2, 4} 
	Output: arr2[] is a subset of arr1[]
	
	'''
	
	n1=int(input("Enter the number of elements of 1st array :"))
	arr1=[]
	print("Enter the elements :")
	for i in range(0,n1):
	    a=int(input())
	    arr1.append(a)
	print("Array 1 :",arr1)
	
	n2=int(input("Enter the number of elements of 2nd array :"))
	arr2=[]
	print("Enter the elements :")
	for i in range(0,n2):
	    a=int(input())
	    arr2.append(a)
	print("Array 2 :",arr2)
	
	flag=1
	if(n1>n2):
	    for i in range(0,n2):
	        for j in range(0,n1):
	            if(arr2[i]==arr1[j]):
	                flag=0
	                break
	            else:
	                flag=1
	    if(flag==0):
	        print("arr2[] is a subset of arr1[]")
	    else:
	        print("arr2[] is not a subset of arr1[]")


29.Majority Element.

	'''Find the majority element in the array. A majority element in an array A[]
	of size n is an element that appears more than n/2 times (and hence there is
	at most one such element). 
	
	Examples : 
	
	Input : A[]={3, 3, 4, 2, 4, 4, 2, 4, 4}
	Output : 4
	Explanation: The frequency of 4 is 5 which is greater than the half of the
	size of the array size. 
	
	Input : A[] = {3, 3, 4, 2, 4, 4, 2, 4}
	Output : No Majority Element
	Explanation: There is no element whose frequency is greater than the half of
	the size of the array size.
	
	'''
	
	def sort(arr,n):
	    for i in range(0,n-1):
	        for j in range(i+1,n):
	            if(arr[i]>arr[j]):
	                a=arr[i]
	                arr[i]=arr[j]
	                arr[j]=a
	
	    return arr
	
	def major(arr,n):
	    a=n//2
	    maxi=0
	    i=0
	    while(i<n):
	        count=1
	        if(i==n-1):
	            break
	        else:
	            for j in range(i+1,n):
	                if(arr[i]==arr[j]):
	                    count+=1
	                else:
	                    i=j+1
	                    break
	            maxi=max(count,maxi)
	            if(maxi>a):
	                break
	    return maxi,arr[i]
	    
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(0,n):
	    a=int(input())
	    arr.append(a)
	print("Array :",arr)
	
	arr=sort(arr,n)
	
	maxi,b=major(arr,n)
	print(maxi)
	if(maxi>n//2):
	    print("Majority element :",b)
	else:
	    print("There is no majority element.")


30.Find the missing and repeating number.

	'''Given an unsorted array of size n. Array elements are in the range of 1 to n.
	One number from set {1, 2, …n} is missing and one number occurs twice in the
	array. Find these two numbers.
	
	Examples: 
	
	Input: arr[] = {3, 1, 3}
	Output: Missing = 2, Repeating = 3
	Explanation: In the array, 2 is missing and 3 occurs twice 
	
	Input: arr[] = {4, 3, 6, 2, 1, 1}
	Output: Missing = 5, Repeating = 1
	'''
	
	def bubsort(arr,n):
	    for i in range(0,n):
	        for j in range(i+1,n):
	            if(arr[i]>arr[j]):
	                a=arr[i]
	                arr[i]=arr[j]
	                arr[j]=a
	
	n=int(input("Enter the number of elements :"))
	arr=[]
	print("Enter the elements :")
	for i in range(n):
	    a=int(input())
	    arr.append(a)
	print("Array :",arr)
	
	bubsort(arr,n)
	
	arr1=[]
	for i in range(0,n-1):
	    if(arr[i]==arr[i+1]):
	        print("Repeating element :",arr[i])
	        break
	
	for i in range (1,n+1):
	    if i not in arr:
	        print("Missing element :",i)
	        break
	

### DAY 19:

 #### Top 50 DSA questions on Strings:

 1.Reverse words in a given string.

	'''Given a string, the task is to reverse the order of the words in the given
	string. 
	
	Examples:
	
	Input: s = “geeks quiz practice code” 
	Output: s = “code practice quiz geeks”
	
	Input: s = “i love programming very much” 
	Output: s = “much very programming love i” 
	
	'''
	
	a=input("Enter the string :")
	j=len(a)
	print("Reversed words :",end=" ")
	for i in range(len(a)-1,0,-1):
	    if(a[i]==" "):
	        print(a[i+1:j],end=" ")
	        j=i
	print(a[0:j])

 2.Longest Common Prefix using Sorting.

	'''Problem Statement: Given a set of strings, find the longest common prefix.
	Examples:
	
	Input: {“geeksforgeeks”, “geeks”, “geek”, “geezer”}
	Output: “gee”
	
	Input: {“apple”, “ape”, “april”}
	Output: “ap”
	'''
	
	print("Enter the strings :",end=" ")
	a=list(map(str,input().split()))
	print(a)
	arr=a[0]
	b=len(arr)
	p=0
	for i in range(1,len(a)):
	    mini=min(len(arr),len(a[i]))
	    for j in range(0,mini):
	        if(arr[j]==a[i][j]):
	            p=j
	            continue
	        else:
	            break
	    b=min(b,p)
	
	print("Longest common prefix :",arr[0:b+1])

 3.Find the minimum distance between the given two words.

	'''Given a list of words followed by two words, the task is to find the
	minimum distance between the given two words in the list of words.
	
	Examples:
	
	Input: S = { “the”, “quick”, “brown”, “fox”, “quick”}, word1 = “the”,
	word2 = “fox”
	
	Output: 3
	Explanation: Minimum distance between the words “the” and “fox” is 3
	
	Input: S = {“geeks”, “for”, “geeks”, “contribute”,  “practice”},
	word1 = “geeks”, word2 = “practice”
	
	Output: 2
	Explanation: Minimum distance between the words “geeks” and “practice” is 2
	'''
	
	print("Enter the string :",end=" ")
	a=list(map(str,input().split()))
	s1=input("Enter string1 :")
	s2=input("Enter string2 :")
	
	p=q=mini=len(a)
	for i in range(0,len(a)):
	    if(a[i]==s1):
	        p=i
	    if(a[i]==s2):
	        q=i
	    s=p-q
	    if(s<0):
	        s*=-1
	    mini=min(mini,s)
	print("Minimum distance :",mini)

 4.Check divisibility by 7.

	'''Given a number N, the task is to check if it is divisible by 7 or not.
	Note: You are not allowed to use the modulo operator, floating point
	arithmetic is also not allowed.
	
	'''
	
	def divisible_by_7(n):
	    if(n>0):
	        n-=7
	        divisible_by_7(n)
	    elif(n==0):
	        print("It is divisible by 7.")
	    else:
	        print("It is not divisible by 7.")
	
	n=int(input("Enter a number :"))
	n1=divisible_by_7(n)

 5.Check if given String is Pangram or not.

	'''Given a string Str. The task is to check if it is Pangram or not. 
	
	A pangram is a sentence containing every letter in the English Alphabet.
	
	Examples: 
	
	Input: “The quick brown fox jumps over the lazy dog” 
	Output: is a Pangram 
	Explanation: Contains all the characters from ‘a’ to ‘z’] 
	
	Input: “The quick brown fox jumps over the dog”
	Output: is not a Pangram 
	Explanation: Doesn’t contain all the characters from ‘a’ to ‘z’, as ‘l’, ‘z’,
	‘y’ are missing
	
	'''
	
	def bubsort(arr,n):
	    for i in range(0,n-1):
	        for j in range(i+1,n):
	            if(arr[i]>arr[j]):
	                a=arr[i]
	                arr[i]=arr[j]
	                arr[j]=a
	
	def del_dupli(arr,n):
	    arr2=[]
	    for i in arr:
	        if i not in arr2:
	            arr2.append(i)
	    return arr2
	
	def panagram(arr,n):
	    a=97
	    flag=1
	    for i in range(1,n):
	        if(ord(arr[i])==a):
	            a+=1
	            flag=0
	        else:
	            flag=1
	    if(flag==0):
	        return 0
	    else:
	        return 1
	    
	arr=input("Enter a string :")
	arr=arr.lower()
	arr1=list(arr)
	bubsort(arr1,len(arr1))
	arr1=del_dupli(arr1,len(arr1))
	a=panagram(arr1,len(arr1))
	if(a==1):
	    print("It is not a panagram.")
	else:
	    print("It is a panagram.")


6.Check if a string can be obtained by rotating another string 2 places.

	'''Given two strings, the task is to find if a string can be obtained by
	rotating another string by two places. 
	
	Examples: 
	
	Input: string1 = “amazon”, string2 = “azonam” 
	Output: Yes 
	Explanation: Rotating string1 by 2 places in anti-clockwise gives the string2.
	
	
	Input: string1 = “amazon”, string2 = “onamaz” 
	Output: Yes 
	Explanation: Rotating string1 by 2 places in clockwise gives the string2.
	'''
	
	def compare(arr1,arr2,n):
	    flag=0
	    for i in range(0,n):
	        if(arr1[i]==arr2[i]):
	            continue
	        else:
	            flag=1
	            break
	    if(flag==1):
	        return False
	    else:
	        return True
	        
	    
	str1=input("Enter string 1 :")
	str2=input("Enter string 2 :")
	
	str3=[]
	str3.append(str2[len(str2)-2])
	str3.append(str2[len(str2)-1])
	for i in range(0,len(str1)-2):
	    str3.append(str2[i])
	
	
	str5=[]
	for i in range(2,len(str2)):
	    str5.append(str2[i])
	str5.append(str2[0])
	str5.append(str2[1])
	
	
	if(compare(str3,str1,len(str1)) or compare(str5,str1,len(str1))):
	    print("Yes")
	else:
	    print("NO")


### DAY 20:

Revised learnings of Day 14 and 15 (TREES)



### DAY 21:

##### Deleting a Node in Binary Tree:

To delete a node from a binary tree in Python, you need to consider different cases:

1.Starting at the root, find the deepest and rightmost node in the binary tree and the node which we want to delete. 

2.Replace the deepest rightmost node’s data with the node to be deleted. 

3.Then delete the deepest rightmost node.

	class TreeNode:
	    def __init__(self, key):
	        self.key = key
	        self.left = None
	        self.right = None
	
	def inorder_traversal(root):
	    result = []
	    if root:
	        result = inorder_traversal(root.left)
	        result.append(root.key)
	        result += inorder_traversal(root.right)
	    return result
	
	def deleteDeepest(root, d_node): 
	    q = [] 
	    q.append(root) 
	    while(len(q)): 
	        temp = q.pop(0) 
	        if temp is d_node: 
	            temp = None
	            return
	        if temp.right: 
	            if temp.right is d_node: 
	                temp.right = None
	                return
	            else: 
	                q.append(temp.right) 
	        if temp.left: 
	            if temp.left is d_node: 
	                temp.left = None
	                return
	            else: 
	                q.append(temp.left)
	
	def deletion(root, key): 
	    if root == None: 
	        return None
	    if root.left == None and root.right == None: 
	        if root.key == key: 
	            return None
	        else: 
	            return root 
	    key_node = None
	    q = [] 
	    q.append(root) 
	    temp = None
	    while(len(q)): 
	        temp = q.pop(0) 
	        if temp.key == key: 
	            key_node = temp 
	        if temp.left: 
	            q.append(temp.left) 
	        if temp.right: 
	            q.append(temp.right) 
	    if key_node: 
	        x = temp.key 
	        deleteDeepest(root, temp) 
	        key_node.key = x 
	    return root 
	
	# Example usage:
	A=TreeNode(10)
	B=TreeNode(11)
	C=TreeNode(7)
	D=TreeNode(12)
	E=TreeNode(9)
	F=TreeNode(15)
	G=TreeNode(8)
	
	A.left=B
	B.left=C
	B.right=D
	A.right=E
	E.left=F
	E.right=G
	
	print(inorder_traversal(A))
	
	root = deletion(A, 11)
	
	print(inorder_traversal(A))

    

##### Deleting a Node in Binary Search Tree:

To delete a node from a binary search tree (BST) in Python, you need to consider different cases:

1.If the node to be deleted is a leaf node (no children), simply remove it from its parent.

2.If the node to be deleted has only one child, replace the node with its child.

3.If the node to be deleted has two children, find the inorder successor (or predecessor), copy its data to the node to be deleted, and then delete the inorder successor (or predecessor).

	class TreeNode:
	    def __init__(self, key):
	        self.key = key
	        self.left = None
	        self.right = None
	
	
	def insert(root,x):
	    if root is None:
	        return (TreeNode(x))
	    else:
	        if(root.key<x):
	            root.right=insert(root.right,x)
	        else:
	            root.left=insert(root.left,x)
	    return root
	
	def inorder_traversal(root):
	    result = []
	    if root:
	        result = inorder_traversal(root.left)
	        result.append(root.key)
	        result += inorder_traversal(root.right)
	    return result
	
	def deleteNode(root, k):
	    if root is None:
	        return root
	 
	    if root.key > k:
	        root.left = deleteNode(root.left, k)
	        return root
	    elif root.key < k:
	        root.right = deleteNode(root.right, k)
	        return root
	
	    if root.left is None:
	        temp = root.right
	        del root
	        return temp
	    elif root.right is None:
	        temp = root.left
	        del root
	        return temp
	    else:
	        succParent = root
	        succ = root.right
	        while succ.left is not None:
	            succParent = succ
	            succ = succ.left
	
	    if succParent != root:
	            succParent.left = succ.right
	    else:
	        succParent.right = succ.right
	    root.key = succ.key
	    del succ
	    return root
	
	# Example usage:
	A=TreeNode(50)
	
	A=insert(A,30)
	A=insert(A,20)
	A=insert(A,40)
	A=insert(A,70)
	A=insert(A,60)
	
	print(inorder_traversal(A))
	
	root = deleteNode(A, 20)
	print(inorder_traversal(A))
	
	root = deleteNode(A, 70)
	print(inorder_traversal(A))
	
	root = deleteNode(A, 50)
	
	print(inorder_traversal(A))
	
	
##### Solved HackerRank Challenges :

1.Mr. Anant Asankhya is the manager at the INFINITE hotel. The hotel has an infinite amount of rooms.

One fine day, a finite number of tourists come to stay at the hotel.

The tourists consist of:

→ A Captain.

→ An unknown group of families consisting of K members per group where K ≠ 1.

The Captain was given a separate room, and the rest were given one room per group.

Mr. Anant has an unordered list of randomly arranged room entries. The list consists of the room numbers for all of the tourists. The room numbers will appear K times per group except for the Captain's room.

Mr. Anant needs you to help him find the Captain's room number.
The total number of tourists or the total number of groups of families is not known to you.
You only know the value of K and the room number list.


	def merge_sort(arr):
	    if (len(arr)>1):
	        mid=len(arr)//2      
	        l=arr[:mid]
	        r=arr[mid:]
	        merge_sort(l)
	        merge_sort(r)
	 
	        i=0
	        j=0
	        k=0
	        
	        while ((i<len(l))and(j<len(r))):
	            if (l[i]<=r[j]):
	                arr[k]=l[i]
	                i+=1
	            else:
	                arr[k]=r[j]
	                j+=1
	            k+=1
	 
	        while (i<len(l)):
	            arr[k]=l[i]
	            i+=1
	            k+=1
	 
	        while (j<len(r)):
	            arr[k]=r[j]
	            j+=1
	            k+=1
	
	def find_single(arr,n,K):
	    flag=1
	    count=1
	    for i in range(0,n-1):
	        if(arr[i]==arr[i+1]):
	            count+=1
	        else:
	            if(count==K):
	                count=1
	            elif(count==1):
	                flag=0
	                break
	    if(flag==0):
	        return arr[i]
	    else:
	        return arr[n-1]
	    
	
	K=int(input())
	arr=list(map(int,input().split()))
	merge_sort(arr)
	count=find_single(arr,len(arr),K)
	print(count)

 ![image](https://github.com/titli17/DailyLearnings_in_PYTHON_and_AIML-/assets/96014974/e97f635b-0728-4c75-b347-56424d0efde7)


 2.Given the participants' score sheet for your University Sports Day, you are required to find the runner-up score. You are given n scores. Store them in a list and find the score of the runner-up.


	if __name__ == '__main__':
	    n = int(input())
	    arr = list(map(int, input().split()))
	    
	    max=-101
	    for i in range(0,n):
	        if(arr[i]>max):
	            max=arr[i]
	    
	    sec_max=-101
	    for i in range(0,n):
	        if(arr[i]>sec_max and arr[i]<max):
	            sec_max=arr[i]
	    
	    print(sec_max)

     ![image](https://github.com/titli17/DailyLearnings_in_PYTHON_and_AIML-/assets/96014974/b20c9130-f0fb-4b85-8496-688a3837109d)






    











	
