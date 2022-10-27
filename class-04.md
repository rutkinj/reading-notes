# Reading

## Object

- all objects have state/fields and behavior/methods
- methods only affect state
- data encapsulation: private state only interactable via local object methods
- modularity: objects are independent and self contained. Easily moveable, easy maintenance.

## Classes

- classes are blueprints for creating objects
- classes can inherit the structure of a parent class but can have additional fields/ methods
- class can only have one parent
- a class can implement an interface, but we haven't learned that yet.
- I still don't really get the point of making a var private if we then make getters and setters
  - getters sure, but setters?? i guess it's to restrict exactly how you can interact with that field
- constuctors look like method declarations but have no return type
- a class can have multiple constructors. differentiated by what is passed in?
- arbitrary num args: `varType... varargs` ... says any number of arguments of this type, varargs treated as array
  - could it take an array that contains the same type specificied?
- args are passed by value and are unchanged by method actions. the accception being public fields on a passed in object?

## Numbers

- binary is in base 2
- hexadecimal is base 16
  - 0-9 are numerical
  - 10-15 are A-F
  - 16 is the reset so it shows as 10 where 1_ is 16 and 0 is 0;
  - what is the point of hexidecimal???
