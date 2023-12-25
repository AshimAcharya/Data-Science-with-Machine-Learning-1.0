### 1.Explain the significance of Python keywords and proide examples of five keywords.  
Keywords are special(reserved) words in Python that can not be used as variable(identifier)  
and provide clear set of instruction to the machine and make programming easier by setting clear pattern.  

 Keywords can be accessed by typing the command:-  

```python
help('keywords')  
```

The examples of keywords are help, while, for, do, continue etc and so on.     
    
### 2.  Describe the rules for defining identifiers in Python and provide an example.
Identifiers are names used to identify variables, functions, classes, etc. In Python, identifiers:

1. Can be used both small(a-z), capital(A-Z) letter or number(0-9).
2. Cann't start with number but can be followed after letter or underscore(_). _2file(allowed) but 2file(not allowed)
3. Special characters are not allowed except underscore(_).
4. Space is not allowed at all. (file name) *not allowed.*  

### 3. What are comments in Python, and why are they useful? Provide an example.
**Comments** are the descriptive text that may describe any thing related to the code e.g function, variable, section of code or output. They are ignored by interpreter. Comments can be either single or multiple line.

*Single-line comment* are written as 
```python
# This is example of single line comment.
```
*multiple-line comment* are written as 
``` python
""" This is example of
    multiple line of comment."""
```
### 4. Why is proper indentation important in Python?
Proper indentation provides clearity and readibility of the code as well as improper indentation leads to indentation error or syntax error.Also, indentation is used to define the block of code, such as loops, conditional statements, function definitions, and more. The spaces or tabs used for indentation signify the grouping of statements within a block.

### 5. What happens if indentation is incorrect in Python?
Incorrect indentation  lead to syntax errors or change the logical structure of the code. For example, an improperly indented block inside a loop or condition may execute unexpectedly or throw an indentation-related error.

### 6. Differentiate between expression and statement in Python with examples.

Expressions are combinations of values, variables, and operators that evaluate to a single value. Statements are line or multiple line of code that executes and create some result. For example:

```Python
# Expression example
x = 5 - 4
```
```Python
# Statement example
if x = 10:
    print("x is equal to 10")
```
