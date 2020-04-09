# Forms Lists and Tables.
forms take in user information since user information is usuall grouped together as being related, it is organized using a list and tables are the cleanest most user freindly way to organize and display that information in a useful fashion

## The HTML side 

Forms are created with elements specifically designed to take in user input and store it for future use. the Elements take specific kinds of information using different controls for each.
- Adding text: 
  - text input (like the prompts and confirms used earlier)
  - passwrd input (masks entered characters)
  - multi-line text area
- Making Choices
  - "radio buttons" 
  - check boxes
  - dropdown boxes
- Submitting entered information
  - image buttons allowing submission of image as data
  - basic submit button
  - uploading files (i know you've seen the browse files button)

The tag for creating a form is ` <form> ` form elements have required attributes
  - action defines where the information will go using a url to the server page
  - methods tel it what to do with the information
    - these are either get or set (retrieve or store)
  finally each part of the form must be told what controls it will have. 

form information can be grouped together using a `<fieldset>`

just like any html element, forms can be styled with attributes. tables and forms us many of the same attribute and attribute values. 

## Javascript Events
In short the flow of an event looks like this
` *interaction* --> *Creates Event*--> *Event Triggers Code* --> **Code Responds To User** ` rinse and repeate. 

the 3 main steps that get repeated are

1. select the element that will respond
1. indicate the event that it will respond to
1. declare the code that you want to be invoked in response to the event. 

very much like the DOM manipulation cycle of Get target create content uppend target content. 

html event handlers are bad practice. DOM even Handlers were the standard and DOM event Listeners have become the new standard with an update in 2000 a.d.  

syntax for event handler/listener in the DOM is as follows

```
elementNodeToTarget.**on**_eventName_ = functionName;

```

