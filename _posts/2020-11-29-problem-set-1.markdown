---
layout: post
title:  "Problem Set 1"
date:   2020-11-29 16:20:57 +0800
categories: jekyll update
---

### Problem 1 ###
Write a simple printing function which:
1. Takes in a person's name
2. Takes in a person's height in cm
3. Prints out a message using the above 2 pieces of information.

```
What is your name?
> Calvin
What is your height?
> 170
My name is Calvin and I am 170cm tall.
```

### Problem 2 ###
Write a function which:
1. Takes in an integer
2. Prints out a message accordingly.

```
# Zero files
How many files need to be transferred?
> 0
No files need to be transferred. End of operation.

# >0 files
How many files need to be transferred?
> 5
Transferring file 1 of 5.
Transferring file 2 of 5.
Transferring file 3 of 5.
Transferring file 4 of 5.
Transferring file 5 of 5.
End of operation.
```

### Problem 3 ###
Write a simple calculator function that:
1. Prompts the user for a choice of an operation (add, subtract, multiple, divide)
2. Takes in exactly two parameters to perform the chosen operation
3. Returns the result accordingly.

*** Notes ***
* Add and multiply operations may only utilise the `+` operator. Use of the `*` operator is not allowed.
* Subtract and divide operatins may only utilise the `-` operator. Use of the `/` and `%` operators is not allowed.
* Beginners can assume inputs will also be valid responses, and operands will only be positive integers.
* Advanced learners may explore input validation and also determine how to deal with negative integer

```
What operation would you like to perform?
1: Add
2: Subtract
3: Multiply
4: Divide

# Add is chosen
> 1
Input first operand:
> 10
Input second operand:
> 2
Result: 12


# Subtract is chosen
> 2
Input first operand:
> 10
Input second operand:
> 2
Result: 8


# Multiply is chosen
> 3
Input first operand:
> 10
Input second operand:
> 2
Result: 20


# Divide is chosen (No remainder)
> 4
Input first operand:
> 10
Input second operand:
> 2
Result: 5

# Divide is chosen (With remainder)
> 4
Input first operand:
> 10
Input second operand:
> 3
Result: 3 with remainder 1
```


Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
