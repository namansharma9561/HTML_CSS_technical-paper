# Common CSS Structural Classes

## Introduction

CSS structural classes are classes used to organize and structure webpage layouts. They help developers create reusable, clean, and maintainable designs.

Structural classes focus mainly on:
- Layout organization
- Content alignment
- Page sections
- Grid systems
- Responsive structure

These classes are commonly used in modern frameworks such as:
- Bootstrap
- Tailwind CSS
  
---

# Importance of Structural Classes

Structural classes are important because they:

- Improve code readability
- Reduce repeated CSS
- Help create responsive layouts
- Simplify maintenance
- Improve consistency across webpages

---

# Common Structural Classes

Some widely used structural classes are:

1. container
2. wrapper
3. row
4. column
5. section
6. header
7. footer
8. sidebar
9. navbar
10. main-content

---

# 1. Container Class

The `container` class is used to center content and provide maximum width.

---

## Example

### HTML

```html
<div class="container">
    Website Content
</div>
```

### CSS

```css
.container {
    width: 90%;
    max-width: 1200px;
    margin: auto;
}
```

---

## Explanation

- `width: 90%` makes content responsive
- `max-width` prevents excessive stretching
- `margin: auto` centers the container

---

# 2. Wrapper Class

A wrapper surrounds the entire webpage or section.

---

## Example

### HTML

```html
<div class="wrapper">
    Entire Website Content
</div>
```

### CSS

```css
.wrapper {
    min-height: 100vh;
}
```

---

## Purpose

- Wraps all content
- Helps apply global layout styles
- Used for sticky footer layouts

---

# 3. Row Class

Rows organize columns horizontally.

---

## Example

### HTML

```html
<div class="row">
    <div class="col">Column 1</div>
    <div class="col">Column 2</div>
</div>
```

### CSS

```css
.row {
    display: flex;
}
```

---

## Explanation

Rows are commonly used with:
- Flexbox
- Grid systems
- Responsive layouts

---

# 4. Column Class

Columns divide webpage sections vertically.

---

## Example

### CSS

```css
.col {
    flex: 1;
    padding: 20px;
}
```

---

## Benefits

- Creates equal-width layouts
- Simplifies responsive design
- Used in card layouts and dashboards

---

# 5. Section Class

Sections divide content into logical areas.

---

## Example

### HTML

```html
<section class="hero">
    Welcome to Our Website
</section>
```

### CSS

```css
.hero {
    padding: 60px;
    background-color: lightblue;
}
```

---

## Common Website Sections

- Hero section
- About section
- Services section
- Contact section

---

# 6. Header Class

The header contains:
- Logo
- Navigation
- Branding

---

## Example

### HTML

```html
<header class="header">
    My Website
</header>
```

### CSS

```css
.header {
    background-color: black;
    color: white;
    padding: 20px;
}
```

---

# 7. Footer Class

The footer appears at the bottom of the webpage.

---

## Example

### HTML

```html
<footer class="footer">
    Copyright 2026
</footer>
```

### CSS

```css
.footer {
    text-align: center;
    padding: 20px;
    background-color: gray;
}
```

---

# 8. Sidebar Class

A sidebar usually contains:
- Navigation links
- Categories
- Ads
- Dashboard menus

---

## Example

### HTML

```html
<div class="sidebar">
    Sidebar Content
</div>
```

### CSS

```css
.sidebar {
    width: 250px;
    background-color: #f2f2f2;
}
```

---

# 9. Navbar Class

Navigation bars contain menus and links.

---

## Example

### HTML

```html
<nav class="navbar">
    <a href="#">Home</a>
    <a href="#">About</a>
</nav>
```

### CSS

```css
.navbar {
    display: flex;
    gap: 20px;
}
```

---

# 10. Main Content Class

This class contains the primary webpage content.

---

## Example

### HTML

```html
<main class="main-content">
    Main Website Data
</main>
```

### CSS

```css
.main-content {
    padding: 30px;
}
```

---

# Structural Layout Example

## HTML

```html
<div class="container">

    <header class="header">
        Header
    </header>

    <div class="row">

        <aside class="sidebar">
            Sidebar
        </aside>

        <main class="main-content">
            Main Content
        </main>

    </div>

    <footer class="footer">
        Footer
    </footer>

</div>
```

---

# Responsive Structural Layout

Structural classes are often combined with media queries.

---

## Example

```css
@media (max-width: 768px) {

    .row {
        flex-direction: column;
    }

}
```

---

# Benefits of Structural Classes

| Benefit | Description |
|---------|-------------|
| Reusability | Same structure used multiple times |
| Maintainability | Easier to update layouts |
| Responsiveness | Better mobile support |
| Readability | Organized HTML and CSS |
| Scalability | Suitable for large projects |

---

# Structural Classes in Frameworks

## Bootstrap Examples

```html
.container
.row
.col
.navbar
.card
```

---

## Tailwind CSS Examples

```html
flex
grid
container
mx-auto
w-full
```

---

# Best Practices

- Use semantic naming
- Keep structure separate from styling
- Avoid deeply nested layouts
- Use reusable layout classes
- Combine with Flexbox/Grid

---

# References

1. Bootstrap Documentation  
   https://getbootstrap.com/

2. CSS Tricks  
   https://css-tricks.com/

3. W3Schools CSS Layout  
   https://www.w3schools.com/css/
