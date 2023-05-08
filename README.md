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

</details>
</li>
</ul>
</details>

<details>
<summary>Containers</summary>

- List [’a’,’p’,’p’,’l’,’e’]. list() function can convert string to a lists.
- Tuple
- Dictionary

</details>

- [Data type documentation](https://www.geeksforgeeks.org/python-set-3-strings-lists-tuples-iterations/)
  

        
- `type()` is a function that cast the variable type.
- division operator always return float type. To avoid this for integers we can use ‘//’ sign.
- `len()` is a function that returns the length of a string.
- Truthy and Falsy values
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
- `str()` is a function to change other data type to string.

</details>

   