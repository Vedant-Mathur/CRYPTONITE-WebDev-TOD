## Block and Inline
### Block vs. Inline Elements
Most of the elements we've covered so far are **block elements**. By default, these elements:
- Use `display: block`.
- Stack vertically, with each new element appearing on a new line.

**Inline elements**, on the other hand:
- Do not start on a new line.
- Line up horizontally with surrounding elements.
  
A common example of an inline element is the `<a>` (link) tag. When used within a paragraph, it aligns with the surrounding text, acting like part of the same line. Note that padding and margin behave differently on inline elements, and excessive padding/margin on inline elements is generally avoided.

### The Middle Ground: `inline-block`
Elements with `display: inline-block`:
- Behave like inline elements but with block-level padding and margin.
- Are useful for lining up elements horizontally without starting a new line.

While `inline-block` can help align boxes in a row, **flexbox** (covered in the next lesson) is typically more efficient for arranging multiple boxes.

### Divs and Spans
**Div** and **span** elements are essential to understanding block and inline behavior:
- They provide **generic containers** with no semantic meaning, used primarily for styling and grouping.
- `div` is a **block-level** element by default. It’s commonly used as a container for grouping other elements, allowing us to apply styles to specific sections of the page.
- `span` is an **inline-level** element by default. It’s often used to group small chunks of text or inline HTML elements for styling purposes. Use `span` when no other semantic HTML element is appropriate.

These elements act as flexible “hooks” in HTML, enabling developers to apply CSS classes and IDs for styling, positioning, or grouping related elements.
