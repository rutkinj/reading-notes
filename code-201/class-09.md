###### class-09 reading notes

This reading is all about adding interactivity to our webpages. What's a webpage without good buttons? Event listeners give us a new aveneue to use JS in our webpages as well.

## Reading

### [HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)

[Your first Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form).
[How To Structure A Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form).

1. Why are forms so important in web development?
    - they provide an avenue for the user to interact with the webpage
1. When designing a form, what are some key things to keep in mind when it comes to user experience?
    - keep it simple and make the function clear
    - don't make it intrusive
    - never put a form inside a form
1. List 5 form elements and explain their importance.
    - `<label>` allows you to display a name for an input field
    - `<input>` allows you designate the type of input you want, text, checkbox, etc
    - `<textarea>` seems like a special version of input that can take multiple lines of text
    - `<fieldset>` and `<legend>` fieldset allows you create an area where similar types of inputs can be interacted with and legend is basially a label for this area.
    - `<form>` is a container for these other elements and determines what the result of the interaction is, where the input data is sent

### [Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

[Introduction To Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events).

1. How would you describe events to a non-technical friend?
    - events are basically when anything happens on a webpage. You clicked on something? That's an event. Something finished loading? Event. You're rotating your phone to horizontal? Event. Back to vertical? Event.
1. When using the `addEventListener()` method, what 2 arguments will you need to provide?
    - the event name, such as `click`
    - the name of the function to be called when this event is triggered
1. Describe the event object. Why is the target within the event object useful?
    - the event object is a reference to a particular triggered event
    - target refers to the element this event was triggered from. for example, if a button was clicked `e.target` would refer to the button element itself
1. What is the difference between event bubbling and event capturing?
    - event bubbling- an event that 'bubbles up' triggering from it's innermost element to it's outermost element that has an eventlistener
    - event capturing- the same thing but in the *opposite direction*


## Bookmark and Review

[HTML5 Input Types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)

[Event Reference and listings](https://developer.mozilla.org/en-US/docs/Web/Events)

## I want to know more about

- I want to figure out how to implement a simple search function as a form.
- bubbling and capturing: what is the purpose of this? maybe I missed something.
