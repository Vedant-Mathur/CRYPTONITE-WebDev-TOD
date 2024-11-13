# Alignment

## Aligning Items

Let’s dive into how we can control alignment within a flex container.

### Aligning Items Along the Main Axis

If you add `flex: 1` to `.item`, all the items will stretch to fill the available space equally. However, if you want the items to keep their size but distribute them differently inside the container, you can adjust the alignment using the `justify-content` property.

Try removing `flex: 1` from `.item` and adding the following to `.container`: