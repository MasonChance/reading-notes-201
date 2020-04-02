# layout overview

Be sure to remember the previously discussed box model as we touch on some more detailed elements of page-layout. 
If an element is "inside" another element the "outter" element or parent element treats the "inside" element or child element as it's "Contents" two terms to remember. **Block** elements each start on a new line. **Inline** elements flow *in between* surrounding text. 

### positioning schemes

- **Normal Flow:** this is the default. each block element apears on a new line. 
- **relative positioning:** moves an elementto the top,right,bottom, or left of it's *direct parent element* it does not affect the position of other elements in the same parent element.
- **Absolute positioning:** similar to relative but *scroll with the user*
- **fixed position:** from of absolute positioning an element in relation to the browser window rather than in relation to the other elements in the page.
- **floating Elements:** allows you to remove it from normal and position it far right or far left of it's parent element and other elements will flow around it much as if it was an inline element. 

### accounting for varied screen size. 

screen size and resolution affect the size a page will display as having. this can be accounted for in a few ways. one is to use relative sizing constrants that fetch the size of the screen and render the content in relation to it. 

see page 387 in ducketts html&Css handbook for more detail on ways to account for dynamic content using gid layout templates. 

