###### class-02 reading notes

This reading represents the next step in web development learning. CSS is introduced so we can start to style our webpages. Several key concepts are introduced in JS that we can use to make programs that do things on their own (or at least when certain criteria are met).

## *Learn HTML*

1. Why is it important to use semantic elements in our HTML?
    - Semantic elements give SEO's another place to look for keywords. They can be picked up by screenreaders to aid in page navigation. They are also easier for humans to read as code.
1. How many levels of headings are there in HTML?
    - Six. `h1` is the largest and `h6` is even smaller than regular text!
1. What are some uses for the `<sup>` and `<sub>` elements?
    - `<sup>` is superscript and can be used to show exponents in math problems.
    - `<sub>` is subscript, this is for writing out chemical formulas
1. When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?
    - The `title` attribute. Do you have anyway to access that with a screenreader?

## *Learn CSS*

1. What are ways we can apply CSS to our HTML?
    - You can make a `<style>` section in your `<head>`.
    - You can add them inline `<p style="color:blue">`.
    - or you can have an external stylesheet that you reference in your `<head>`.
1. Why should we avoid using inline styles?
    - they your code hard to edit. If you were using inline styling and had to change the style of your all your `<p>`'s, it would take ages. With a `<style>` section in the `<head>`, or an external stylesheet, you only need to make edits in one place.
1. Review the block of code below and answer the following questions:
    1. What is representing the selector?
        - `<h2>`
    1. Which components are the CSS declarations?
        - `color: black;` & `padding: 5px`
    1. Which components are considered properties?
        - color and padding, their conterparts are values

```css
   h2 {
     color: black;
     padding: 5px;
   }
```

- *selectors in CSS favor specificty*

## *Learn JS*

1. What data type is a sequence of text enclosed in single quote marks?
    - that is a string. *does js care about double vs single quotes?*
1. List 4 types of JavaScript operators.
    - `=` assignment `myNum = 5`
    - `===` equality, returns a bool `myNum === 6`
    - `!` not, flips a bool `!isCool`
    - `+` add, used to add numbers or combine strings `"Good" + "bye"`
1. Describe a real world Problem you could solve with a Function.
    - You could write a function to help you calculate a tip.
 
  ```js
  tipCalulator(total, tipPercent){
    if (tipPercent < 20){
      tipPercent = 20;
    }
    let tip = total * (tipPercent * 0.01);
    return tip;
  }
```

1. An if statement checks a ______ and if it evaluates to _______, then the code block will execute.
    - condition
    - true
1. What is the use of an `else if`?
    - It's used as a secondary if statement that gets checked only if the first statement evaluates to false.
1. List 3 different types of comparison operators.
    - `!==` not equal to `5 !== 1`
    - `>` greater than `5 > 2`
    - `<=` less than or equal to `2 <= 2`
1. What is the difference between the logical operator `&&` and `||`?
    - `&&` means AND
    - `||` mean OR

## Things I want to know more about

- can you access the `title` attribute with a screenreader? or any element that you need to hover over?
- in a function, how do you give an argument a default value?
