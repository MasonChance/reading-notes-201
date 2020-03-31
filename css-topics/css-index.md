# CSS Overview and Index

## What is CSS and How does it Work

"CSS" is an acronym for Cascading Style Sheet; It allows us to control how a page looks to the user by creating rules that the browser will follow for rendering each element of an HTML document. As we referenced in the [HTML-Section](/reading-notes-201/html-topics/html-index) each element has default attributes that can be modified within its opening tag. CSS allows us to modify those elements more globaly so that we don't have to go to each individual element and copy paste; which leaves a lot of room for error and is time consuming. Think of CSS as a pre-packaged costume that you would get from the store and then dress the body of your web-page in, with the option to add extra accessories to make it your own. 

To create our costume we first need to understand it's parts and how intricate we want it to be. Let's start with the similarities in the syntax of CSS as compared to HTML. First as always is scope, most html elements have a general or global scope that is then altered by nesting them inside other elements. CSS will always apply the attributes listed for a given element to all elements within it unless specifically told otherwise. When designing our CSS it is important to bear this in mind. Secondly, is the use of "open and close" signifiers so that the browser knows which attributes you are applying to which element; In CSS the "open and close tag" is the use of curly braces `{}`. The final siginificant similarity is the way that attributes are declared and given a value 

![css-syntax-diagram](/reading-notes-201/css-topics/css-diagrams/css-syntax-dia.png)

There are selectors that allow you to target elements more specifically as well such as `.class` and `#id` you may use [CSS Reference](https://www.w3schools.com/cssref/css_selectors.asp) at https://www.w3schools.com/default.asp for descriptive list of CSS selectors and their usage. 

In terms to page layout it is necessary to understand the box-model. all HTML elements have an invisible series of boxes around them that define the space they take up and affect how they will interacate positionally with other elements. the outermost box is called *Margin*. Margin is the space between the element and the the outer-most element it nests inside.*border* is inside margin and is invisible unless given a value in CSS or within the open tag of the element and seperates content from margin. *padding* defines the space between the border and the content itself. 

![box-model-diagram](/reading-notes-201/css-topics/css-diagrams/css-box-model.png)

Now that you understand the basic syntax of CSS and how it interacts with HTML you are ready to start your costume shop! Lists of Attributes and Universal Attribute Values can be found via the W3schools website listed above and are also documented many other places if you prefer a different style of reference.

### CSS Index

(links will be added as the course continues)

