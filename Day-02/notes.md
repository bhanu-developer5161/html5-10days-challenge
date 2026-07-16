# Day 2 Notes - Links, Images & Navigation

## What I Learned
- How to create hyperlinks using the `<a>` tag.
- How to display images using the `<img>` tag.
- How to create navigation menus using links.
- Difference between absolute and relative paths.

---

## Tags Covered

| Tag | Description |
|------|-------------|
| `<a>` | Creates hyperlinks |
| `<img>` | Displays an image |
| `<nav>` | Defines a navigation section |

---

## Anchor Tag

### Syntax

```html
<a href="https://www.google.com">Visit Google</a>
```

### Attributes
- `href` – Specifies the destination URL.
- `target="_blank"` – Opens the link in a new tab.
- `title` – Displays a tooltip when hovering over the link.

Example:

```html
<a href="https://github.com" target="_blank" title="GitHub">
    GitHub
</a>
```

---

## Image Tag

### Syntax

```html
<img src="images/html.png" alt="HTML Logo" width="300">
```

### Attributes
- `src` – Image path.
- `alt` – Alternative text if the image cannot be displayed.
- `width` – Image width.
- `height` – Image height.

---

## Navigation

Example:

```html
<nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="contact.html">Contact</a>
</nav>
```

---

## Relative vs Absolute Path

### Relative Path

```html
<img src="images/logo.png">
```

### Absolute Path

```html
<img src="https://example.com/logo.png">
```

---

## Best Practices
- Use meaningful link text.
- Always provide the `alt` attribute for images.
- Organize navigation inside the `<nav>` element.
- Use relative paths for project files whenever possible.

---

## Practice Completed
- Created internal links.
- Added external links.
- Inserted local and online images.
- Built a simple navigation menu.

---

## Common Mistakes
- Forgetting the `href` attribute.
- Missing the `alt` attribute on images.
- Using incorrect file paths.
- Forgetting to close the `<a>` tag.

---

## Next Topic
HTML Lists and Tables.