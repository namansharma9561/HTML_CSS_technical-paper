# CSS Responsive Queries

## Introduction

CSS Responsive Queries, also called Media Queries, are used to make websites responsive on different screen sizes such as mobile, tablet, and desktop.

They allow developers to apply different styles based on device width, height, or orientation.

---

# Media Query Syntax

```css
@media (max-width: 768px) {

    body {
        background-color: lightgray;
    }

}
```

---

# Common Breakpoints

| Device | Width |
|--------|--------|
| Mobile | 480px |
| Tablet | 768px |
| Laptop | 1024px |
| Desktop | 1200px |

---

# Example of Responsive Layout

## CSS

```css
.container {
    display: flex;
}

@media (max-width: 600px) {

    .container {
        flex-direction: column;
    }

}
```

---

# Explanation

- Large screens → items appear in a row
- Small screens → items stack vertically

---

# Responsive Image Example

```css
img {
    max-width: 100%;
    height: auto;
}
```

This prevents images from overflowing on small devices.

---

# Types of Media Queries

## max-width

Applies styles below a certain width.

```css
@media (max-width: 768px)
```

---

## min-width

Applies styles above a certain width.

```css
@media (min-width: 768px)
```

---

# Importance of Responsive Queries

- Improves mobile experience
- Makes websites device-friendly
- Enhances accessibility
- Improves SEO rankings

---

# Best Practices

- Use flexible layouts
- Test on multiple devices
- Use relative units like `%` and `rem`
- Avoid fixed widths

---

# References

1. MDN Web Docs  
   https://developer.mozilla.org/

2. W3Schools Media Queries  
   https://www.w3schools.com/css/

3. CSS Tricks  
   https://css-tricks.com/
