###### class-11 reading notes

Grid seems like it will be a big deal. I think my basic frustration with flex box is that I would rather it worked in two dimensions... Famous last words. Responsive images also seem like a good add, my sites would benefit.

## Reading

[Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content){:target="_blank"}

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.
    - sounds like it's kind of gone in a circle. It started with plugins like flash, moved to the internal HTML tag `<video>`, and now we're back to external with embedded videos hosted on sites like youtube.
1. Describe the use of the `src` and `controls` attributes in the `<video>` element.
    - `src` holds the path to your video, work the same as in `<img>`
    - `controls` enables the web browsers native video contols for the user.
1. Why is it important to have **fallback content** inside the `<video>` element?
    - similar to the `alt` attribute in images, displays when the video cannot.This could be a link to your video if the browser being used can't support your embedded video.
1. Write a very short story where `<audio>` and `<video>` are characters.
    - One day, little video was at their grandparents house. Grandpa audio got a hold of video and started blabbin'. "Back in my day," he says, "we didn't have no fancy movin' pictures! Just a play button, same as you, and some sounds, same as you, but ain't no pictures a-wavin' and a flickerin!" While Grandpa audio blabbed on, fully occupied, little video lowered his volume.

[A Complete Guide To Grid](https://css-tricks.com/snippets/css/complete-guide-grid/){:target="_blank"}

1. How does Grid layout differ from Flex?
    - where flex is for a single dimension, flex can handle two!
1. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
    - grid container is where you apply `display: grid`. holds all items in the grid.
    - grid item is a child of the grid container, it looks like they are generic and hold other items which contain content
    - grid lines are the lines that make up the grid, divide area where content lies.

[Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images){:target="_blank"}

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
    - conserve user bandwidth.
1. Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used.
    - `srcset` like `src` but takes in multiple paths and also the width of those images.
    - `sizes` sets the scenario when a different size image should be used. This change has a target screensize and an target image to switch to.
1. How is `srcset` more helpful for responsive images than CSS or JavaScript?
    - html is parsed first so if its in charge of responsive images it just loads the one it knows it needs. if js handled responsive image switching, html would have already loaded all size options before js could pick the right one for the job. Inverse of goal...

<!-- NOTE: "Videos" may not be relevant for every class. Omit this section or any of the sections below if you don't have anything for your students here -->
<!-- ## Videos -->

<!-- [Name of Video](https://linktovideohere){:target="_blank"} -->

<!-- Mix it up! Create the questions with pointed answers, fill in the blank, or opinion/open ended -->
<!-- 1. Question 1
1. Question 2
1. Question 3 -->

## Bookmark and Review

[Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML){:target="_blank"}

> This article is review from Class 05.

[Other Embedding Technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies){:target="_blank"}

## Things to learn more about:

- flexbox froggy was a great help, is there a grid gorilla somewhere out there?
- is there no way to do responsive images in js?
- you can make a table with js but not a responsive image?
