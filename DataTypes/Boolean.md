## Boolean

Consists of only two simple states :

* true
* false

In other words, a boolean may only store 1 bit, with 0 beign false and 1 being true.

A boolean is mainly used for __flags__ that signal if something should happen or not

Example :

__visible__ is the boolean propery in this case

```
# Hide boot menu
+ boot_menu{
	visible = false
}
```