###### class-06 reading

JS still blossoming, we continue to learn how to make more and more complicated structures to improve our code. AND JS is converging with our webdev learning, through the DOM. Excited to see where we go with this stuff.

## Reading

[JavaScript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics){:target="_blank"}

1. How would you describe an object to a non-technical friend you grew up with?
    - so, in programming, an object is basically a representation of a thing. If you were turning a dog into an object it would have some attributes like name, age, color, favorite-toy, and an isGoodDog boolean. It would also have some functions it could perform like sit, stay, roll-over and bark. You can use this dog object to represent any dog you want!
1. What are some advantages to creating object literals?
    - simpler function declaration
    - keeps some data together but easier to wokr with than an array
1. How do objects differ from arrays?
    - objects hold items as k:v pairs where an array holds items in a particular order
      - strings to values vs numbers to values
    - objects hold functions that you can call from that object.
    - an array is an object itself?
1. Give an example for when you would need to use bracket notation to access an object's property instead of dot notation.
    - if that particular object property was created at runtime then it would be inaccesable with dot notation
    - you can pass an expression into bracket notation.
1. Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?

```js
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```

    -`this` refers to `this particular incarnation of this object template`

[Introduction To The DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction){:target="_blank"}

1. What is the DOM?
    - Document Object Model
    - a programming interface for web documents, like an API?
    - turns a webpage into an object that can be changed and interacted with
1. Briefly describe the relationship between the DOM and JavaScript.
    - the DOM is an interface that JS can use to interact with HTML.

## Bookmark and Review

[Understanding the problem domain is the hardest part of programming](http://simpleprogrammer.com/2013/07/15/understanding-the-problem-domain-is-the-hardest-part-of-programming){:target=”_blank”}

[What’s the difference between primitive values and object references in JavaScript?](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b){:target="_blank"}

### I want to know more about

- Is an array an object or is an object an array? Or neither? Or both???
- when you use backticks and `${}` to make a fancy string, is that an object literal too?
- should I use objects on my guessing game page to manage questions?
