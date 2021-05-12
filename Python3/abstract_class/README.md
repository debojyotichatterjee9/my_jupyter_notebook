### Problem Statement:

Given a Book class and a Solution class, write a MyBook class that does the following:

* Inherits from Book
* Has a parameterized constructor taking these  parameters:
    1. string ***title***
    2. string ***author***
    3. int ***price***
* Implements the Book class' ***abstract display()*** method so it prints these  lines:
    1. Title:, a space, and then the current instance's .
    2. Author:, a space, and then the current instance's .
    3. Price, a space, and then the current instance's .

**Note:** Because these classes are being written in the same file, you must not use an access modifier (e.g.: public ) when declaring MyBook or your code will not execute.

**Input Format**

You are not responsible for reading any input from stdin. The Solution class creates a Book object and calls the MyBook class constructor (passing it the necessary arguments). It then calls the display method on the Book object.

**Output Format**

The  ***display()*** method should print and label the respective ***title***, ***author***, and ***price*** of the _MyBook_ object's instance (with each value on its own line) like so:

```bash
Title: $title
Author: $author
Price: $price
```
**Note**: The ***$*** is prepended to variable names to indicate they are placeholders for variables.