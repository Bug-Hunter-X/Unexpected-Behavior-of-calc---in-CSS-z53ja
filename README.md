# CSS calc() Unexpected Behavior

This repository demonstrates an issue where the CSS `calc()` function doesn't produce the expected result when calculating an element's width relative to its parent's width. The element should have a width of 50% of the parent's width minus 20 pixels, but this calculation does not work as expected.

## Issue Details

The provided CSS uses `calc(50% - 20px)` to determine the width of an element. However, the calculated width is incorrect.  This could be due to several factors, such as missing or incorrect parent element dimensions, incorrect unit usage, or a conflict with other CSS rules.

## Solution

The solution addresses potential causes: ensuring the parent element has defined dimensions, correctly using units within the `calc()` function, and resolving potential CSS rule conflicts.  The solution provides a corrected CSS file that addresses the unexpected behavior.