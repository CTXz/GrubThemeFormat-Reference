### \_\_timeout\_\_
<b> <sup> Data Type : String </sup> </b>

Stores remaining time before grub boots into the default selection

The timeout countdown gets voided if any button has been pressed

NOTE: The timout counter is only functional in the following elements :

* progress_bar
* circular_progress
* label

In practice :
#
```
# -- theme.txt --

# Displays ammount of seconds left in the middle of the screen
+ label {
	id = "__timeout__"
	color = "#000000"
	left = 50%
	top = 50%
}
```
#
```
# -- theme.txt --

# Display a white progressbar that extends by every second until it reaches timeout (and automatically its max size)
+ progress_bar {
	id = "__timeout__"
	left = 0
	top = 0
	height = 20
	width = 100%
	fg_color = "#FFFFFF"
}
```
#
```
# -- theme.txt --

# Draw a circle of ticks that extends by every second until it reaches timeout (and automatically a full circle)
+ circular_process {
	id = "__timeout__"
	left = 50%
	top = 50%
	height = 25
	width = 25
	tick_bitmap = tick_circle.png
}
```