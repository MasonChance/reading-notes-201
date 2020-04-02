# Links Layout and funtion/method/object Overview

### [Html](/reading-notes-201/html-topics/Links)

folder/file relationships

folders are also called directories. files are the actual documents in the directory, or the "contents" of the directory. we use terms borrowed from the family tree concept to refer to directory/file relationships...remebering to tell the computer **exactly where to find the file or site it needs to link to** is really important. remembering how the family tree works will really help cut down on confusion. 


### [CSS](/reading-notes-201/css-topics/layout-positioning)

##### positioning schemes

- **Normal Flow:** this is the default. each block element apears on a new line. 
- **relative positioning:** moves an elementto the top,right,bottom, or left of it's *direct parent element* it does not affect the position of other elements in the same parent element.
- **Absolute positioning:** similar to relative but *scroll with the user*
- **fixed position:** from of absolute positioning an element in relation to the browser window rather than in relation to the other elements in the page.
- **floating Elements:** allows you to remove it from normal and position it far right or far left of it's parent element and other elements will flow around it much as if it was an inline element. 

screen size and resolution affect the size a page will display as having. this can be accounted for in a few ways. one is to use relative sizing constrants that fetch the size of the screen and render the content in relation to it. 

### [JavaScript ](/reading-notes-201/js-topics/functions-objects)

a function is a series of instructions that then encapsulated and given a name within the framework of the program you are working on and then can be called by their name from anywhere in the program without haveing to write out all the instructions every time you need them. 

declare it by using the following format. ` function name the function(){ all of the instructions the function will execute }`
call it simply by writing: `name of the function();`

Objects are similar to functions in that they are declared and contain statements but these statements are called properties and the properties are then given values in the code block `{ }`. from that point the object can be called and it is understood to have all of those properties and associated values. 

Objects are declared this way: `var objectName = { propertyname01:'propertyValue', propertyname02:'propertyValue',propertyname03:'propertyValue'....etc};`
