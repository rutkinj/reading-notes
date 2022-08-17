###### class-04 reading notes

Continued learning about webpage structuring. Linking is simple but absolutely essential! I see the CSS from this reading really building on the last one. Here's a box and how it works and now *here* is how you can move it around and stick it different places. But again JS is the star, functions are what it's all about!

### [Learn HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML)

[Creating Hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

1. To create a basic link, we wrap text or other content inside what element?
    - `<a/>` this element also needs an attribute to work `href="url/wherever"`
1. The `href` attribute contains what information?
    - the location that you're trying to link to, a website or a location in your local file structure.
1. What are some ways we can ensure links on our pages are accessible to all readers?
    - make the target of the link obvious, keep it short, keep the actual url in the href and don't have 'link' in the link text.
    - if your link starts a download, make sure that's obvious **before** clicking!
    - bad link text: 'click here for a link!'
    - good link text: 'Joe's github profile'

### [CSS Layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout)

[CSS Layout: Normal Flow](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow)
[CSS Layout: Positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning)

1. What is meant by "normal flow"?
    - normal flow refers to how different html elements interact with each other while they've got their default settings (block-level and inline)
1. What are a few differences between `block-level` and `inline` elements?
    - block-level elements give themselves a new line where inline elements live in the line they were created in.
    - block-level elements ahve their size determined by their parent element; inline size is determined by their content.
1. _______ positioning is the default for every html element.
    - static
1. Name a few advantages to using absolute positioning on an element.
    - they exist on a separate plane from other elements, they don't effect and are not affected by other elements
    - their position is still determined by their containing element, so all size and positioning happens relative to the container.
1. What is a key difference between fixed positioning and absolute positioning?
    - fixed positioning works relative to the viewport as opposed to a particular element.

### [Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

[Functions -- Reusable Blocks of Code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions)

1. Describe the difference between a function declaration and a function invocation.
    - declaration starts with the function keyword, declares arguments to be passed in, and establishes what the function does.
    - to invoke the function you simply name it and include any required arguments.

    ```js

    function takeMeTo(location){
      //take to location
    }

    takeMeTo(funkyTown);
    ```

1. What is the difference between a parameter and an argument?
    - from the reading, it seems like difference is in spelling only. they are the same.

### Miscellaneous

[6 Reasons for Pair Programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)

1. Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.
    - learning from fellow students- This one has already helped me! Even just looking at someone elses code, you can learn new tricks and approaches. This could only be enriched by working side by side and hearing a persons thought process.
    - work environment readiness- Collaboration is always going to be part of the tech process so might as well get used it ASAP!
