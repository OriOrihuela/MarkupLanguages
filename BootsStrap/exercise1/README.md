# exercise1 
## Make a page with a customizable design based on its resolution. This one
**The page will have 3 boxes with id A, B, C. The behavior of the boxes will be the following**:
- If the page is displayed on a `400px` maximum screen, the 3 boxes they will appear one on top of the other.

- If the screen is between `401px` and `800px`, the boxes A and B will be displayed in the upper part occupying a width of `50%` (it may be necessary to adjust a% little lower). And box C will appear below these 2 boxes occupying everything the width of the screen.

- If the screen has 801px or more A, B and C will be displayed next to each other. A occupying `20%`, B another `20%` and C `58%`.

Use div in html. In order to solve it, you must use only one css with `@media screen and` (...).