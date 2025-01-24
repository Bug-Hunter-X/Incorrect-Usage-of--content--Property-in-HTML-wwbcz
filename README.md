# Incorrect Usage of 'content' Property in HTML

This repository demonstrates an uncommon error in HTML related to the incorrect usage of the 'content' property to modify the content of an HTML element. The 'content' property is not a standard way to change the content of a div.  This example highlights the correct use of 'textContent' and 'innerHTML' and illustrates why attempting to use 'content' will fail.

## Bug Description
The bug lies in the incorrect usage of the `content` property to modify the text within a `<div>` element.  HTML elements don't have a standard `content` property for setting their inner content. This will result in no visible change to the HTML element.

## Solution
The correct way to modify the content of a div is using `textContent` or `innerHTML`.

*   `textContent` sets the content as plain text, while
*   `innerHTML` allows you to set content using HTML tags.