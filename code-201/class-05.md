###### class-05 reading notes

Below you will find some reading material, code samples, and some additional resources that support the topic for this class and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

### [HTML Media](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding){:target="_blank"}

[Using Images In HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML){:target="_blank"}.
Read [Common Image Types](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types){:target="_blank"} and [Choosing Image Formats](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types#choosing_an_image_format){:target="_blank"}.

1. What is a real world use case for the `alt` attribute being used in a website?
    - Read by a screenreader to describe an image.
    - You've got a problem and your html can't find your image, dislaying your `alt` as a backup.
1. How can you improve accessibility of images in an HTML document?
    - Provide an `alt` that is nice and descriptive.
    - Probably don't use a `title` as they are harder to access, at least don't use one in place of an `alt`.
    - Remember that `<figcaption>` is *about* the image. `alt` *is* the image in text form.
1. Provide an example of when the `figure` element would be useful in an HTML document.
    - `figure` is good for keeping images and their captions together in a neat container.
1. Describe the difference between a `gif` image and an `svg` image, pretend you are explaining to an elder in your community.
    - a `gif` is like a tiny and usually short movie with no sound.
    - an `svg` is an image that is very scalable, like a projector slide: you can look at the slide and see the image, but you can also put it in the projector to see it much larger but at a similar quality.
1. What image type would you use to display a screenshot on your website and why?
    - `jpeg` but probably `png`, it's just my preference w/ greater clarity and transparency capabilities.
    - `jpeg` would maybe be most logical: quality loss probably wouldn't be so damaging to a screenshot. and no need for transparency.

### [Learn CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS){:target="_blank"}

[Using Color in CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color){:target="_blank"}.
[Styling HTML Text Elements](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals){:target="_blank"}

1. Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.
    - so first off, everything on a webpage is in a box, probably there are really *a lot of boxes*. Any text is surrounded by a square box. That box is the background and will be filled via `background-color`. And the text, or the content, is the foreground and gets colored via `color`.
1. Your friend asks you to give his colorless blog website a touch up.  How would you use color to give his blog some character?
    <!-- - I would collaborate with them on a color scheme with a very reasonable color combo for blog text and blog background, good contrast. -->
1. What should you consider when choosing fonts for an HTML document?
    - availability. 
1. What do `font-size`, `font-weight`, and `font-style` do to HTML text elements?
    - `font-size` is exactly as it sounds, equivilent to changing your text size in Word.
    - `font-weight` is the thickness of the font, think bold
    - `font-style` is for things like italics and that is the only one i recognize.
1. Describe two ways you could add spacing around the characters displayed in an `h1` element.

If you have any questions or comments  from the readings, post them in the class Slack channel!

### Additional

- does foreground in html really only refer to text?
- I see inherit, initial, and unset and I want to know how they work, I have some ideas but I wonder about reasonable use cases
- I want to learn about making themes for vsCode. I wonder if there's a theme for beginners that is designed for readablilty and understanding rather than prettiness. Like big ugly color coding so it's painfully, maybe literally, obvious how your code interacts with itself, or like the scope of loops or variables, where your curly braces are, etc. 