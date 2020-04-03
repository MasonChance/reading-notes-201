# images, color and text

### color

all color may be specified using 4 different methods. RGB: red green blue `rgb(integer to the 100's, integer to the 100's, integer to the 100's) ` HEXidecimal: this puts the rgbvalues into consecutive numbers preceeded by `#`, color names: many colors are specified and accepted by broswers by default and can be called by their names.  you can download a color picker extension for your browser for help choosing colors.

### text

text attributes affect the font itself or the way the font looks, 
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

### images

 always measure and adjust image size with the *pixels* unit. 
- images should be uploaded and saved at the same measurements you want to use them on the site. while they can be scaled with css attributes this can cause some undesired extra work, especially with dynamic sites or while adjusting other site elements in CSS. 
- img size is more important than resolution when being used in a web format.

the tag for displaying an image is self closing and must contain a source attribute to work correctly. ` <img src="img-file-location/image-file-name.img-file-type-extension>` other attributes like *hieght* *width* and *background* can be added either in the tag or via css rules. 