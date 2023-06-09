# Data-analysis
## First step with python

![hero](images/hero1.png)
<details>
<summary>Here, I have learnt some basic shortcuts for Jupyter notebook.</summary>

- Select cell on the blue and press A to insert cell above
- Select cell and press Esc + A to insert cell above
- Select cell on the blue and press B to insert cell below
- Select cell and press Esc + B to insert cell below
- Select cell on the blue and press D twice to delete cell
- To change the cell type press Esc + Y a then Esc + M for markdown
- To run cell press Shift + Enter
</details> 
<details>
<summary>Some basic operators</summary>

![Operator](images/operator.png)
</details>   

<details>
<summary>NameError is when we don’t define a variabler beforehand but invoke it.</summary>

![name](images/name.png)
</details>   

<details>
<summary>Commenting</summary>

- ‘#- - -#’ is for single line comment
- “””- - -””” is for multi line comment
</details>
    
<details>
<summary>Printing</summary>

print() is the function for printing something, usually a aiding text, First argument of this function is quoted test like “this a the value” and the second argument is the value of the calculation.

</details>
    
<details>
<summary>Conditional Operator</summary>

![Conditional](images/Conditional.png)

Result of the compare is either True or Flase

</details> 

<details>
<summary>Logical Operator</summary>

- And Operator

![and](images/and.png)
        
- Or Operator

![or](images/or.png)
        
- Not Operator  
    - Not operator just inverse the result. i.e. True get False and Flase get True

</details> 
    
<details>
<summary>Markdown</summary>

