## text
<b> <sup> Data Type : String </sup> </b>

Stores text that will be displayed on/inside the progress bar

The text property may also be defined to special values :

<b> NOTE : [id](../../../Common-Properies/id/id.md) must be set before the values can be used </b>

_Ns_ = Number of seconds remaining before default selection gets executed

* @TIMEOUT_NOTIFICATION_SHORT@ - _Ns_
* @TIMEOUT_NOTIFICATION_MIDDLE@ - _Ns_ remaining
* @TIMEOUT_NOTIFICATION_LONG@ - _Ns_ The highlighted entry will be executed automatically in _Ns_

If undefined : None
#
In practice :


Example 1
```
# -- theme.txt --

# Display "Hello" in progressbar
+ progress_bar {
	text = "Hello"
}
```

Example 2
```
# -- theme.txt --

# Display Number of remaining seconds in progressbar
+ progress_bar {
	text = @TIMEOUT_NOTIFICATION_SHORT@
}
```