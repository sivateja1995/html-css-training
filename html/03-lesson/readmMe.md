# Semantic vs Non-Semantic HTML Tags

Understanding the difference between semantic and non-semantic tags is essential for writing clean, accessible, and SEO-friendly HTML.

---

## ✅ Semantic HTML Tags

Semantic tags clearly describe their meaning to both the **browser** and the **developer**.

| Tag            | Description                                  |
| -------------- | -------------------------------------------- |
| `<header>`     | Represents a header section                  |
| `<footer>`     | Represents a footer section                  |
| `<main>`       | Represents the main content                  |
| `<section>`    | Represents a section of related content      |
| `<article>`    | Represents a self-contained piece of content |
| `<nav>`        | Represents navigation links                  |
| `<aside>`      | Represents content aside from the main       |
| `<figure>`     | Represents media content like images/videos  |
| `<figcaption>` | Represents a caption for `<figure>` content  |
| `<address>`    | Represents contact information               |
| `<time>`       | Represents a specific time or date           |

### Example:

```html
<article>
    <header>
        <h1>Blog Post Title</h1>
        <p>By Author</p>
    </header>
    <p>This is the main content of the blog post.</p>
    <footer>Published on June 27, 2025</footer>
</article>
```

---

# ❌ Non-Semantic HTML Tags

Non-semantic HTML tags **do not provide any meaning** about the content inside them. They are used purely for **layout** or **styling**, and require additional context (like classes or ARIA labels) to convey structure or meaning to browsers and assistive technologies.

---

## 🔍 What Are Non-Semantic Tags?

Non-semantic tags are **generic containers** that do not describe the role of their content. They are mostly used with CSS or JavaScript to achieve layout or formatting.

---

## Common Non-Semantic Tags

| Tag      | Description                                 |
|----------|---------------------------------------------|
| `<div>`  | Generic block-level container               |
| `<span>` | Generic inline-level container              |
| `<b>`    | Makes text bold, no semantic meaning        |
| `<i>`    | Makes text italic, no semantic meaning      |
| `<font>` | *(Deprecated)* Changes text appearance      |

---

## Example Usage

```html
<div class="card">
    <span class="label">User Name:</span>
    <span class="value">John Doe</span>
</div>
```
