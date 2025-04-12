```bash
Example:
img {
  max-width: 100%;
  height: auto;
}

img - By default, an image displays inline and keeps its original (natural) dimensions, even if it overflows its container.

Why images overflow:

🧱 Default behavior - <img> tags are inline elements that maintain their native size.
📏 Large resolution - If an image's width is larger than its container, it will overflow unless controlled.
🌐 Responsive design - Without constraints, images don’t automatically adapt to different screen sizes.

Best practices to prevent overflow:

✅ Use max-width: 100%; - Ensures the image won't grow beyond the container's width.
✅ Use height: auto; - Maintains the image's aspect ratio while resizing.
✅ Consider display: block; - Removes extra space below the image caused by its default inline behavior.
✅ Wrap images inside a container (like a div) with controlled width if needed.

Responsive Image Tip:
img {
  display: block;
  max-width: 100%;
  height: auto;
}

This makes the image responsive and prevents it from breaking the layout.
```
