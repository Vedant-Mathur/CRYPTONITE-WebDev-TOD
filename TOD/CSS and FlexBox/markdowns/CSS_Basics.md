# Intro To CSS

### Basic CSS Syntax
CSS consists of rules made up of a selector and declarations (property–value pairs). Key concepts:

1. **Selectors** – Identify which HTML elements to style.
2. **Properties** – Define specific styles for selected elements.

### Selectors
Common selectors include:
- **Universal selector (`*`)**: Applies to all elements.
- **Type selector (`element`)**: Targets all instances of a specific element (e.g., `div`).
- **Class selector (`.className`)**: Targets elements with a specific class attribute.
- **ID selector (`#idName`)**: Targets a unique element by its ID.
- **Grouping selector**: Allows applying the same style to multiple selectors (e.g., `.read, .unread`).
- **Chaining selectors**: Combines multiple selectors to target elements with shared characteristics (e.g., `.subsection.header`).
- **Descendant combinator**: Targets elements nested within a specific ancestor.

### Key CSS Properties
- **color** and **background-color**: Set text and background colors using names, HEX, RGB, or HSL values.
- **font-family** and **font-size**: Define fonts and their sizes.
- **font-weight**: Adjusts text boldness.
- **text-align**: Aligns text horizontally.
- **height** and **width**: Control element dimensions, especially useful for images.

### Adding CSS to HTML
1. **External CSS**: Create a `.css` file and link it in the HTML `<head>`. This method keeps HTML and CSS separate and is most scalable.
2. **Internal CSS**: Use `<style>` tags within the HTML `<head>`, helpful for single-page styles.
3. **Inline CSS**: Add `style=""` directly in an element’s tag. Though not preferred, it’s useful for one-off styles.
    
