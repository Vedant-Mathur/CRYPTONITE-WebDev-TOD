## CSS Cascade Summary
### The Cascade of CSS
CSS often contains rules that overlap or conflict. The cascade determines which rules actually style an element. Factors in the cascade include specificity, inheritance, and the order of rules. Understanding these principles can help prevent unexpected styling issues.

### Specificity
A more specific CSS declaration overrides a less specific one. Here’s the hierarchy for specificity:
1. **ID selectors** (most specific)
2. **Class selectors**
3. **Type selectors**

When elements have multiple conflicting declarations, CSS applies the declaration with the highest specificity. For instance:
```html
<div class="main">
  <div class="list subsection">Red text</div>
</div>
