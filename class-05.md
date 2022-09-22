# Reading

## React Docs - Thinking in React

What is the single responsibility principle and how does it apply to components?

- the single responsibility principle means that your thing is responsible for only one piece of functionality. For a component it means that your component only renders one thing to the page and only deals with functionality that occurs through its component.

What does it mean to build a ‘static’ version of your application?

- a fancy mockup, an application that has all it's ducks in a row but you can't interact with those ducks.

Once you have a static application, what do you need to add?

- interactivity? state?

What are the three questions you can ask to determine if something is state?

- is it not passed in from as props?
- does it change over time?
- is it's value independent of props or other state?

How can you identify where state needs to live?

- find the things that renders based on state and put state in their common owner component, unless it seems too crazy, then make a dummy middleman component that is just for holding state

## Higher-Order Functions

What is a “higher-order function”?

- a function that needs other functions to operate, either passed in or returned

Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

- returns a function that can compare the originally input value with a new value?

Explain how either map or reduce operates, with regards to higher-order functions.

- map is a higher order function because it takes a function as an argument. That passed in function is then run once for every element in the mapped array with that element passed in as an argument to the passed in fucntion.
