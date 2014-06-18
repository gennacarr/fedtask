fedtask
=======

Responsive page

Retina images:
The way this has been implemented in current job is to double the size of the image and then scale it down in the CSS. 

I am aware there are also multiple other ways of doing this, such as:

 - using js/plugin to look for other image sizes and serve those up instead
 - using js/plugin/third party service that automatically resizes images on the fly
 - using the new HTML <picture> tag to declare what images should be used at what screen size
