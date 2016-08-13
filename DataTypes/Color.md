## Color

In the grub theme language there are 3 ways to define a color property

#### RGB

Consist of three different color values (bytes to be specific)

* __R__ - Red
* __G__ - Green
* __B__ - Blue

Each color ranges to a max value of __255__

Example colors :
```
Pure Red
255,0,0

Pure Green
0,255,0

Pure Blue
0,0,255

Pure Black
0,0,0

Pure White
255,255,255

Pure Grey
127,127,127

Lime
128,255,0
```

Defining RGB to a color property
```
# Neon Magenta
color = "124,6,183"
```

#### RGB HEX

The most common and used type due to it's already popular usage in the HTML language and shorter writing

Same as RGB however, colors start __#__ sign following the color values is __hexadecimal__ without seperation commas

Because RGB HEX is so common, there are plenty of generators available, here are few :

http://www.color-hex.com/ \
http://html-color-codes.info/ \
http://www.w3schools.com/colors/colors_picker.asp

Example colors :
```
Pure Red
#FF0000

Pure Green
#00FF00

Pure Blue
#0000FF

Pure Black
#000000
or
#000

Pure White
#FFFFFF

Pure Grey
#7F7F7F

Lime
#80FF00
```

Defining RGB HEX to a color property
```
# Neon Magenta
color = #7C06B7"
```

#### SVG 1.0

Simple color names (eg. blue, red, cyan)

For all names visit one of the following pages :

https://www.w3.org/TR/css3-color/#svg-color \
http://www.december.com/html/spec/colorsvg.html

Defining SVG to a color property
```
# Neon Magenta
color = "midnightblue"