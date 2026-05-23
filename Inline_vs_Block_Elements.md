
# Inline versus Block Elements

---

# Block Elements

A block element always starts on a new line and takes up the full width available.

## Characteristics of Block Elements

- Starts on a new line
- Occupies full available width
- Can contain other block and inline elements
- Height and width can be controlled
- Margin and padding work fully

---

# Common Block Elements

Examples include:

```html
<div>
<p>
<h1> to <h6>
<section>
<article>
<header>
<footer>
<nav>
<ul>
<li>
```

---

# Example of Block Elements

## HTML

```html
<div>First Block Element</div>
<div>Second Block Element</div>
<p>This is a paragraph.</p>
```

## Output Behavior

```text
First Block Element

Second Block Element

This is a paragraph.
```

Each element appears on a separate line.

---

# Styling Block Elements

## CSS

```css
div {
    background-color: lightblue;
    margin: 10px;
    padding: 20px;
}
```

## Explanation

- `margin` creates space outside the element
- `padding` creates space inside the element
- Block elements can have custom width and height

---

# Inline Elements

Inline elements only take up as much width as necessary.

They do not start on a new line.

---

# Characteristics of Inline Elements

- Does not begin on a new line
- Occupies only required width
- Appears within text flow
- Width and height usually cannot be changed
- Vertical margin has limited effect

---

# Common Inline Elements

Examples include:

```html
<span>
<a>
<strong>
<em>
<label>
<small>
<img>
```

---

# Example of Inline Elements

## HTML

```html
<span>Hello</span>
<span>World</span>
<a href="#">Click Here</a>
```

## Output Behavior

```text
Hello World Click Here
```

All elements appear on the same line.

---

# Styling Inline Elements

## CSS

```css
span {
    color: blue;
    background-color: lightyellow;
}
```

---

# Major Differences Between Inline and Block Elements

| Feature | Block Element | Inline Element |
|---------|---------------|----------------|
| Starts on New Line | Yes | No |
| Width | Full Width | Content Width |
| Height/Width Control | Yes | Limited |
| Margin/Padding | Full Support | Partial Support |
| Layout Usage | Structure/Layout | Text Formatting |

---

# Inline-Block Elements

CSS also provides a hybrid display type called `inline-block`.

It combines features of both inline and block elements.

## Properties

- Appears inline
- Allows width and height
- Supports margin and padding fully

---

# Example of Inline-Block

## HTML

```html
<button>Button 1</button>
<button>Button 2</button>
```

## CSS

```css
button {
    display: inline-block;
    width: 120px;
    height: 50px;
    margin: 10px;
}
```

Buttons appear side by side while allowing size control.

---

# display Property

The `display` property controls element behavior.

## Common Values

### Block

```css
display: block;
```

### Inline

```css
display: inline;
```

### Inline-Block

```css
display: inline-block;
```

### None

```css
display: none;
```

Hides the element completely.

---

# Practical Usage

## Block Elements Are Used For

- Layout sections
- Containers
- Navigation bars
- Page structure

Example:

```html
<div class="container">
    <header>Header</header>
    <main>Main Content</main>
    <footer>Footer</footer>
</div>
```

---

## Inline Elements Are Used For

- Text formatting
- Hyperlinks
- Icons
- Small content pieces

Example:

```html
<p>
    This is <strong>important</strong> text.
</p>
```

---

# Converting Between Types

An element’s display type can be changed using CSS.

## Make Inline Element Behave Like Block

```css
span {
    display: block;
}
```

## Make Block Element Behave Like Inline

```css
div {
    display: inline;
}
```

# References

1. MDN Web Docs  
   https://developer.mozilla.org/

2. W3Schools HTML Display  
   https://www.w3schools.com/html/html_blocks.asp

3. CSS Tricks  
   https://css-tricks.com/
