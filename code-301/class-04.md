# Reading

## React Docs - Forms

What is a ‘Controlled Component’?

- an HTML input element whose value is controlled by react state.

Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

- as soon as they enter them because their display value is read from state.

How do we target what the user is entering if we have an event handler on an input field?

- event.target.value? same as normal, looks like

## The Conditional (Ternary) Operator Explained

Why would we use a ternary operator?

- much more concise for simple true/false if/else statement

Rewrite the following statement using a ternary statement:

```js
if(x===y){
  console.log(true);
} else {
  console.log(false);
}

x===y ? console.log(true) : console.log(false)
```

## Bookmark and Review

React Bootstrap - Forms

React Docs - conditional rendering