###### class-01 reading notes

## *Getting Started*

__Compose a short poem describing how HTTP sends data between computers.__

> Little old me needs cat pics to see,
>
> But the server won't listen to "Please."
>
> So I use my PC, which sends HTTP,
>
> To handshake and return Siamese.

__Describe how HTML, CSS, and JS files are “parsed” in the browser.__

First parsed is the barebones HTML. While this occurs, any CSS or JS references are requested from the server. Then the CSS and JS are parsed.

__How can you find images to add to a Website?__

Google image search. Be aware of liscening restrictions, set filters Creative Commons.

__How do you create a String vs a Number in JavaScript?__

    let myString = '12';
  
    let myNumber =  12;
  
"let" declares a variable. Variable type is determined by the data you give it. Data in quotes is a string, even if it's numerical data. Numbers are numbers, no quotes.

__What is a Variable and why are they important in JavaScript?__

A varible is a container for data. They are important because they let you store data, any data, and manipulate that data, use that data elsewhere, etc. 

## *Introduction to HTML*

__What is an HTML attribute?__

    <a href="https://website.com">The Net</a>
    
An attribute contains extra info about a tag. In this example, href is the attribute and it gives a location for the <a> tagged text to link to.
  
__Describe the Anatomy of an HTMl element.__
  
  It starts with an opening tag such as `<p>` followed by some text and finished with a closing tag like `</p>`. The opening tag can house attributes.
  
__What is the Difference between `<article>` and `<section>` element tags?__
  
  It seems to me like the main difference is that `<section>` is generic and meant to organize a piece of a webpage, where `<article>` is specifically for something which could stand alone and could resonable hold <section>s of its own.
  
__What Elements does a “typical” website include?__
  
  Every html doc needs a `<head>` and `<body>`. But a typical website probably has `<header>`, `<footer>`, `<aside>`, and `<nav>` at least.
  
  *Are `<head>` and `<body>` elements technically?? What about `<html>`???*
  
__How does metadata influence Search Engine Optimization?__
  
  Metadata holds info that search engines will access to find keywords or author names, things like that.
  
__How is the <meta> HTML tag used when specifying metadata?__
  
  It's used as a self-closing tag that lives in the `<head>`. It can reference something specific like `charset` or you can make what looks to me like a k:v pairing.
  
  *Do `<meta>` elements holding these k:v pairs need to refer to a specific thing somewhere? if so, where is that thing?*
  
  *ex: `<meta name="author" content="Whoever">` what if instead of author, you put creator? would your meta just be useless?*
  

## *Start Designing a Website*
  
__What is the first step to designing a Website?__
  
  Figure out what you're trying to accomplish and how a website would get you there. Then try to plan the steps. Okay, so this is just all three of the first steps...
  
__What is the most important question to answer when designing a Website?__
  
  ~~where do i put the dancing baby?~~ What am I trying to accomplish?
  

  ## *Semantics*

  __Why should you use an `<h1>` element over a `<span>` element to display a top level heading?__
  
  h1 comes prestyled to look like a heading, whereas you'd have to make your own span heading from scratch. h1 also has semantics used by SEO's and screenreaders for keywords and navigation. Also h1 is more readable to humans than span.
  
  *are semantics metadata for specific elements?*
  
__What are the benefits of using semantic tags in our HTML?__

  I touched on this in my previous answer. SEO's will pull keywords from certain semantic tags. Screenreaders use them for navigation. They offer specificty, lending to code readability and predictability.
  
  ## *What is JS*
  
  __Describe 2 things that require JavaScript in the Browser?__

  Interacting with API's for one, putting a map from google on your website, or maybe a spotify player. Another would just be storing data in a variable, maybe from user input.
  
  *I was thinking animations as well, but i think you can do that with CSS. how is animating with JS different?*
  
__How can you add JavaScript to an HTML document?__
  
  Well, you can jam it all between a couple of `<script>` tags, but usually it's probably better to add it from outside as an attribute in the header like this:
  
    <script src='myScript.js' defer></script>
  
  *is it true that it's really better? I need practice*
  
  *can you call a function from a js script that was loaded when your page loaded? or does it just do a run through at start and then terminate once it finsishes?*
