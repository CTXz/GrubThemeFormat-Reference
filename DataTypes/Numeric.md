## Numeric

A numeric property may only contain the following values :

* Integral value in pixels
* Integral percentage value of elements size (or screen if it's the root element)
* Combined value where a percentage may be additioned or subtracted with a pixel value and vise versa

NOTE: No whitespaces are allowed between symbols and values (eg. 20%-100 OK, 20% - 100 BAD)

Example Pixel value:

__height__, __width__, __left__ and __top__ are the numeric properies in this case

```
# Display 100x100 "Hello" 200 pixels to the right and 50 pixels from top
+ label {

	width = 100
	height = 100

	left = 200
	top = 50

	text = "Hello"
	
}
```

Example Percentage value:

__left__ and __top__ are the numeric properies in this case

```
# Display "Hello" in the middle of the screen
+ label {

	left = 50%
	top = 50%

	text = "Hello"

}
```

Example Combined value

__height__, __width__, __left__ and __top__ are the numeric properies in this case

```
# Display 50x50 exampleImage.png in the middle
+ image {

	file = "exampleImage.png"

	width = 50
	height = 50

	left = 50%-25
	top = 50%-25

	text = "Hello"

}
```