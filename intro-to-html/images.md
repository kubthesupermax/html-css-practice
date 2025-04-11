```bash
width_attribute sets the horizontal size of an image in pixels or percentage using the width="value" syntax.

height_attribute sets the vertical size of an image using height="value", which can also be in pixels or percentage.

image_scaling happens automatically when you set either width or height — the other adjusts to keep the aspect ratio.

fixed_dimensions like width="300" height="200" make the image display at exactly those pixel sizes, regardless of original size.

percentage_values can be used (e.g., width="50%") to make images responsive to the size of their parent container.

distortion_warning occurs if both width and height are set and don’t match the image’s original ratio, which can stretch or squash the image.

css_alternative allows setting image size using CSS styles instead of HTML attributes, like style="width: 100px; height: auto;".

default_behavior displays the image in its original size if width and height are not set.
```

```bash
object_fit is a CSS property used to control how an image or video is resized to fit its container.

fit_fill stretches the image to fill the container entirely, possibly distorting its aspect ratio.

fit_contain makes the image fit within the container while preserving its aspect ratio, leaving empty space if needed.

fit_cover fills the container while maintaining aspect ratio, cropping parts of the image if necessary.

fit_none keeps the image at its original size regardless of the container, possibly overflowing.

fit_scale_down behaves like either contain or none, whichever results in a smaller image.

used_with works on replaced elements like <img> or <video> and is often paired with width and height styles.

centered_effect can be achieved by combining object-fit with object-position to control image alignment.

visual_control helps maintain design consistency when displaying different image sizes in fixed-size containers.
```

```bash
object_position is a CSS property used to set the alignment of an image or video within its container when object-fit is applied.

default_value is "50% 50%", which centers the object both horizontally and vertically inside the container.

top_left uses object-position: top left; to align the object to the top-left corner.

bottom_right uses object-position: bottom right; to push the object to the bottom-right corner of its container.

x_y_values can be used like object-position: 30% 70%; to manually control horizontal (x) and vertical (y) alignment.

px_or_units allows using specific units like pixels or em, e.g., object-position: 20px 10px;.

works_with controls alignment only when object-fit is set to contain, cover, or none — otherwise, it's not noticeable.

cropping_control helps decide which part of the image stays visible when parts are cropped due to object-fit: cover.

fine_tuning gives designers control over visual balance when displaying media inside fixed-size containers.

```
