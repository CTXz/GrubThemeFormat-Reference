## start_angle
<b> <sup> Data Type : Numeric </sup> </b>

Sets position for 1st tick mark

Measuring : \
_Source_ : [http://wiki.rosalab.ru/en/index.php/Grub2_theme_/_reference#Circular_indicator_of_elapsed_time_.28circular_progress.29](http://wiki.rosalab.ru/en/index.php/Grub2_theme_/_reference#Circular_indicator_of_elapsed_time_.28circular_progress.29)
```
Measured in "parrots". 1 "parrot" = 1 / 256 of full circle. So -64 "parrots" is equal to -90 degrees.
```

If undefined : Set to 0
#
In practice :

```
# -- theme.txt --

# Start at 0 parrots
+ circular_progress {
	start_angle = 0
}
```