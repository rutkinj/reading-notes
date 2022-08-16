###### class-03 reading notes

In this reading we open our css skills up to more structured web pages. Learn about lists in HTML, I'm sure we'll use those at least a little. This is a meaty reading for JS though!! Loops and if statements are where programming really starts to feel like programming.

### [Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML){:target="_blank"}

[Ordered](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol){:target="_blank"} and [Unordered](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul){:target="_blank"} lists.

1. When should you use an `unordered list` in your HTML document?
    - anytime you need to list something where order is irrelevant. ex: a list of ingredients.
1. How do you change the `bullet style` of unordered list items?
    - with the list-style-type CSS property `<ul style="list-style-type: circle">`
1. When should you use an `ordered list` vs an `unorder list` in your HTML document?
    - anytime that order matters. ex: organize the steps of a recipe.
1. Describe two ways you can change the numbers on `list items` provided by an `ordered list`?
    - reversed: like it sounds, numbers items from high to low. set with a boolean
    - start: determines the number to start at. set with a number as a string *does it work with a proper number?*

### [Learn CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS){:target="_blank"}

[The Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model){:target="_blank"}.

1. Describe the CSS properties of `margin` and `padding` as characters in a story. What is their role in a story titled: "The Box Model"?
    > Once there were two brothers, Margin and Padding. These brothers could grow to incredible sizes and push stuff around as they pleased (usually.) One day, Padding found some Content and covetously surrounded it. But this wasn't enough for Padding, who then got a Border to put around himself. Margin, watching all this happen, realized that his brother might need some space, so stretched himself around the Border to further insulate Padding from the outside world. And that, children, is how the Box Model came to be.
1. List and describe the **four** parts of an HTML elements box as referred to by the `box model`.
    1. Content box- this is where content is displayed. It is the innermost box.
    1. Padding box- this box surrounds the content. Lives between conent and border.
    1. Border box- this is a box that basically outlines the padding box.
    1. margin box- outermost box. this is the space between this element and other elements.

### [Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript){:target="_blank"}

[Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays){:target="_blank"}.
[Operators and Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators){:target="_blank"}.
[Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals){:target="_blank"}.
[Loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code){:target="_blank"}.

1. What `data types` can you store inside of an `Array`?
    - seems like basically anything! strings, numbers, objects, arrays. even bools but I can't really think of a good usecase for a loose bool...
1. Is the `people` array a valid JavaScript array?  If so, how can I access the values stored? If not, why?
    - yes it is. it's an array of arrays.
    - if you wanted to access the entire first list you grab it at `people[0]`
    - if you wanted to access just 'librarian' it would be `people[0][2]`

    ```javascript
    const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
    ```

1. List **five** shorthand operators for assignment in javascript and describe what they do.
    1. `a += b` a classic! add two things together, rather, add a thing to the first thing
    1. `a /= b` divide the first thing by the second thing
    1. `a %= b` modulo. here `a` is divided by `b` and then the remainder is assigned to `a`
    1. `a << b` left shift assignment. `a` as binary is shifted over `b` spaces to the left. I'm out of my depth here and can't imagine a use case...
    1. `a &&= b` logical and. This is weird one but less weird. if `a` has any value (truthy) then `a` is assigned the value of `b`
1. Read the code below and evaluate the last `expression` and explain what the result would be and why.
    - before I just run it, I think it will either return an error or maybe `'10dog'`
    - so it was `'10dog'`, based on that I can infer that `false == 0` and `10` gets converted to a string
    - changing false to true results in `'11dog'`

    ```javascript
    let a = 10;
    let b = 'dog';
    let c = false;

    // evaluate this
    (a + c) + b;
    ```

1. Describe a real world example of when a conditional statement should be used in a JavaScript program.
    - the one we've come across in class is a non-answer to a `prompt()`. you're expecting a string, so you do some string operation, but if no answer was given then you've got a `null` not a string and you'll get an error. You can use a conditional to check if the returned value was `null` and run the `prompt()` again. Or at least avoid an error by skipping the string operation.
1. Give an example of when a `Loop` is useful in JavaScript.
    - loops are extremely useful! want to write a program that says hello to a group of people? loop through a list of their names and plug each value into a message. Make a file for every reading assignment you'll have at code fellows? use a for loop to make a certain number of files, and even give them appropriate names maybe!

## Things I want to know more about

- there were some majorly weird asasignment operators that I'm curious about, but probably I'll just have to wait on those.
- CSS boxes and margins and things like that. Mostly I think I just need practice, fiddling with different properties and noting the results. 
