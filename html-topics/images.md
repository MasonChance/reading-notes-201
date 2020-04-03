# Images in HTML

There are 2 things to bear in mind when adding images aside from the actual tag used to add display them after they have been uploaded to the site directory. the tag for displaying an image is self closing and must contain a source attribute to work correctly. ` <img src="img-file-location/image-file-name.img-file-type-extension>` other attributes like *hieght* *width* and *background* can be added either in the tag or via css rules. 

First we need to consider image size, this will affect how the rest of the page appears and flows.
- always measure and adjust image size with the *pixels* unit. 
- images should be uploaded and saved at the same measurements you want to use them on the site. while they can be scaled with css attributes this can cause some undesired extra work, especially with dynamic sites or while adjusting other site elements in CSS. 
- img size is more important than resolution when being used in a web format.
