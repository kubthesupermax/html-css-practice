## Css Syntax rules

```bash
Css_selector - It tells the computer which elements we are targeting with our css code
css_property - left of the colon and tells the computer what we are changing
css_value - right of the colon and tells the computer what we are changing to.

px - Unit of measurement

class_attribute lets us label html elements, to target a class in css we use . then the class name immediately after it, no space. Multiple elements can have the same class

margin space around an element
```

```css
height: 36px;
width: 70px;
/* Border radius can be */
border-radius: 18px; /* Which is half of the height or*/
border-radius: 35px; /* Which is half of the width*/
```

```bash
pseudo-class Adds extra styles in a certain situation. eg Hover, active
.css-selector:hover Styles take effect when we hover
.css-selector:active Styles take effect when we click on the element

opacity Sets transparency level (0 = invisible, 1 = visible)
opacity:1 Fully visible
opacity:0.5 Half transparent
opacity:0 Fully invisible

transition Adds smooth animation between property changes You can also add more (like timing function and delay), but the two core values are:
transition: property duration
property  What CSS property to animate (e.g., background, transform)
duration  How long the animation lasts (e.g., 0.3s, 1s)
transition: background 0.5s;


box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.15);
box-shadow: offset-x offset-y blur-radius color;
5px   Horizontal offset → shadow moves 5px to the right
5px   Vertical offset → shadow moves 5px down
10px  Blur radius → softens the shadow edges
rgba(0, 0, 0, 0.15)  Shadow color (black with 15% opacity)
```

The issue of button misalignment on the same line arises due to differences in the styles applied to each button.

- **Height**: The `.subscribe-button` and `.tweet-button` have the same height (`36px`), but the `.join-button` has a different height because of the larger padding values for `top` and `bottom` (`20px` padding on top, with no explicit height). This causes the buttons to not align properly in terms of vertical positioning.
- **Padding**: The padding values across the buttons are inconsistent.
  - `.subscribe-button` has `padding-top: 10px; padding-bottom: 10px;`
  - `.join-button` has `padding-top: 20px; padding-bottom: 20px;`
  - `.tweet-button` has no top and bottom padding explicitly, which affects the perceived height due to its font size.
- **Font Size**: The `.tweet-button` has a `font-size: 15px;` while the others do not specify a font size, meaning the font size for the `.subscribe-button` and `.join-button` may default to a smaller value. The differing font sizes also lead to different vertical alignment and overall size.

### Why the text is aligned well:

The text inside each button is likely vertically aligned due to the consistent use of padding and height in `.subscribe-button` and `.tweet-button`, where the text is centered properly within the button box. The issue with alignment is more due to the box sizes themselves not matching across buttons.

### Solution:

To ensure proper alignment of all the buttons on the same line, consider these changes:

- Set the **same height** for all buttons (`height: 36px` for all).
- Make padding consistent across buttons. For example, use `padding-top: 10px; padding-bottom: 10px;` for all.
- Apply a **consistent font size** across buttons to make the text appear aligned vertically.
- If needed, use `display: inline-block;` on the button elements to ensure they line up horizontally.

By standardizing these properties, you’ll have the buttons lined up properly.

The issue of button misalignment on the same line can also be related to vertical alignment. When using `vertical-align: top;`, the elements are aligned with their top edges aligned, which might cause some buttons to appear misaligned due to differences in their heights, padding, or font sizes.

- **Vertical Align**: When using `vertical-align: top;`, the buttons' top edges are aligned with the highest element in the group, but this does not account for their different heights or padding. For example, if one button has extra padding or a larger font size, it may cause the buttons to appear misaligned vertically.
- **Height and Padding**: If buttons have inconsistent heights or padding values, `vertical-align: top;` will align the tops of the buttons but not necessarily their content or bottoms. This can make the buttons look unaligned even though their top edges are aligned.

### Why the text is aligned well:

The text is typically centered within the buttons, and when the `vertical-align: top;` property is used, it only affects the position of the buttons themselves, not the text. This can cause misalignment if the button dimensions differ.

### Solution:

To fix vertical alignment issues when using `vertical-align: top;`, consider the following:

- Ensure **consistent heights** and **padding values** across all buttons.
- Use a **consistent font size** to prevent one button from appearing larger than the others.
- If you still want to use `vertical-align: top;`, apply it to all buttons in a way that accounts for these consistent sizes and paddings, and make sure to set a uniform height for all buttons.

By standardizing the button properties, the vertical alignment will appear as expected.

```bash
border-width: was set to 1px so join button was a px taller than subscribe and tweet buttons so made padding on the vertical axis reduced by 1
```
