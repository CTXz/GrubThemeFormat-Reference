## selected_item_font
<b> <sup> Data Type : Font </sup> </b>

Font used on item selection

If set to _inherit__, the font will be the same used by the [__item_font__](item_font.md) property

If undefined : inherit
#
In practice :

```
# -- theme.txt --

# Display DejaVu Sans font in bold on selection
+ boot_menu {
	selected_item_font = "DejaVu Sans bold 14"
}
```