## Axes
### Lesson Overview
By the end of this lesson, you will understand:
- The 2 axes in a flex container: the main axis and the cross axis.
- How to change the axes to arrange content in columns instead of rows.

### Axes
The most confusing part of flexbox is how it can work both horizontally and vertically. The direction of the flex container is controlled using the `flex-direction` property. By default, the direction is horizontal, but it can be changed to vertical.

```css
.flex-container {
  flex-direction: column;
}
