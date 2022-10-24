# Reading

## Java Basics

### Variables

Probably should read the what is an object article as im not sure what a "field" is exactly, but it sounds like a variable declared in a class

- instance var (non-static **field**): a var that belongs to a class with a value unique to that class instance.
- class var (static **field**): a var that belongs to a class with a value that is the same across all instances. use `final` keyword to indicate this value will never change. will it throw an error if you try to change it?
- local var: a variable that exsists entirely within a method.
- parameter: var declaration as argument for a method.

so fields are variables for classes and plain old variables are for methods?

### Naming Variables

- common sense stuff: name it clearly, lowercase or camelcase, no reserved words
- if it's a const: all caps, words separated by underscore
- you can use the dollar sign but don't!

### Data Types

- statically typed: variables must be declared with name and type before use
- strings are objects not primitives. they are immutable.
- you can use underscores *between* numbers to improve readability `123_456_7890`

### Arrays

- fixed number of values and only of one type. starts at 0.
- declaration similar to standard with addition of `[]` after type declaration (technically it could go after the name too, but do not)

### Operators

- all look much the same as I'm used to
- except for bitwise stuff, idk what that is. another time.

### Expressions

- pemdas is not respected, must use parens to make order explicit

### Control Flow

- this all looks quite familiar as well
- maybe do while is the newest where the while check is at the bottom. wonder what a good usecase for this is.

## Questions

1. What does “strong typed” mean?

- basically that your program will throw an error if you try to intermix your data types. pass the wrong type into a method, add an int and a string, stuff like that.
- in java does any auto conversion happen at all? can you add an int and a float? would that result in a float or an error?
- what is the exact relationship between static and strong typed? can you have one without the other?

1. Explain to a non-technical friend the difference in how compilation works in Java and JavaScript.

- java has a proofreader where as javascript is more "doing it live". java, before actually running any code, checks out what you wrote and makes sure its all copacetic. Only then does it start runnning your code. JS on the other hand does this line by line: checks a line, looks good, runs that line, checks the next, runs it, and so on.
