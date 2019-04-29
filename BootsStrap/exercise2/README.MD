# exercise2
## Make a page that adapts easily to any resolution. 
This page will have 4 boxes with id A, B, C and D. Use div in html.
- For all cases there is a container of 4 rows (all of the same height) and 3 columns (20%, 20% and 60% widths).

In order to do so, in the CSS you must use the following expressions:
- `grid-template-rows: 25% 25% 25% 25%;`
- `grid-template-columns: 20% 20% 60%;`

**If the screen has less than `800px`, there must be these properties in the CSS**:
- `grid-row: 1;`
- `grid-column: 1/4;`
