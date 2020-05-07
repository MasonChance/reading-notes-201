# Grid-based-layout

using grid allows you to manipulate columns and rows instead of just the rows like in flex-box. 
there are rules that apply to parent elements and rules that apply to child elements. 
set parent element to display: grid. then use the `grid-template-columns ` and `grid-template-rows` to set the number of columns and nubmer of rows. 

the widths of the columns and  rows can be set with px, em, %, and fr. 

  *fr* is a fractional unit and the number indicates how many fractions of the screen the row or column will take up. 

child elements can use the `order` property to change their position much like a `z-index` 0 is current -x is left +x is right.
