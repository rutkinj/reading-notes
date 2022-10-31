# Reading

## Interface

- used in class creation via `implements` keyword.
- establishes methods, commonly empty, that class is then required to have.
- if they are not implemented, the code will not compile.

## Static

- used to make a class member available without creating a class instance
- `Math` is a good example, you can just call out `Math.random()` but you never have to make a local instance of the math class
- static variables share the same value across all object instances.

## Singleton

- design pattern to restrict a class to a single object instance.
- use cases? I have done this before in Unity, I think it was for scene management? One scene manager that lives across all scene loading.
- also at the bottom it says basically never do this, lol, that was the same thing I was told while learning it in unity.
- if this the mentality then why does it keep coming up??

## Questions

What is the difference between an Object and a Class in Java?

- A class lays the groundwork for an object to be created. A class determines the basic layout and structure of an object crated from that class.

What is a Design Pattern? Describe one or two with analogies from your previous work experience.

- I think you can describe it as a language agnostic feature implementation, a piece of functionality that is built out of logic rather than language features? By this definition are most data structures also design patterns? Based on fridays lab, a linked list feels like it definitely fits in this category. I think I could recreate a linked list in java, c#, python, and maybe js too.

Static methods are also called what? Why?

- class methods, because they belong to the class rather than the object that class creates. Do they additionally belong to the object that class the creates?
