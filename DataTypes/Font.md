## Font

If a font file has been located, the font property can store its font name, font style and font size.
GRUB then proceeds to render all text in that font acording to its element or propery.

Fonts __must__ be stored inside the same directory as the theme.txt file

Because grub only supports PFF2 (.pf2) font formats, most fonts must be converted with the grub-mkfont or grub2-mkfont tool!

Example :

__terminal-font__ is the font property in this case

```
# Assuming that dejavu_12.pf2 is in our dir
terminal-font: "Dejavu Sans Regular 12"
```

Example 2 :

__item_font__ is the font property in this case
```
# Assuming that dejavu_bold_14.pf2 is in our dir
+ boot_menu {
	item_font = "DejaVu Sans Bold 14"
}