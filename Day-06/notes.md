# Day 6 - Semantic HTML

## What is Semantic HTML?

Semantic HTML means using HTML tags that clearly describe the purpose of the content.

It helps:
- Developers understand the code easily.
- Search engines understand webpage content.
- Improve website structure and accessibility.

Example:

### Non-Semantic HTML

```html
<div>
    Website Header
</div>
```

The browser does not know what the `<div>` represents.

### Semantic HTML

```html
<header>
    Website Header
</header>
```

The browser understands that it is a header section.

---

# Semantic HTML Tags

## 1. `<header>`

### Meaning:
The `<header>` tag represents the top section of a webpage.

### Used for:
- Website title
- Logo
- Introduction
- Navigation area

### Example:

```html
<header>
    <h1>My Portfolio</h1>
    <p>Python Full Stack Developer</p>
</header>
```

---

# 2. `<nav>`

### Meaning:
The `<nav>` tag is used to create navigation links.

### Used for:
- Home
- About
- Services
- Contact links

### Example:

```html
<nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
</nav>
```

---

# 3. `<main>`

### Meaning:
The `<main>` tag represents the main content of a webpage.

### Rules:
- A page should normally have only one `<main>` tag.
- It contains the important content of the page.

### Example:

```html
<main>
    <h2>Welcome to my website</h2>
</main>
```

---

# 4. `<section>`

### Meaning:
The `<section>` tag groups related content into different sections.

### Examples:
- About section
- Skills section
- Education section
- Experience section

### Example:

```html
<section>
    <h2>My Skills</h2>
    <p>HTML, CSS, Python</p>
</section>
```

---

# 5. `<article>`

### Meaning:
The `<article>` tag represents independent content.

The content should make sense by itself.

### Used for:
- Blog posts
- News articles
- Project details
- Product information

### Example:

```html
<article>
    <h2>AI Resume Analyzer</h2>
    <p>
        A project that analyzes resumes.
    </p>
</article>
```

---

# 6. `<aside>`

### Meaning:
The `<aside>` tag contains extra information related to the main content.

### Used for:
- Sidebar content
- Related links
- Advertisements
- Social media links

### Example:

```html
<aside>
    <h3>Follow Me</h3>
    <p>GitHub Link</p>
</aside>
```

---

# 7. `<footer>`

### Meaning:
The `<footer>` tag represents the bottom section of a webpage.

### Used for:
- Copyright information
- Contact details
- Social links

### Example:

```html
<footer>
    <p>© 2026 My Portfolio</p>
</footer>
```

---

# Difference Between `<div>` and Semantic Tags

## `<div>`

Meaning:
- A general container.
- Does not describe the content.

Example:

```html
<div>
    My Skills
</div>
```

---

## Semantic Tags

Meaning:
- Have a clear purpose.
- Describe the content.

Example:

```html
<section>
    My Skills
</section>
```

---

# Complete Website Structure Using Semantic HTML

```html
<header>
    Website Header
</header>

<nav>
    Navigation Links
</nav>

<main>

    <section>
        About Content
    </section>

    <article>
        Project Content
    </article>

    <aside>
        Extra Information
    </aside>

</main>

<footer>
    Copyright Information
</footer>
```

---

# Why Use Semantic HTML?

✅ Clean and readable code  
✅ Better SEO ranking  
✅ Easier website maintenance  
✅ Better accessibility for users  
✅ Professional webpage structure  

---

# Day 6 Practice Completed

Created:
- Header section
- Navigation menu
- Main content
- About section
- Skills section
- Project article
- Sidebar
- Footer

## Learning Outcome

After Day 6, I can create a well-structured webpage using semantic HTML tags.