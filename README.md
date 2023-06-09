# Whimsy ✨
Welcome to Whimsy, a compiler created in Java. Say goodbye to semicolons, curly brackets, and multiline pieces of code to do simple things. <br>
Buckle up, all you need is a `.txt` file to write in Whimsy, `Main.java`, and `Compiler.java` :) 

## Printing Statements
Forget `print()`, `console.log()`, `System.out.println()`, and all the other ways to do the simple yet essential task of displaying some data on the command-line. <br>
Say hello to `display()`. Just put what you want to print in between the parentheses.
```
display("Hello world.")
display(30)
```
`Hello world.` and `30` will be displayed on separate lines.
 
## Creating Variables
Variables are for storing values to use later. It can be a value that changes throughout the program, such as a random number, or number that stays fixed, such as your birthdate. There are clear indicators around each part of a variable. 
### Text (Strings)
To set a text variable, first let the compiler know it is going to be text with `t`. Then have opening and closing square brackets `[]` around the variable name. Put an `=` sign, and finally put the text you want to store between quotations. 
```
 t <hiVar> = "hi"
 t <heyVar> = "hey"
```
This piece of code stores the text `"hi"` in a variable called `hiVar` and `"hey"` in a variable called `heyVar`.

### Numbers (Integers)
To create a variable storing a number, use `n` first to indicate that it's a number. Put the variable name between opening and closing square brackets `[]` and equal signs following it. Then insert the integer value you would like to store.
```
n [zero] = 0
``` 
Here `0` is stored in the variable aptly titled `zero`.

## User input
User inputs can be useful when you want to use it to manipulate another statement. To ask the user to input something, simply run the `ask()` command.
```
ask("Enter your name: ")
```

## Math
Currently only integer values are supported for all mathematical operations.
### Addition
Just include a `+` between two numbers you would like to add. The order of the numbers does not matter. <br>
```
2 + 3
```
The output should be `5`.

### Subtraction
Similar to subtraction, just include a `-` to subtract two numbers. <br>
```
77 - 13
```
The output should be `64`.

### Multiplication
To multiply, put an `*` between the two values. The order does not matter. <br>
```
4 * 5
```
The output should be `20`.

### Division
Dividing just requires a `/` between the two numbers. Keep in mind the result will always be an integer, so the decimal places are cut off. <br>
```
120 / 10
```
The output should be `12`.
```
12 / 10
```
The output should be `1`.

### Remainder
To find the remainder when dividing two numbers, simply add a `%` symbol.
```
67 % 10
```
The output should be `7`, since 67 goes into 10 a total of 6 times, with 7 remaining.

## Conditions
Conditions allow a certain piece of code to run depending on other variables. Currently only `if` conditions are supported. <br>
Instead of `if` statements, we have `logic()` statements, because that is what `if` statements really are.
```
logic(3>=3): display("3 is greater than or equal to 3")
logic(5<3): display("5 is less than 3")
logic(hiVar==heyVar)
```
Since 3 is indeed >= to 3, the program outputs `It's true`. <br>
5 is not less than 3, so it will not print anything.
`hiVar` and `heyVar` contain different values, so it will not display anything.

## Loops
If you want to run a piece of code multiple times, use the `loop()` function.
Simply indicate how many times you want to loop to run within `loop()`.
```
loop(5): display("I'm printing this 5 times")
```
This piece of code will output: <br>
`I'm printing this 5 times` <br>
`I'm printing this 5 times` <br>
`I'm printing this 5 times` <br>
`I'm printing this 5 times` <br>
`I'm printing this 5 times` <br>

## Comments
Comments are perfect for text only for human eyes, or code that doesn't run. They are quite helpful when sharing code with other programmers so they can quickly understand how your code works. To spice things up, comments now appear in the form of `$$$`. <br>
Here is an example of a comment:
```
$$$ I won't run, this is just a comment
```

### Errors
Accidently mistyped Whimsy's syntax? Wrote something that will go out of bounds? Fear not! The command-line will tell you which piece of code doesn't compile.
```
fakeMethod()
```
`"Error: fakeMethod()" doesn't compile.` will be displayed.
