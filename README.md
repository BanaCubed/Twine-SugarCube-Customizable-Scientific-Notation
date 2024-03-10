Twine SugarCube Customizble Scientific Notation

The .twee file contains a widget that replaces itself with the output
The widget should be used as such:
<<sciNotation {NUMBER TO CONVERT} {MIN VALUE FOR CONVERSION} {NUMBERS AFTER THE DECIMAL PLACE}>>

Reccomended to be something like this:
<<sciNotation $number $notationStart $notationLength>>

This also removes the '+' that comes with most conversions to scientific notation (can be removed by the corresponding line of javascript)

The second argument is the minimum number for conversion, not the minimum length.
