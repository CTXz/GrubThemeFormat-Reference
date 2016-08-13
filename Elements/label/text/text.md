## text
<b> <sup> Data Type : String </sup> </b>

Stores text that will be displayed

The text property may also be defined to special values :

* @KEYMAP_SHORT@ - enter: boot, `e': options, `c': cmd-line
* @KEYMAP_MIDDLE@ - Press enter to boot the selected OS, `e' to edit the commands before booting or `c' for a command-line.
* @KEYMAP_LONG@ - Press enter to boot the selected OS, `e' to edit the commands before booting or `c' for a command-line. ESC to return previous menu.

You may also set the common [id](../../../Common-Properies/id/id.md) property to display the elapsed time, however text should be empty

If undefined : None
#
In practice :


Example 1
```
# -- theme.txt --

# Display "Hello" as label
+ label {
	text = "Hello"
}
```

Example 2
```
# -- theme.txt --

# Display "enter: boot, `e': options, `c': cmd-line"
+ label {
	text = "@KEYMAP_SHORT@"
}
```

Example 3
```
# -- theme.txt --

# Display remaining time before default execution
+ label {
	id = __timeout__
}
```