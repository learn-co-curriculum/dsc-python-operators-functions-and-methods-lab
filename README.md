
# Built-in Python Operators, Functions and Methods - Lab

## Introduction
We've looked at some of the built-in methods, functions, and the operators in Python. These are all very powerful tools we can (and will) use in our code. Below, we'll put these new tools to use to solve the tests in this lab.

## Objectives
You will be able to:
* Use built-in Python functions
* Use comparison operators to compare objects
* Use logical operators to incorporate multiple conditions
* Use identity operators to confirm the identity of an object


## Instructions

Let's start by using some built-in functions and methods. Employ the appropriate functions and methods to get the intended result.


```python
# Desired output: "HELLO, THERE"
yell_hello = "hello, there" 
yell_hello
```


```python
# Desired output: "psst, hey"
whisper_hey = "PSST, HEY" 
whisper_hey
```


```python
# Desired output: "Learn. Love. Code"
flatiron_mantra = "LEARN. LOVE. CODE." 
flatiron_mantra
```


```python
# Desired output: str
type_string = "i'm a string" 
type_string
```


```python
# Desired output: list
type_list = ["i'm", "a", "list"] 
type_list
```


```python
# Desired output: 3
lenght_of_list = ["i'm", "a", "list"] 
lenght_of_list
```


```python
# Desired output: "list"
longest_word_in_list = ["i'm", "a", "list"]
longest_word_in_list
```


```python
# Desired output: 1
smallest_number = [1, 3, 4, 78]
smallest_number
```


```python
# Desired output: 11
sum_of_numbers = [1, 2, 3, 5]
sum_of_numbers
```

Uncomment the code in each cell as you start working on them. For example, when you begin working on the first cell, remove `#` at the start of each line.  

> **Note:** The `cmd+?` keyboard shortcut comments or uncomments a given line of code!

Replace `[COMPARISON]`, with the correct comparison operator to get the desired output, which you will find as a comment at the end of each line. See the example below.

```python
# boolean_compare = False [COMPARISON] True # True 
=> boolean_compare = False != True # True
OR
=> boolean_compare = False != True
```

Once uncommented, you can check the output to see if your comparisons match the answers provided in the ending comments.

> **Remember** the comparison operators are: `==`, `!=`, `<`, `>`, `<=`, `>=`


```python
# boolean_compare = True [COMPARISON] True # False
# boolean_compare2 = False [COMPARISON] True # False
# print(boolean_compare, boolean_compare2)
```


```python
# number_compare = 10 [COMPARISON] 10 # True
# number_compare2 = -20 [COMPARISON] 30 # True
# number_compare3 = 4 [COMPARISON] 5 # False
# print(number_compare, number_compare2, number_compare3)
```


```python
# string_compare = "stacy" [COMPARISON] "STACY" # True
# string_compare2 = "hey i love python!" [COMPARISON] "hi love python" # False
# string_compare3 = "this string is bigger than the other" [COMPARISON] "that is true" # True
# print(string_compare, string_compare2, string_compare3)
```

In the next section, do not use either `==` or `!=` operators


```python
# list_compare = [0,0,0,0] [COMPARISON] [0,0,0] # True
# list_compare2 = [1,0,0] [COMPARISON] [0,0,0] # True
# list_compare3 = [0,0,0] [COMPARISON] [0,0,3] # False
# list_compare4 = [0,0,3,0] [COMPARISON] [0,0,3] # True
# list_compare5 = [0,0,4,0] [COMPARISON] [0,0,3] # False
# print(list_compare, list_compare2, list_compare3, list_compare4, list_compare5)
```

### Practicing Identity and Logical Operators

In this next section, use the identity and logical operators to get the desired output as you did in the examples above using the comparison operators.

> **Remember** the **logical operators** are `and`, `or`, & `not`; and the **identity operators** are `is` & `is not`

Use logical opertors for this section


```python
# logical_compare = 2 [COMPARISON] [] # []
# logical_compare2 = [COMPARISON] [] # True
# logical_compare3 = 0 [COMPARISON] [] # 0
# logical_compare4 = True [COMPARISON] 2 # 2
# logical_compare5 = 2 [COMPARISON] 3 # 2
# logical_compare6 = [COMPARISON] True # False
# logical_compare7 = False [COMPARISON] 2 # False
# print(logical_compare, logical_compare2, logical_compare3, logical_compare4,
#       logical_compare5, logical_compare6, logical_compare7)
```

Use identity opertors for this section


```python
# a = []
# b = a
# identity_compare = {} [COMPARISON] {} # False
# identity_compare2 = a [COMPARISON] b # True
# identity_compare3 = b [COMPARISON] [] # True
# identity_compare4 = 9 [COMPARISON] 10 # True
# identity_compare5 = "Same" [COMPARISON] "Same" # False
# identity_compare6 = [1,3,4] [COMPARISON] [1,2,3] # False
# print(identity_compare, identity_compare2, identity_compare3,
#       identity_compare4, identity_compare5, identity_compare6)
```

## Summary
Great work! After all that, there's nothing we can't compare. Well, I guess apples and oranges might still be off the table. We practiced using comparison, logical, and identity operators in Python to compare elements of the same and different datatypes and/or values. Going forward, there will be plenty of instances where we will need to compare elements. So, it is important to have a good understanding of how each of these operators works. Don't worry, as with all concepts in programming, the more we work with something the better we understand it. 
