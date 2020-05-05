## Jquerry and DOM manipulation

jquerry is a litte antiquated but more than 97% of websites still use it particularily when a JS library is used in the website, thus it is still important to know it has important features especially when working with a legacy programs, and is useful in maintaining existing web-sites. 

the CDN for jequerry can be found at [jquerry-cdn](code.jquerry.com) place this in script before all other script tags at bottom of the body. 

use `$` to invoke jquerry function, this is a global variable representing the jquerry function. from this point we will use `$` to reference jquerry in our notes. 

$ has two types of methods, getters and setters. 
the getter replaces the `document.getElementById('')` method of DOM manipulation in a shorter form.
$ can also set values for the thing retrived, most $ getters can also be used as setters without changing thier basic structure. this is much shorter and easier than traditional DOM manipulation. 

all $ methods return the item that the method was run on. 

for easy reference of all jquerry methods see [jquerry-cheat-sheet](https://oscarotero.com/jquery/). this organizes all of the methods in an easy to read way that links directly back to the $ docs

## DOM with $

when declaring a var with a value assigned by $ start the var name with a `$`.
``` const *$varName* = $(*jquerrySelectors*);
    
``` 
 to get information from json file. use `$.get('*filePath'*, *callbackfunction*)`

 The process for using $ in dom manipulation.

 ``` 1. build template
     2. build clone w/jquerry target only the first child
     3. define constructor
     4. define prototype
     5. hide only the first child w/css


 ```
 