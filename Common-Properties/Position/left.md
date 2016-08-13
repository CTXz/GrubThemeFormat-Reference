## left
<b> <sup> Data Type : Numeric </sup> </b>

Defines left offset of an element

Each element starts at the top left corner, meaning, the higher the given value is, the more right the element is positioned
#
In practice :

###### Note the ":" character and the quotation marks at the number, those are root element specific only
#
```
# -- theme.txt --

# Sets console 50pxl lower from top
terminal-top : "50"
```
#
```
# -- theme.txt --

# Sets console in the vertical middle
terminal-top: "50%"
```
#
```
# -- theme.txt --

# Sets bootmenu 50pxl lower from top
+ boot_menu {
	left = 50
}
```
#
```
# -- theme.txt --

# Sets bootmenu to the vertical middle
+ boot_menu {
	left = 50%
}
```
#
```
# -- theme.txt --

# Sets bootmenu 100pxl to the left from the middle
+ boot_menu {
	left = 50%-100
}
```