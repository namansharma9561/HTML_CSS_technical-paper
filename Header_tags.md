# Common Header Meta Tags

## Introduction

Meta tags are HTML elements placed inside the `<head>` section of a webpage. They provide information about the webpage to browsers and search engines.

Meta tags improve:
- SEO
- Responsiveness
- Browser compatibility
- Accessibility

---

# Basic Structure

```html
<head>

    <meta charset="UTF-8">

</head>
```

---

# 1. Charset Meta Tag

Defines character encoding.

## Example

```html
<meta charset="UTF-8">
```

### Importance

- Supports multiple languages
- Prevents character display issues

---

# 2. Viewport Meta Tag

Used for responsive design.

## Example

```html
<meta name="viewport"
      content="width=device-width, initial-scale=1.0">
```

### Importance

- Makes webpages mobile-friendly
- Adjusts layout based on screen size

---

# 3. Description Meta Tag

Provides webpage description.

## Example

```html
<meta name="description"
      content="Learn HTML and CSS">
```

### Importance

- Improves SEO
- Appears in search engine results

---

# 4. Keywords Meta Tag

Defines important webpage keywords.

## Example

```html
<meta name="keywords"
      content="HTML, CSS, JavaScript">
```

---

# 5. Author Meta Tag

Defines webpage author.

## Example

```html
<meta name="author"
      content="Naman Sharma">
```

---

# 6. Refresh Meta Tag

Automatically refreshes webpage.

## Example

```html
<meta http-equiv="refresh"
      content="30">
```

Refreshes page every 30 seconds.

---

# Complete Example

```html
<head>

    <meta charset="UTF-8">

    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">

    <meta name="description"
          content="Frontend Tutorial">

    <meta name="keywords"
          content="HTML, CSS, JavaScript">

    <meta name="author"
          content="Naman Sharma">

</head>
```

---

# Importance of Meta Tags

- Better SEO
- Mobile responsiveness
- Improved browser support
- Better webpage information handling

---

# Conclusion

Header meta tags are essential for modern webpages. They improve search engine optimization, responsiveness, and browser compatibility.

---

# References

1. MDN Web Docs  
   https://developer.mozilla.org/

2. W3Schools HTML Meta Tags  
   https://www.w3schools.com/

3. HTML Living Standard  
   https://html.spec.whatwg.org/
