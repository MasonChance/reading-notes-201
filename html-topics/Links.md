# Links Overview

links can be to either external websites or *relative* links to other pages within the site you are working on. to understand links it is importan to understand the relationships between them. external sites are easy you just enter the full url of the website as the value for the `href`atrribute. If you do not enter the https:// part than the browser assumes the link to be reletive. 

### folder/file relationships

folders are also called directories. files are the actual documents in the directory, or the "contents" of the directory. we use terms borrowed from the family tree concept to refer to directory/file relationships. 
since the browser knows it needs a dir/file within the website, it will limit it's search there, but it still has to know where the content it is referencing is. to do this we indicate the location and any successive location is listed after a `/` . for example if I need something in my images folder but inside my images folder i have 3 other folders that have image files in them, I also have to indicate which folder inside the images folder I am looking for. if i want an image from the third file in the images folder i would write my `href` attribute as follows. 

`<a href="images/folder3/image-name-here.*file extension such as png or jpeg*>`

remebering to tell the computer **exactly where to find the file or site it needs to link to** is really important. remembering how the family tree works will really help cut down on confusion. 