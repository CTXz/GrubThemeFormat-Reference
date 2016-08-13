## align
<b> <sup> Data Type : string </sup> </b>

Sets horizontal location of text

Possible values

* left
* center
* right

If undefined : Set to "left"
#
In practice :

```
# -- theme.txt --

# Draw "Hello in center"
+ label {
	text = "Hello"
	align = "center"
}
```