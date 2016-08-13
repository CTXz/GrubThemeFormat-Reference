# Styled Box

A styled box property can consists of up to 9 images that complete the decoration for a simple box

To make a complete styled box, there can be a total of 9 images, each for one decoration.

The following images should exist for a complete styled box (replace exampleImage with the according image name)

* exampleImage_c.png - Centre

* exampleImage_n.png - North
* exampleImage_e.png - East
* exampleImage_s.png - Sout
* exampleImage_w.png - West

* exampleImage_ne.png - North East
* exampleImage_nw.png - North West
* exampleImage_se.png - South East
* exampleImage_sw.png - South West

To set the property, use the asterisk symbol
```
exampleImage_*.png
``` 
__

Example :

Inside theme directory

```
/boot/grub/themes/exampleTheme/

boot_menu_c.png - Centre texture
boot_menu_n.png - Top edge texture
boot_menu_e.png - Right edge texture
boot_menu_s.png - Bottom edge texture
boot_menu_w.png - Left edge texture
boot_menu_ne.png - Top right corner texture
boot_menu_nw.png - Top left corner texture
boot_menu_se.png - Bottom right corner texture
boot_menu_sw.png - Bottom left corner texture
```

In theme.txt

__menu_pixmap_style__ is our styled box property in this case
```
+ boot_menu {
	menu_pixmap_style = "boot_menu_*.png"

	height = 76%
	width = 50%

	top = 12%
	left = 25%
}


