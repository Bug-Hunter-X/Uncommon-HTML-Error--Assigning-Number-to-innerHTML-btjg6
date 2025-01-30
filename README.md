# Uncommon HTML Error: Assigning Number to innerHTML
This repository demonstrates an uncommon error in HTML related to using the `innerHTML` property with a numerical value instead of a string.  While common practice involves setting `innerHTML` to strings, using other data types can lead to unexpected behaviors.

## Description
The `bug.html` file shows an example where a number (123) is assigned to `innerHTML` of a div element. This results in the number being interpreted and rendered differently than a string.

## Solution
The `solution.html` file corrects the issue by converting the number to a string before assigning it to `innerHTML`. This ensures the number is rendered as expected.

This example highlights the importance of ensuring data types are correctly handled when manipulating the DOM via `innerHTML` to avoid unexpected rendering behavior.