# Specificity

Specificity is a scoring system that gives priority to certain types of CSS selectors. It ensures that more targeted rules (like IDs) override more general ones (like class selectors). Specificity is calculated based on the types of selectors used:

## Inline Styles (Top Authority): 
These are like direct orders given by the CEO. They override any other styles because they are considered the most specific.
## ID Selectors (High Authority): 
These are like high-level executives. They can override class and element selectors but not inline styles.
## Class Selectors (Mid Authority): 
These are like managers. They have more influence than general employees but less than executives or direct orders.
## Element Selectors (Lowest Authority): 
These are like general employees with basic roles and the least influence.

How the Cascade and Specificity Work Together

When there are multiple CSS rules targeting the same element, the cascade first looks at importance (!important), then at specificity, and finally at the order of appearance to decide which rule to apply.

[specific vader](./specific_vader.html)

Further reading:
https://specificity.keegan.st/
https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity
https://css-tricks.com/specifics-on-css-specificity/