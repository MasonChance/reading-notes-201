# HTML, and More on Functions Methods and Objects

HTML can be used to display content as a table this works on the same framework as a nested list:
```
<table>
  <th>
    <tr> *first row*</tr>
    <tr> *second row* </tr>
    <tr>*ad infinitum*</tr>
  </th>
  <th>
    <tr>rinse adn repeat for each column and the rows it contains.
  </th>
</table>
```

tables are great for organizing information but take some extra care in writing so that the information displays in the correct position. 

### back to JavaScript.

as in yesterdays reading we discused object literals now we may want to use a constructor to allow us to create more than on object with the same properties as the first but using a function instead to fill in the object's unique values for those properties. 

accessing the object after it is created is done the same way. 

the syntax for constructor object creation is as follows: 

```
*declare a function*
function objectName //// name the function after the general name of the object
*function objectName*(propertyName01, propertyName02, etc)///// list the property names as    parameters of the function
*function objectName(propertyName01, propertyName02, etc)*{
  ***this***  ////_is a keyword refering to the object the keyword is invoked inside._ 
  *declare the values of the propertys as you would declare variables but using dot notation and the *this* keyword.
  this.propertyName01 = valueOfProperty;
  this.propertyName02 = valueOfProperty;
  *methods are added to the Object by nesting them as properties with a value set to a function declaration. the function needs no name for this technique.
  this.propertyNameNotPreviouslyDeclared = function(){
    *code the function as normal here*;
  },<--- add a comma to the final brace of the function code-block

  *more properties can go here*
} end of object declaration. 


  