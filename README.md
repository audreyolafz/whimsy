# Whimsy ✨
Welcome to Whimsy, a compiler created in Java. Say goodbye to semicolons, curly brackets, and multiline pieces of code to do simple things.
Buckle up, all you need is a `.txt` file to write in Whimsy and `Compiler.java` :) 

## Creating Variables
There are clear indicators around each part of a variable. 
### Text (Strings)
To set a text variable, first let the compiler know it is going to be text with `t`. Then have opening and closing square brackets `[]` around the variable name. Put an `=` sign, and finally put the text you want to store between quotations. 
```
 t <hiVar> = "hi"
```
This piece of code stores the text `"hi"` in a variable called `hiVar`.

### Numbers (Integers)
To create a variable storing a number, use `n` first to indicate that it's a number. Put the variable name between opening and closing square brackets `[]` and equal signs following it. Then insert the integer value you would like to store.
```
n [zero] = 0
``` 
Here `0` is stored in the variable aptly named `zero`.

## User input
To ask the user to input some text, simply run the `ask()` command.
```
ask("Enter your name: ")
```

## Math
### Addition
Just include a `+` between two numbers you would like to add. The order of the numbers does not matter. <br>
```
2 + 3
```
The output should be `5`.

### Subtraction
Similar to subtraction, just include a `-` to subtract two numbers. <br>
```
77-13
```
The output should be `64`.

### Multiplication
To multiply, put an `*` between the two values. The order does not matter. <br>
```
4*5
```
The output should be `20`.

### Division
Dividing just requires a `/` between the two numbers. Keep in mind the result will always be an integer, so the decimal places are cut off. <br>
```
120/10
```
The output should be `12`.
```
12/10
```
The output should be `1`.

### Remainder
To find the remainder when dividing two numbers, simply add a `%` symbol.
```
67%10
```
The output should be `7`, since 67 goes into 10 a total of 6 times, with 7 remaining.

## Conditions

## Loops

## Comments
To spice things up, comments now appear in the form of `$$$`. <br>
Here is an example of a comment: <br>
```
$$$ I won't run, this is just a comment
```
