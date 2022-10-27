# 1. Assignment operations in JS
An assignment operator assigns a value to its left operand based on the value of its right operand. 

|Name|	Shorthand operator|	Meaning|
|-----|------------------|-------|
|Assignment|	x = f()	|x = f()|
|Addition assignment|	x += f()|	x = x + f()|
|Subtraction assignment	||x -= f()|	x = x - f()|
|Multiplication assignment|	x *= f()|	x = x * f()|
|Division assignment|	x /= f()|	x = x / f()|
|Remainder assignment|	x %= f()|	x = x % f()|

# The increment and decrement operations.
### The increment operator (++)
increments its operand by 1; that is, it adds 1 to the existing value. 
### The decrement operator (--) 
that decrements a variable's value by 1. That is, it subtracts 1 from the value.

JavaScript provides these operators since incrementing and decrementing by 1 are such commonplace operations.

There are two forms of ++: one that comes before the variable name (**the pre-increment operator** ), and one that comes after (**the post-increment operator**). Both increment the variable, but they differ in what gets returned by the expression. The pre-increment form returns the new value of the variable, while the post-increment form returns the previous value of the variable.