## top
<b> <sup> Data Type : Numeric </sup> </b>

Defines top offset of an element

Each element starts at the top left corner, meaning, the higher the given value is, the lower the element is positioned
#
In practice :

###### Note the ":" character and the quotation marks at the number, those are root element specific only
#
```
# -- theme.txt --

# Sets console 50pxl lower the right
terminal-left : "50"
```
#
```
# -- theme.txt --

# Sets console in the horizontal middle
terminal-left: "50%"
```
#
```
# -- theme.txt --

# Sets bootmenu 50pxl to the right
+ boot_menu {
	left = 50
}
```
#
```
# -- theme.txt --

# Sets bootmenu to the horizontal middle
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