This is a [link](https://learnxinyminutes.com/docs/markdown/)

</details>     

<details>
<summary>Further Reading and References</summary>

Following are some resources where you can learn about more arithmetic, conditional and logical operations in Python:
    
- [Python Tutorial at W3Schools](https://www.notion.so/Python-586d26da5fc94e37bbaf829054a8fcf2)
- [Practical Python Programming](https://dabeaz-course.github.io/practical-python/Notes/Contents.html)
- [Python official documentation](https://docs.python.org/3/tutorial/index.html)
- [Detailed operator documentation](https://www.geeksforgeeks.org/python-operators/)

</details> 

<details>
<summary>Questions for Revision</summary>

- Try answering the following questions to test your understanding of the topics covered in this notebook:

    1. What is a Jupyter notebook?
    2. How do you add a new code cell below an existing cell?
    3. How do you add a new Markdown cell below an existing cell?
    4. How do you convert a code cell to a Markdown cell or vice versa?
    5. How do you execute a code cell within Jupyter?
    6. What the different arithmetic operations supported in Python?
    7. How do you perform arithmetic operations using Python?
    8. What is the difference between the `/` and the `//` operators?
    9. What is the difference between the `` and the `*` operators?
    10. What is the order of precedence for arithmetic operators in Python?
    11. How do you specify the order in which arithmetic operations are performed in an expression involving multiple operators?
    12. How do you solve a multi-step arithmetic word problem using Python?
    13. What are variables? Why are they useful?
    14. How do you create a variable in Python?
    15. What is the assignment operator in Python?
    16. What are the rules for naming a variable in Python?
    17. How do you view the value of a variable?
    18. How do you store the result of an arithmetic expression in a variable?
    19. What happens if you try to access a variable that has not been defined?
    20. How do you display messages in Python?
    21. What type of inputs can the print function accept?
    22. What are code comments? How are they useful?
    23. What are the different ways of creating comments in Python code?
    24. What are the different comparison operations supported in Python?
    25. What is the result of a comparison operation?
    26. What is the difference between `=` and `==` in Python?
    27. What are the logical operators supported in Python?
    28. What is the difference between the `and` and `or` operators?
    29. Can you use comparison and logical operators in the same expression?
    30. What is the purpose of using parentheses in arithmetic or logical expressions?
    31. What is Markdown? Why is it useful?
    32. How do you create headings of different sizes using Markdown?
    33. How do you create bulleted and numbered lists using Markdown?
    34. How do you create bold or italic text using Markdown?
    35. How do you include links & images within Markdown cells?
    36. How do you include code blocks within Markdown cells?
    37. Is it possible to execute the code blocks within Markdown cells?
    38. How do you upload and share your Jupyter notebook online using Jovian?
    39. What is the purpose of the API key requested by jovian.commit ? Where can you find the API key?
    40. Where can you learn about arithmetic, conditional and logical operations in Python?

</details>

## Pyhton Data types and variables

![hero](images/hero2.png)
<details>
<summary>Assigning variable value</summary>

```python
fruit1 = 'apple'
```
    
```python
fruit1, fruit2, fruit3 = 'apple', 'mango', 'grape'
```
    
```python
fruit1, fruit2, fruit3 = 'apple'
```
</details>
    
<details>
<summary>Naming convention</summary>

- Start with alphabet or _
- No spaces or speacial charecter
- Names are case-sensative

</details>

<details>
<summary>Data Types</summary>

 <details>
<summary>Primitive</summary>
<ul>
<li>Integer (2022)</li>
<li>Float (3.1415..)</li>
<li>Boolean ( True, False )</li>
<li>None ( used when it is needed to declare a variable for later use )
</li>
<li>
<details>
<summary>String ( “apple”).</summary>

- Strings created using single or double quotes must begin and end on the same line.
- To create multiline strings, use three single quotes `'''` or three double quotes `"""` to begin and end the string. Line breaks are represented using the newline character `\n` , Gets properly executed when it is printed.
- Strings also support several list operations, which are discussed in the next section. We'll look at a couple of examples here.
- You can access individual characters within a string using the `[]` indexing notation. Note the character indices go from `0` to `n-1`, where `n` is the length of the string.
- You can access a part of a string using by providing a `start:end` range instead of a single index in `[]`.
- You can also check whether a string contains a some text using the `in` operator.
- Two or more strings can be joined or *concatenated* using the `+` operator. Be careful while concatenating strings, sometimes you may need to add a space character `" "` between words.
- Strings in Python have many built-in *methods* that are used to manipulate them. Let's try out some common string methods.

> Methods: Methods are functions associated with data types and are accessed using the . notation e.g. variable_name.method() or "a string".method(). Methods are a powerful technique for associating common operations with values of specific data types.
> 

The `.lower()`, `.upper()`, `.capitalize()`, `.replace()` , `strip()`, `split()` and `format()`  are commonly used methods. [Methods Documentation](https://www.w3schools.com/python/python_ref_string.asp)
- string methods return a modified version of the real string.

</details>
</li>
</ul>
</details>

<details>
<summary>Containers</summary>
<details>
<summary>List</summary>

- A list in Python is an ordered collection of values. Lists can hold values of different data types and support operations to add, remove, and change values.
- List [’a’,’p’,’p’,’l’,’e’]. list() function can convert string to a lists.
- As list is an ordered list so we can access list via index , index more than a `len(list)` it  will give an `indexerror` .
- Negative indices return the value from the end of a list, i.e. `list_name[-1]` will give last entry of the list.
- We can also access a range of values by using `list_name[2:5]` , where second boundary is exclusive.
- [List method list.](https://www.w3schools.com/python/python_ref_list.asp)

</details>

<details>
<summary>Tuples</summary>

- A tuple is an ordered collection of values, similar to a list. However, it is not possible to add, remove, or modify values in a tuple. A tuple is created by enclosing values within parentheses `(` and `)`, separated by commas.
- You can also skip the parantheses `(` and `)` while creating a tuple. Python automatically converts comma-separated values into a tuple.
- [Tuple Methods](https://www.w3schools.com/python/python_ref_tuple.asp)

</details>
<details>
<summary>Dictionary</summary>

- A dictionary is an unordered collection of items. Each item stored in a dictionary has a key and value. You can use a key to retrieve the corresponding value from the dictionary. Dictionaries have the type `dict`.
- Dictionaries are often used to store many pieces of information e.g. details about a person, in a single variable. Dictionaries are created by enclosing key-value pairs within braces or curly brackets `{` and `}`.
- [Dictionary methods](https://www.w3schools.com/python/python_ref_dictionary.asp)

</details> 

</details>

- [Data type documentation](https://www.geeksforgeeks.org/python-set-3-strings-lists-tuples-iterations/)
   
- `type()` is a function that cast the variable type.
- division operator always return float type. To avoid this for integers we can use ‘//’ sign.
- `len()` is a function that returns the length of a string.
- `str()` is a function to change other data type to string.
- You can access individual characters within a string using the `[]` indexing notation. Note the character indices go from `0` to `n-1`, where `n` is the length of the string. i.e. `variable name[0:5]`
- You can also check whether a string contains a some text using the `in` operator. `'text' in variable name`
- Python has a date time module.
- To know about methods we can do `variable. + tab` , that will show us all the methods available for that data type. Also to know what a specific method do, we can ask python `?variable name.mehtod` . or we can just type `help(varible.method)` .

<details>
<summary>Truthy and Falsy values</summary>

- Any value in Python can be converted to a Boolean using the `bool` function. 
    Only the following values evaluate to `False` (they are often called *falsy* values):
    
    1. The value `False` itself
    2. The integer `0`
    3. The float `0.0`
    4. The empty value `None`
    5. The empty text `""`
    6. The empty list `[]`
    7. The empty tuple `()`
    8. The empty dictionary `{}`
    9. The empty set `set()`
    10. The empty range `range(0)`
    - Everything else evaluates to `True` (a value that evaluates to `True` is often called a *truthy* value).

</details>

- `str()` is a function to change other data type to string.
- You can access individual characters within a string using the `[]` indexing notation. Note the character indices go from `0` to `n-1`, where `n` is the length of the string. i.e. `variable name[0:5]`
- You can also check whether a string contains a some text using the `in` operator. `'text' in variable name`
- Python has a date time module.
- To know about methods we can do `variable. + tab` , that will show us all the methods available for that data type. Also to know what a specific method do, we can ask python `?variable name.mehtod` . or we can just type `help(varible.method)` .

</details>
<details>
<summary>Questions for Revision</summary>
Try answering the following questions to test your understanding of the topics covered in this notebook:

1. What is a variable in Python?
2. How do you create a variable?
3. How do you check the value within a variable?
4. How do you create multiple variables in a single statement?
5. How do you create multiple variables with the same value?
6. How do you change the value of a variable?
7. How do you reassign a variable by modifying the previous value?
8. What does the statement `counter += 4` do?
9. What are the rules for naming a variable?
10. Are variable names case-sensitive? Do `a_variable`, `A_Variable`, and `A_VARIABLE` represent the same variable or different ones?
11. What is Syntax? Why is it important?
12. What happens if you execute a statement with invalid syntax?
13. How do you check the data type of a variable?
14. What are the built-in data types in Python?
15. What is a primitive data type? 
16. What are the primitive data types available in Python?
17. What is a data structure or container data type?
18. What are the container types available in Python?
19. What kind of data does the Integer data type represent?
20. What are the numerical limits of the integer data type?
21. What kind of data does the float data type represent?
22. How does Python decide if a given number is a float or an integer?
23. How can you create a variable which stores a whole number, e.g., 4 but has the float data type?
24. How do you create floats representing very large (e.g., 6.023 x 10^23) or very small numbers (0.000000123)?
25. What does the expression `23e-12` represent?
26. Can floats be used to store numbers with unlimited precision?
27. What are the differences between integers and floats?
28. How do you convert an integer to a float?
29. How do you convert a float to an integer?
30. What is the result obtained when you convert 1.99 to an integer?
31. What are the data types of the results of the division operators `/` and `//`?
32. What kind of data does the Boolean data type represent?
33. Which types of Python operators return booleans as a result?
34. What happens if you try to use a boolean in arithmetic operation?
35. How can any value in Python be covered to a boolean?
36. What are truthy and falsy values?
37. What are the values in Python that evaluate to False?
38. Give some examples of values that evaluate to True.
39. What kind of data does the None data type represent?
40. What is the purpose of None?
41. What kind of data does the String data type represent?
42. What are the different ways of creating strings in Python?
43. What is the difference between strings creating using single quotes, i.e. `'` and `'` vs. those created using double quotes, i.e. `"` and `"`?
44. How do you create multi-line strings in Python?
45. What is the newline character, `\n`?
46. What are escaped characters? How are they useful?
47. How do you check the length of a string?
48. How do you convert a string into a list of characters?
49. How do you access a specific character from a string?
50. How do you access a range of characters from a string?
51. How do you check if a specific character occurs in a string?
52. How do you check if a smaller string occurs within a bigger string?
53. How do you join two or more strings?
54. What are "methods" in Python? How are they different from functions?
55. What do the `.lower`, `.upper` and `.capitalize` methods on strings do?
56. How do you replace a specific part of a string with something else?
57. How do you split the string "Sun,Mon,Tue,Wed,Thu,Fri,Sat" into a list of days?
58. How do you remove whitespace from the beginning and end of a string?
59. What is the string `.format` method used for? Can you give an example?
60. What are the benefits of using the `.format` method instead of string concatenation?
61. How do you convert a value of another type to a string?
62. How do you check if two strings have the same value?
63. Where can you find the list of all the methods supported by strings?
64. What is a list in Python?
65. How do you create a list?
66. Can a Python list contain values of different data types?
67. Can a list contain another list as an element within it?
68. Can you create a list without any values?
69. How do you check the length of a list in Python?
70. How do you retrieve a value from a list?
71. What is the smallest and largest index you can use to access elements from a list containing five elements?
72. What happens if you try to access an index equal to or larger than the size of a list?
73. What happens if you try to access a negative index within a list?
74. How do you access a range of elements from a list?
75. How many elements does the list returned by the expression `a_list[2:5]` contain?
76. What do the ranges `a_list[:2]` and `a_list[2:]` represent?
77. How do you change the item stored at a specific index within a list?
78. How do you insert a new item at the beginning, middle, or end of a list?
79. How do you remove an item from al list?
80. How do you remove the item at a given index from a list?
81. How do you check if a list contains a value?
82. How do you combine two or most lists to create a larger list?
83. How do you create a copy of a list?
84. Does the expression `a_new_list = a_list` create a copy of the list `a_list`?
85. Where can you find the list of all the methods supported by lists?
86. What is a Tuple in Python?
87. How is a tuple different from a list?
88. Can you add or remove elements in a tuple?
89. How do you create a tuple with just one element?
90. How do you convert a tuple to a list and vice versa?
91. What are the `count` and `index` method of a Tuple used for?
92. What is a dictionary in Python?
93. How do you create a dictionary?
94. What are keys and values?
95. How do you access the value associated with a specific key in a dictionary?
96. What happens if you try to access the value for a key that doesn't exist in a dictionary?
97. What is the `.get` method of a dictionary used for?
98. How do you change the value associated with a key in a dictionary?
99. How do you add or remove a key-value pair in a dictionary?
100. How do you access the keys, values, and key-value pairs within a dictionary?

</details>

