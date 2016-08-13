## desktop-image
<b> <sup> Data Type : Image </sup> </b>

Sets grub background image.

If desktop-image is set, desktop-color will be voided

If undefined : uses desktop-color
#
In practice :

```
# -- theme.txt --

# Set background to Background.png assuming it's in the same dir as theme.txt
desktop-image : "Background.png"
```