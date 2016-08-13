## Image

A image property stores a path to a targeted image file.
GRUB then proceeds to render that image acording to its element or propery.

It is __highly__ recommended to store images inside the same directory as the theme.txt file
as it doesn't require to write down the entire path, rather only the image file name as the cd (current directory)
is set to the theme.txt directory.

The following image formats are supported

* PNG
* TGA
* JPG

Transparency (or Alpha layer) is supported

Example :

__file__ is the image property in this case

```
# Render example.png in the middle
+ image {
    file = "example.png"
	top = 50%
	left = 50%
}