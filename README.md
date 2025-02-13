# Uncommon HTML Bug: Incorrect innerHTML Usage

This repository demonstrates a subtle yet important bug related to using `innerHTML` in HTML.  The incorrect usage attempts to directly append to the `innerHTML` which might lead to unexpected behavior. The correct approach demonstrates the proper way to modify `innerHTML` using concatenation of strings.

## Bug Description
The bug highlights the importance of understanding how `innerHTML` works when modifying the content of an HTML element. Directly appending to `innerHTML` using the += operator might not always work as expected and may lead to issues with certain browsers, rendering engines or when dealing with complex HTML structures.

## Solution
The solution shows the corrected approach to using `innerHTML`. It involves concatenating the existing `innerHTML` with the new content before assigning it back to the `innerHTML` property.