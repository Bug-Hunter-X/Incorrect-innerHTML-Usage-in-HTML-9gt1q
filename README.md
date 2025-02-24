# Incorrect innerHTML Usage in HTML

This repository demonstrates a common yet easily overlooked error when working with innerHTML in HTML.
The bug showcases an incorrect usage that leads to unexpected behavior. The solution provides the correct way to modify the content of a div element using innerHTML.

## Bug
The bug lies in the improper use of the `innerHTML` property. The code attempts to change the content of a div element without properly selecting it first.  This results in the innerHTML property not affecting the intended element.

## Solution
The solution correctly selects the div element using its ID before modifying its innerHTML. This ensures the update is applied to the correct element.