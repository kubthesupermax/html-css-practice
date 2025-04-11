## Html Notes

```bash
Syntax means rules for writing code.

a tag means link to a web site <a>

html_attribute modifies how an element behaves, examples - href determines where the link element takes us when we click it. Can have multiple html attributes on a link.

Attribute_Name is left of the equals sign and tells us what we are modifying.

Attribute_value is on the right side of the equals sign and tells us what we are modifying it to.

target attribute determines whether this link opens in the current page or in a new tab.
By_default It opens in the current page but if we set target to
"_blank" , it opens in a new page
```

## Weird quirks

```bash
Extra_spaces in html are ignored.

html_entity means special codes used to display reserved characters in HTML, like &lt; for < and &amp; for &.

paragraphs_by_default come with padding at the top and bottom, giving space between blocks of text.

text-element means an HTML element used to display text content, like <p>, <h1>, <span>, or <div>.

button not centering because text-align: center only affects inline or inline-block elements.

Fix 1: Make the button inline-block with display: inline-block.

Fix 2: Or make it block-level and center using margin: 0 auto.

Use one of these depending on your layout needs.
```
