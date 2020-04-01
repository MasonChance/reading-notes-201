# Lists, Controling Boxes, Switch Statements and Loops

We are going to start referenceing our previous sections you can click on the header for each topic to go to the full detail page for that topic. 

#### [HTML Lists](/reading-notes-201/html-topics/lists-brief-notes)

Lists are used to organize information with similar qualities. ie: items in a cart, to-do-tasks, order of operations, new terms about a topic, etc.

Definition lists are used to show a collection of terms along with their definitions. below are the tags used to create the list and descriptions/notes on structure, content, and syntax. 

- `<dl>` is used to create the list. don't forget the closing tag `</dl>` the next two tags create the list items and the list item definitions that go between the open/close tags of the definition list; and are organized in matched pairs.

- ` dt ` "*Definition Term*" this holds the term being defined. 
- ` dd ` " *Definition* list *Definition*. the way the tag is written may seem redundant but hopefully the added "list" above helps clarify. this is where you will see the actual definition of the term imediately preceeding it. 

#### [CSS Controlling Boxes](/reading-notes-201/css-topics/boxes-more-detail)

We discussed the box model breifly In our [CSS Overview](/reading-notes-201/css-topics/css-topics/css-index) for convenience I've also included the diagram from the overview here. Now lets look at what we can do with the box-model and how it influences page design...

boxes take up as much space as is needed  to fit their contents. Height and Width values can be specified in pixels, %ofpage or structural element, and ems which are relative to the content of the box. as discussed previously you can also alter the dimensions of the box by specifying: Borders, Padding, and Margin.

you can also add images and shadows to the box and change its apparent shape. for more on the specific attributes see [w3schools Css reference](https://www.w3schools.com/cssref/default.asp). 

#### [Switches and Loops](/reading-notes-201/js-topics/decisions-loops)

a switch statement allows us to set multiple conditions with different outcomes based on input flow and how each successive condition is evaluated. Switch statements function similarily to `if` and `else if` statements but create a default value that runs uless a condition is met. starting with a switch variable the switch value is set. 

**for** loop. use this if you know the specific number of times you need the code to run. 

**while** loop. use this if you do not know how many times the code should run. 

**do while** is like the *while* loop but will always run each peice of code at least once even if condition evaluates false. in this case the statements are made ***before the condition is declared***