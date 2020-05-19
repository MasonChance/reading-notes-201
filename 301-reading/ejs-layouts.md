# Using Partials EJS

Partials are a way to use ejs to describe templates for repeated html or other repeated code in your app. put all the repeated html in a `/views/partials` directory and the filename of the partial. to use a partial add `<%-include('partials/*fileName*') %>` in the place you want to add it. 