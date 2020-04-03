# Color and Text Overview. (list of attributes and noteworthy nuances)

### Color Attributes

- all color may be specified using 4 different methods. 
  - RGB: red green blue `rgb(integer to the 100's, integer to the 100's, integer to the 100's). a fourth value can be added to indicate opacity this is measured in value from .01-1.0. 
  - HEXidecimal: this puts the rgbvalues into consecutive numbers preceeded by `#` an additional 2 digits can be added to indicate opacity. 
  - color names: many colors are specified and accepted by broswers by default and can be called by their names. 

- using color as the only attribute statement without any modifiers affects the forground or text. 
- stating the part of an element that you want to change followed by ` -color: colorvalue ` where *colorvalue* is the color you select, will change the background. 
- you can download a color picker extension for your browser for help choosing colors
- hsl is another way similar to rgb but refers to hue saturation and lightness instead of red green blue. 
### text attributes

text attributes affect the font itself or the way the font looks


  - Typeface
    - serif
    - sans-serif
    - monospace
    - weight - adds emphasis and can affect the white-space of elements
    - style - affects italic, normal, and oblique- (normal but on an angle)
    - Stretch - affects spacing between letters as well as thickness of their lines
    - aside from default font-families there are open source typeface makers that you can access for a site but you will need to research the useage agreements. you can also link to a google css doc that will allow you to use fonts from there [google webfont](www.google.com/webfonts).


More attributes. 
- text-transform. affects letter CaSe 
- text-decoration. underline, strike, overline. (please don't use blink!)
- line-height, affects spacing between lines.
- kerning, spacing between words and letters
- and a variety of alignment options. 