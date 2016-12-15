---
title: CSS background
category: CSS
---

Background
----------

### Shorthand

    background: #ff0  url(bg.jpg) left top      / 100px auto no-repeat fixed;
    background: #abc  url(bg.png) center center / cover      repeat-x  local;
    /*          ^     ^           ^             ^            ^         ^
                color image       position      size         repeat    attachment */

### Multiple backgrounds

    background:
      linear-gradient(to bottom, rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
      url('background.jpg') center center / cover,
      #333;

### Other properties

    background-clip: border-box | padding-box | content-box [, ...]*; /* IE9+ */
    background-repeat: no-repeat | repeat-x | repeat-y;
    background-attachment: scroll | fixed | local;
    background: url(x), url(y); /* multiple (IE9+) */

### Background size

    background-size: auto|length|cover|contain|initial|inherit;

|Value     |Function                                                                                                                                                                                                                     |
|----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|auto      |Default value. The background-image contains its width and height                                                                                                                                                            |
|length    |Sets the width and height of the background image. The first value sets the width the second value sets the height. If only one value is given the second is set to "auto"                                                   |
|percentage|Sets the width and height of the background image in percent of the parent element. The first value sets the width the second value sets the height. If only one value is given the second is set to "auto"                  |
|cover     |Scale the background image to be as large as possible so that the background area is completely covered by the background image. Some parts of the background image may not be in view within the background positioning area|
|contain   |Scale the image to the largest size such that both its width and its height can fit inside the content area                                                                                                                  |
|initial   |Sets this property to its default value. Read about initial                                                                                                                                                                  |
|inherit   |Inherits this property from its parent element. Read about inherit                                                                                                                                                           |
