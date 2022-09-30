# Printing - Python Programming
How exactly do we see output from a program in the console?

In order to debug (correct errors) or output something from a program, we need to display it somewhere. Where do we do this?
**In the console!**

First, you need to know how to write a comment inside of a program.
Comments are completely ignored by Python's interpreter, so it's a good place to put notes on what exactly a specific function, per se, can do.

You can make a single-line comment with the hashtag "#"
But if you want to write a lot of comments within the same area, you can use multi-line comments.
However, Python doesn't support multi-line comments. So a workaround is `docstrings`

You can make a docstring by using 6 double-quotes or 6 single-quotes

Here's how to comment:
```python
# This is a comment
# It is completely ignored by Python

'''
This is also a multi-line comment
Python will ignore this also, as it is a `docstring` and not an actual program
'''
```

Here's how to print to the console:
In order to print we need to state the `print()` function call. Whatever we put inside the parenthesis (called `arguments` or `args`) will be displayed inside of our program's console.
```python
# This will print "Hello world!" to the console
print("Hello world!")

# This will print "1" to the console
print("1")
# And so will this
print(1)
# We'll get into that later
```

Try it out!
