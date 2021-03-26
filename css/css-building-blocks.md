# CSS Building Blocks

## Cascade and Inheritace

CSS stands for Cascading Style Sheets, and that first word *cascading* is incredibly important to understand - the way that the cascade behaves is key to understanding CSS.

* Stylesheets **cascade** - at a very simple level, that means that the order of the CSS rules matter; when two rules apply that have equal specificity the one that comes last in the CSS is the one that will be used.

* **Specificity** is how the browser decides which rule applies if multiple rules have different selectors, but could still apply to the same element.

* **Inheritance** - Some CSS property values set on parent elements are inherited by their child elements, and some aren't.

* Which properties are inherited by default and which aren't is largely down to common sense.

## CSS selectors

A CSS selector is the first part of a CSS Rule.
It is a pattern of elements and other terms that tell the browser which HTML elements should be selected to have the CSS property values inside the rule applied to them.

The element or elements which are selected by the selectors are referred to as the *subject of the selector*.

### Types of Selectors:

1. Type, class, and ID selectors.
2. Attribute selectors.
3. Psedudo-classes and pseudo-elements.
4. Combinators

Visit [here](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors) to know more.

### Descendant combinator

Selectors that utilize a descendant combinator are callled *descendant selectors*.

Represented by a single space `( )`.

### Child combinator

Child combinator matches only those elements matched by the second selector that are the direct children of elements matched by the first.

Represented by `(>)`.

### Adjacent sibliing combinator

Matches only those elements matched by the second selector that are the next sibling element of the first selector.

Represented by `(+)`.
