## Growing and Shrinking
### The Flex Shorthand
The `flex` property is shorthand for **3 properties** that define how flex items size themselves within a flex container:
1. `flex-grow`
2. `flex-shrink`
3. `flex-basis`

Using shorthand properties like `flex` allows for concise code. The shorthand `flex: 1` is equivalent to `flex-grow: 1; flex-shrink: 1; flex-basis: 0;`. Here’s a closer look at each of these properties.

#### Flex-Grow
- **Definition**: Controls how much a flex item will grow relative to other items in the container. 
- **Example**: `flex-grow: 1` on multiple items causes them to grow equally. If one item has `flex-grow: 2`, it will grow to be twice as large as others with `flex-grow: 1`.

#### Flex-Shrink
- **Definition**: Determines how much a flex item will shrink if the container is too small.
- **Example**: If you set `width: 100px` on each item but make the container smaller than their total width, `flex-shrink` controls how much they shrink to fit.

#### Flex-Basis
- **Definition**: Sets the initial size of a flex item, providing a starting point for flex-grow and flex-shrink.
- **Example**: The shorthand defaults to `flex-basis: 0`, which ignores any `width` value. Changing it to `auto` tells the item to check for a `width` value.

### Important Note About Flex-Basis
By default, `flex-basis` is set to `auto`, but using `flex: 1` interprets it as `flex-basis: 0`. For better control, you can set `flex: 1 1 auto`.

### Flex: Auto
The shorthand `flex: auto` (or `flex: 1 1 auto`) combines `flex-grow: 1`, `flex-shrink: 1`, and `flex-basis: auto`. Though it may seem like the default, `flex: auto` is not the default value.

### In Practice
Commonly used shorthand declarations include:
- `flex: 1;` for equal growth.
- `flex-shrink: 0;` to prevent an item from shrinking.

Advanced layouts may use different ratios, but generally, these simpler declarations cover most use cases.
