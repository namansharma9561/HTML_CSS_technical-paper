# Flexbox and CSS Grid

## Introduction

Flexbox and CSS Grid are modern CSS layout systems used to create responsive and organized webpage layouts.

- Flexbox is mainly used for one-dimensional layouts.
- Grid is used for two-dimensional layouts.

---

# Flexbox

Flexbox helps align items in rows or columns.

---

# Basic Flexbox Example

## CSS

```css
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
}
```

## HTML

```html
<div class="container">

    <div>Box 1</div>
    <div>Box 2</div>
    <div>Box 3</div>

</div>
```

---

# Common Flexbox Properties

| Property | Purpose |
|----------|----------|
| justify-content | Horizontal alignment |
| align-items | Vertical alignment |
| flex-direction | Row or column layout |
| gap | Space between items |

---

# CSS Grid

CSS Grid is used for row and column layouts.

---

# Basic Grid Example

## CSS

```css
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}
```

## HTML

```html
<div class="container">

    <div>Item 1</div>
    <div>Item 2</div>
    <div>Item 3</div>

</div>
```

---

# Common Grid Properties

| Property | Purpose |
|----------|----------|
| grid-template-columns | Defines columns |
| grid-template-rows | Defines rows |
| gap | Space between grid items |
| place-items | Align items |

---

# Flexbox vs Grid

| Feature | Flexbox | Grid |
|---------|----------|------|
| Layout Type | One-dimensional | Two-dimensional |
| Best For | Small components | Full page layouts |
| Direction | Row or column | Rows and columns |

---

# Responsive Example

```css
.container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
}
```

This automatically adjusts columns based on screen size.

---

# Advantages

## Flexbox

- Easy alignment
- Simple layouts
- Flexible spacing

## Grid

- Powerful page layouts
- Better control over rows and columns
- Responsive design support

---

# References

1. MDN Web Docs  
   https://developer.mozilla.org/

2. CSS Tricks Flexbox Guide  
   https://css-tricks.com/

3. CSS Tricks Grid Guide  
   https://css-tricks.com/
