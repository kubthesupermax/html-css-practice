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

## HTML STRUCTURE

```bash
html_structure refers to the way HTML elements are organized in a webpage, usually in a nested, tree-like format.

doctype_declaration is the first line in an HTML document (e.g., <!DOCTYPE html>) that tells the browser which version of HTML is being used.

html_element is the root element that wraps all content in an HTML document, typically written as <html>.

head_section contains metadata, links to stylesheets, and other resources, but not content visible on the page.

body_section holds all the visible content and elements like text, images, and links that appear on the webpage.

nesting means placing elements inside other elements to create a logical structure, such as putting <li> items inside a <ul>.

semantic_tags are HTML5 elements like <header>, <footer>, <article>, and <section> that describe the meaning of content.

block_vs_inline refers to how elements behave in layout: block elements take full width and start on a new line; inline elements do not.
```

## Void elements

```bash
void_elements are HTML elements that do not have closing tags and cannot have child content.

self_closing means these elements are written with just an opening tag, like <br>, <img>, or <input>.

line_break uses the <br> tag to insert a line break in text content.

image_element uses the <img> tag to display an image and must include the src attribute to define the image source.

input_element is used to create interactive fields in forms, like text boxes or checkboxes, using the <input> tag.

meta_tag provides metadata like character encoding or page description using the <meta> tag inside the head section.

link_tag is used to link external resources like CSS stylesheets with the <link> tag, placed in the head section.

no_content means void elements do not wrap around any content, so adding text or other elements inside them is invalid.
```

```bash
link_tag is a void element used in the <head> section to connect external resources like stylesheets or icons.

rel_attribute specifies the relationship between the current document and the linked resource, such as "stylesheet" for CSS files.

href_attribute provides the URL or path to the external resource being linked, like href="styles.css".

stylesheet_link uses <link rel="stylesheet" href="styles.css"> to apply external CSS styles to the HTML page.

favicon_link uses <link rel="icon" href="favicon.ico"> to set the small icon that appears in the browser tab.

no_closing_tag means the <link> tag does not need a closing </link> because it’s a void element.

head_section is where the <link> tag must be placed for it to properly apply styles or metadata.

external_resource refers to any file outside the HTML document that’s linked using the href attribute in the <link> tag.
```
