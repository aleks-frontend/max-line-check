# maxLineCheck()
## Implementation
### HTML implementation
`data-max-line` attribute needs to be added to an HTML element that we want the text restriction to apply to.
### Additional instructions
- Just add integer value to data-max-line attribute and this will be set as the maximum number of lines allowed.
- Note that font-size and line-height need to be set to element itself and not children elements!
- Cause calculation is using line-height of the element that has data-max-line attribute set.
- Also, it is not advised to use this if we have div container that has rich text input inside with elements 
with different font sizes, line heights and margins (in these cases, it is advised to use data-max-height)
