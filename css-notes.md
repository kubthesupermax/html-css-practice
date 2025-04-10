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
