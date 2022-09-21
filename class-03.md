# Reading

## React Docs - lists and keys

What does .map() return?

- an array

If I want to loop through an array and display each value in JSX, how do I do that in React?

- use .map() to turn each item in the original array into an element that holds the original data, render that new array of elements.

Each list item needs a unique ____.

- key, that ideally is a lengthy string of some sort.

What is the purpose of a key?

- unique id used by react to keep track of what is changing on the page

## The Spread Operator

What is the spread operator?

- `...` magic dots used to 'spread' an array out into *serparate elements sort of?*

List 4 things that the spread operator can do.  

- separate an array into arguments for passing into a func
- copy arrays
- combine arrays/objects
- add to state in react

Give an example of using the spread operator to combine two arrays.

```js
let arrOne = [1,2,3]
let arrTwo = [4,5]
let bigArr = [...arrone, ...arrTwo]
```

Give an example of using the spread operator to add a new item to an array.

```js
let arrMatey = ['blackbeard','roberts','crunch']
let arrYaReadyKids = ['painty', ...arrMatey, 'patchy']
```

Give an example of using the spread operator to combine two objects into one.

```js
let objBob = {name: 'bob', hair: false}
let objDog = {goodBoy: false, rollOver: () =>{console.log('borf borf')}}
let objBobDog = {...objBob,...objDog}
```

## How to Pass Functions Between Components

In the video, what is the first step that the developer does to pass functions between components?

- create the function at the same level as the state to be changed?

In your own words, what does the increment function do?

- there are two different methods called increment lol
- loops through an array of people objects, looking for a particular person, and when it finds that person, their count is incremented. then it updates state to reflect this change. recreating the entire collection of people for the sole purpose of increasing one value on one person by one seems mega inefficient...

How can you pass a method from a parent component into a child component?

- pass it as a prop, very simple! `<Thing method={this.method} />`

How does the child component invoke a method that was passed to it from a parent component?

- call it via props? `this.props.method()`

### Bookmark and Review

React Tutorial through ‘Declaring a Winner’
React Docs - Lifting State Up
