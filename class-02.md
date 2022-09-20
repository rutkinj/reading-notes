# Reading

## React lifecycle

Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
    - render
What is the very first thing to happen in the lifecycle of React?
    - constructor in mounting phase
Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
    - constructor
    - render
    - react updates
    - componentDidMount
    - componentWillUnmount
What does componentDidMount do?
    - seems like nothing on its own? invokes after a successful mounting to the DOM. can be used to start network requests?

## React State Vs Props

What types of things can you pass in the props?
    - seems like anything basically? the same sort of things you would pass into a function argument
What is the big difference between props and state?
    - props are passed in, state is internally handled
When do we re-render our application?
    - when state is altered (or a prop is passed in?)
What are some examples of things that we could store in state?
    - current score in a game, information in a form element.
    