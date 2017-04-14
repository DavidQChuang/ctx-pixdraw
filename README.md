# Description
ctx-pixdraw is a Javascript pixel text and shap drawing library.

### Features
* Customizable scale factor
* Customizable 'font'.

### Future features
* More shapes and other things.

### Browser Compatibility
* Works in any browser that supports the HTML5 Canvas element.

# Documentation

### Contents
* [Usage](#usage)
* [Examples](#examples)

### Usage
#### Variables
* var letters (string array) - This is the variable with the 'font' letters. You can change these arrays if you want to use a different 'font'.
* var scaleFactorX (number) - This is the variable that scales up the rectangles and text in the X axis.
* var scaleFactorY (number) - This is the variable that scales up the rectangles and text in the Y axis.
#### Functions
* drawText(x(num),y(num),text(string array),width(num),height(num)) - Draws text from the letters variable and scales it up on each axis by (scaleFactor(axis) * width).
* drawRect(x(num),y(num),width(num),height(num)) - Draws a rectangle at (x * scaleFactorX), (y * scaleFactorY) with a width of (width * scaleFactorX) and a height of (height * scaleFactorY).

### Examples

### License

Copyright (c) 2017 David Chuang

Released under the [MIT License](https://github.com/HyperionSniper/ctx-pixdraw/blob/master/LICENSE).
