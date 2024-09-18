In CSS, cascading and specificity are two critical mechanisms that work together to determine how styles are applied to elements. Let’s break down how they relate:

# The Cascade
The cascade refers to the process by which the browser determines which CSS rules apply to an element when multiple conflicting rules exist. It prioritizes rules based on:

## Origin
Stylesheets can come from different sources (e.g., browser default styles, external stylesheets, inline styles, etc.).

## Importance
The use of the !important keyword will make a rule override any other rules, regardless of order or specificity.

## Specificity 
When multiple rules target the same element, the one with the highest specificity takes precedence.

## Order of Appearance
If two rules have the same specificity and importance, the one that appears later in the stylesheet wins.

[cascading potter](./cascading_potter.html)

### Further readings:

https://developer.mozilla.org/en-US/docs/Web/CSS/Cascade

https://css-tricks.com/the-c-in-css-the-cascade/
