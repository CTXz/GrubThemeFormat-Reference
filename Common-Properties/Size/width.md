## width
<b> <sup> Data Type : Numeric </sup> </b>

Defines width of an element

Width expands to the right, meaning the higher the value, the more the element stretches to the right side of your screen
#
In practice :

###### Note the ":" character and the quotation marks at the number, those are root element specific only
#
```
# -- theme.txt --

# Sets console width to 500pxl
# Note the ":" character and the quotation marks at the number, those are root element specific only
terminal-width : "500"
```
#
```
# -- theme.txt --

# Sets console width to the size of the screen resolution width
terminal-width: "100%"
```
#
```
# -- theme.txt --

# Sets bootmenu width to 300pxl
+ boot_menu {
	wdith = 300
}
```
#
```
# Sets bootmenu width to half the screen
+ boot_menu {
	width = 50%
}
```
#
```
# Sets bootmenu width 100pxl less than the half of the width resolution
+ boot_menu {
	width = 50%-100
}
```