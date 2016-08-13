## scrollbar_thumb
<b> <sup> Data Type : Styled Box </sup> </b>

Texture used for scrollbar thumb (The movable part of a scrollbar, wrapped inside the [scrollbar_frame](scrollbar_frame.md))

If undefined : None
#
In practice :

```
# -- theme.txt --

# Draw scrollbar thumb using scrollbar_thumb_*.png decorations
+ boot_menu {
	scrollbar_thumb = scrollbar_thumb_*.png
	scrollbar_frame = scrollbar_frame_*.png
}
```