# Reading

## Functional Programming Concepts

What is functional programming?

- programming that avoids use of state, global variables. prefers shallow copies?

What is a pure function and how do we know if something is a pure function?

- a function that performs actions only on what is passed into it with no sideeffects?
- returns something new, does not alter parameters
- above, and also, with the same parameters, the result should be the same everytime (no random)

What are the benefits of a pure function?

- no sideeffects, simpler maintenance on large systems, easier testing

What is immutability?

- not sure how to say this... a things capacity to not be changed or altered?

What is Referential transparency?

- sounds like a variable whos value was determined by a function that was producing the same output when given the same input?
- none of the pictures of code on this website are displaying lol so I don't have much to go on with this one...

Videos
Node JS Tutorial for Beginners #6 - Modules and require()

What is a module?

- another file that holds functions

What does the word ‘require’ do?

- grabs a file at the designated directory and makes its exports available

How do we bring another module into the file the we are working in?

- call require with the relevent file path of the module

What do we have to do to make a module available?

- export relevent functions
