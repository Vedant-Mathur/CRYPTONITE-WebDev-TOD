## Flexbox
**Foundations Course**

### Introduction
Over the years, web developers have had many ways to position elements on a page, with new methods constantly evolving. **Flexbox** brought a revolutionary change in CSS layout, making positioning more efficient and adaptable. While some resources treat it as an advanced topic, flexbox is now a standard tool in web development. Let’s dive in to make it one of your primary layout techniques!

### Lesson Overview
In this lesson, you’ll learn:
- How to position elements using **flexbox**.
- The difference between **flex containers** and **flex items**.
- How to create versatile components and layouts beyond simple stacking and centering.

### Before We Get Started
Flexbox can seem complex at first, so you’ll want to rely on your **developer tools** to inspect and debug as you go. Flexbox involves more configuration options than some of the simpler CSS concepts we’ve covered, but hands-on experimentation will make a huge difference.

As you proceed, interact with all the embedded code examples. You’ll probably want to refer back to these concepts and resources later, so take your time to explore each example!

### Let’s Flex!
Flexbox arranges items in rows or columns that can **flex**—grow or shrink—according to specified rules. Let’s start with a quick demonstration.

In the example below, uncomment the two `flex`-related CSS declarations by removing the `/*` and `*/` tags to activate the code. You’ll see all three divs arrange horizontally. Adjusting the results frame with the “1x,” “.5x,” and “.25x” buttons shows how the divs flex, filling the available space and resizing automatically to fit.

If you add another div inside the `.flex-container` in the HTML, it will also line up with the others and adjust to fit the available space. For larger view examples, feel free to click “Edit on CodePen” or “Fork on CodePen” to open it in a full-sized window.

### Flex Containers and Flex Items
Flexbox isn’t just one CSS property but a toolbox of properties that control element alignment and positioning. Flexbox properties can apply to either:
- **The flex container**: Any element with `display: flex` applied to it.
- **The flex items**: Any elements that are direct children of the flex container.

It’s important to understand that any element can be both a **flex container** and a **flex item**. This means you can apply `display: flex` to an item within another flex container, creating nested flex layouts for more complex designs.

### Nesting Flex Containers
Building complex layouts often involves nesting multiple flex containers. You’ll use flexbox to control the size, alignment, and placement of items, allowing for intricate yet flexible designs.

Flexbox’s versatility can produce impressive layouts, like the one below, achieved solely with flex properties.

_Flexbox in action!_
