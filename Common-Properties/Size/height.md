## height
<b> <sup> Data Type : Numeric </sup> </b>

Defines height of an element

Height expands to the bottom, meaning the higher the value, the more the element stretches to the bottom of your screen
#
In practice :

###### Note the ":" character and the quotation marks at the number, those are root element specific only
#
```
# -- theme.txt --

# Sets console height to 500pxl
terminal-height : "500"
```
#
```
# -- theme.txt --

# Sets console height to the size of the screen resolution height
terminal-height: "100%"
```
#
```
# -- theme.txt --

# Sets bootmenu height to 300pxl
+ boot_menu {
	wdith = 300
}
```
#
```
# -- theme.txt --

# Sets bootmenu height to half the screen
+ boot_menu {
	height = 50%
}
```
#
```
# -- theme.txt --

# Sets bootmenu height 100pxl less than the half of the height resolution
+ boot_menu {
	height = 50%-100
}
```