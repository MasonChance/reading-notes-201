# Embedded javascript templating

ejs is a view engine using Express server package that allows for using javascript to create templates on the front-end including pagination and interacting with data that comes back in JSON format. ejs can also be used in conjunction with express paths to create pagination. 

the general syntax for ejs is `<%= variable %>` to set a value to be read and displayed to the page. to have something in place but not yet read, use the same open/close tags but no `=` sign. 

Partials refer to re-usable code snippets. these are usually stored in a directory and used by writing them into the ejs view file `<%include *fileName*%>.