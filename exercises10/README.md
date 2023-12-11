# Practice 10

## Task 1
Implement a `Button` class that contains width, height, button text,
and the `show()` method, which displays the button on the screen
using the button tag and the `document.write()` function.

Implement the `BootstrapButton` class by inheriting it from the
`Button` class. Add the color field and override the `show() ` method
so that the button is displayed with styles and the specified color.

## Task 2
Implement a class that describes a geometric figure with properties and methods:
 - get property to get name of the figure
 - method for displaying information about the figure (sides and their length)
 - method for calculating area of the figure
 - method for calculating perimeter of the figure

Implement inherited classes: square, rectangle, and triangle. Override
output and calculation methods in the heir classes.
Create an array with different figures and display information about
each figure including area and perimeter.

## Task 3
Implement the `ExtentedArray` class by inheriting it from the standard Array class and adding the following methods:
 - `getString(separator)` method to get a string with all array elements listed in the specified delimiter: comma, dash, space, etc.
 - `getHtml(tagName)` method to get a string with html code, where each element of the array is wrapped in the specified tag (note, if the li tag is specified, all elements must also be wrapped
in ul).

Create an object of the `ExtentedArray` class, fill it with data and
display the results of the `getString()` and `getHtml()` methods.