```bash
grid: is a layput that has rows and columns

```

## To create a grid

```bash
display:grid Set display property to grid <- 1st step

grid-template-columns:_100px_100px Set how many columns our grid has, they define how wide our grid columns are. 1 by 2 grid <-2nd step

Note: divs are block elements by default and take the whole width but when they are inside a grid, they are put into the grid so they take the entire column.

Second_note: There are no extra spaces between the 2 columns

third_note: Add a paragraph to the second div, it makes the second div have more content than the first but both divs are vertically alignd unlike inline block, they handle alignment better.

4th_note: When we have more elements than columns, it wraps around and creates new rows

grid-template-columns:_100px_1fr"
1fr(free_space):
1fr means: "take up 1 remaining free space"

Example:
grid-template-columns: 100px 1fr;

The first column is fixed at 100px.
The second column takes up all the space that’s left over.
If the container is 300px wide,
the second column will be 200px (300px - 100px = 200px).

Bonus:
You can use multiple fr units like:
grid-template-columns: 1fr 2fr;
This means:
- First column = 1 part
- Second column = 2 parts (twice as wide as the first one)

```
