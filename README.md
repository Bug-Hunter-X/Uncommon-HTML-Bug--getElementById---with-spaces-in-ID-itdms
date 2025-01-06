# Uncommon HTML Bug: getElementById() with Spaces in ID

This repository demonstrates an uncommon bug in HTML related to using `getElementById()` with spaces in the element's ID.  The correct solution is to use hyphens or underscores as separators instead of spaces.

## Bug Description
Attempting to access an HTML element by its ID using `document.getElementById()` with spaces in the ID will fail to select the element correctly. The `getElementById()` method is case-sensitive and does not handle spaces correctly. 

## How to Reproduce
1. Open `bug.html` in your web browser.
2. Notice that the text in the div does not change as expected. 

## Solution
The solution is to avoid spaces in the ID. Use hyphens or underscores as separators, and ensure you access the ID with the exact casing.