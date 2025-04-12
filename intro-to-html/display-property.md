```bash

Example:
h1 {
  display: block;
}

display - It tells the browser how the element should behave in terms of layout (i.e., box behavior)

Common values for display:

block - Element takes up full width of container, starts on a new line (e.g., <div>, <h1>, <p>)
inline - Element takes up only as much width as it needs, stays on the same line (e.g., <span>, <a>)
inline-block - Like inline, but allows setting width and height.
               ⚠️ Note: Even after using inline-block, some elements (like <div>) may still stretch to 100% width by default.
               ✅ You may need to manually set the width (e.g., width: 50%) to reduce it.
none - Hides the element completely (not rendered on the page)
flex - Turns the element into a flex container for flexible layout
grid - Turns the element into a grid container for grid-based layout

```
