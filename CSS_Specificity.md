
# CSS Specificity

## Introduction

CSS specificity determines which CSS rule is applied when multiple rules target the same element. The rule with higher specificity gets priority.

---

# Specificity Hierarchy

CSS applies styles in the following order:

1. Inline Styles
2. ID Selectors
3. Class Selectors
4. Element Selectors

---

# 1. Inline Styles

Inline styles have the highest priority.

### Example

```html
<h1 style="color:red;">
    Hello
</h1>
```

Specificity Value:

```text
1000
```

---

# 2. ID Selectors

ID selectors are more specific than classes.

### CSS

```css
#title {
    color: blue;
}
```

### HTML

```html
<h1 id="title">
    Heading
</h1>
```

Specificity Value:

```text
100
```

---

# 3. Class Selectors

Classes have lower priority than IDs.

### CSS

```css
.heading {
    color: green;
}
```

Specificity Value:

```text
10
```

---

# 4. Element Selectors

Element selectors have the lowest priority.

### CSS

```css
h1 {
    color: orange;
}
```

Specificity Value:

```text
1
```

---

# Example of Specificity

### CSS

```css
h1 {
    color: red;
}

.heading {
    color: blue;
}

#title {
    color: green;
}
```

### HTML

```html
<h1 id="title" class="heading">
    CSS Specificity
</h1>
```

### Result

```text
Green Color
```

Reason:
The ID selector has the highest specificity.

---

# !important Rule

The `!important` keyword overrides normal specificity.

### Example

```css
h1 {
    color: red !important;
}
```

Use carefully because it makes debugging difficult.

---

# Best Practices

- Keep selectors simple
- Avoid overusing IDs
- Avoid excessive nesting
- Use `!important` only when necessary

---

# Importance of CSS Specificity

- Prevents style conflicts
- Helps manage large projects
- Improves maintainability
- Makes debugging easier

---


# References

1. MDN Web Docs  
   https://developer.mozilla.org/

2. W3Schools CSS Specificity  
   https://www.w3schools.com/css/

3. CSS Tricks  
   https://css-tricks.com/
