###### class-07 reading notes


## Reading

[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

1. Explain why we need domain modeling.
   - to aid in understanding problems and their relevant factors
   - can be used as point of mutual understanding between technical and business teams

[HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

1. Why should tables not be used for page layouts?
   - challenging to screenreaders navigating your page
   - oodles of tags make it challenging for humans to read your HTML
   - not really supported by default table styling (but if we reset.css eveything anyway...)

1. List and describe 3 different semantic HTML elements used in an HTML `<table>`.
   - `<tr>` table row designates a new row to be filled with:
   - `<td>` table data, containers for data, contained by `<tr>` like: `<li>` inside of `<ol>`
   - `<th>` table header, used in place of `<td>`, works the same way but has styling to make it stand out.

[Introducing Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)

1. What is a constructor and what are some advantages to using it?
   - it's basically a function to initialize an object from a template.
   - it allows you to use objects to their full potential: data containers with differing values but identical structures/methods.
   - easily update an object from one place rather than on each indiviual iteration of that object.
1. How does the term `this` differ when used in an object literal versus when used in a constructor?
   - in an object literal `this` refered to the object literal. In a constructor `this` refers to the object that the constructor creates?

[Object Prototypes Using A Constructor](https://ui.dev/beginners-guide-to-javascript-prototype)

1. Explain prototypes and inheritance via an analogy from your previous work experience.
   - *NOTE: This is a very common front end developer interview question*
   - good god
   - sometimes, at the cheese counter a customer would make a `verySpecificRequest(flavor, region, jeNeSaisQuoi)` and you, lacking that funcionality, would turn to your manager, like you but with more features, who could fufil that request.
   - cheesemonger.prototype functions might include `guessWeight(weight, cheese)` `cutCheese(cheese)` `paperWrap(cutPiece)`
   - man I really maybe 12% understand that last link and am 1% capable of making up analogies about it.

## Bookmark and Review

[HTML Table Advanced Features and Accessibility](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)

## Things to know more about

- that whole last article needs a reread and then another, maybe I'm just tired.
- how can I extract tech relevence from a specialty retail gig?
- can I use Js to write a function that makes HTML tables so I don't have to?
- Salmon Cookies is domain modeling, right?
