## selected_item_color
<b> <sup> Data Type : Color </sup> </b>

Text color used on item selection

If set to _inherit__, the color will be the same used by the [__item_color__](item_font.md) property

If undefined : inherit
#
In practice :

```
# -- theme.txt --

# Display grey text on selection
+ boot_menu {
	selected_item_color = "#7F7F7F"
}
```