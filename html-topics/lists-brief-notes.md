# Lists-Organizing your information

Lists are used to organize information with similar qualities. ie: items in a cart, to-do-tasks, order of operations, new terms about a topic, etc. most of us are already familiar with unordered lists `<ul>` and ordered lists `<ol>` in html syntax. below we will give an overview of something called a definition list which is less common but still very useful. any list of any kind can be nested inside another but putting the appropriate set of tags inside the list item `<li>` of an existing list. 

## Definition Lists

Definition lists are used to show a collection of terms along with their definitions. below are the tags used to create the list and descriptions/notes on structure, content, and syntax. 

- `<dl>` is used to create the list. don't forget the closing tag `</dl>` the next two tags create the list items and the list item definitions that go between the open/close tags of the definition list; and are organized in matched pairs.

- ` dt ` "*Definition Term*" this holds the term being defined. 
- ` dd ` " *Definition* list *Definition*. the way the tag is written may seem redundant but hopefully the added "list" above helps clarify. this is where you will see the actual definition of the term imediately preceeding it. 