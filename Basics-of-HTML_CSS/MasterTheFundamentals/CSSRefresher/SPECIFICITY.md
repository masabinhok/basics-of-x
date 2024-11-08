## CSS SPECIFICITY

CSS specificity determines which styles are applied when there are conflicting rules.

### Inline styles

Specificity: 1000

### IDs

Specificity: 100

### Classes, Pseudo Classes and Attributes

Specificity: 10

### Element and Pseudo Elements

Specificity: 1

Winner is Inline styles having highest specificity, id selectors are more specific.
If two rules have same specificity, last one will be applied.
If we use !important, it will override any other styling.


