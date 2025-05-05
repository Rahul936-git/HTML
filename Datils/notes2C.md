

---

# 📘 **Complete HTML Notes**

---

## ✅ **1. Introduction to HTML**

* **HTML** stands for **HyperText Markup Language**.
* It is the standard markup language for creating web pages.
* HTML describes the structure of a webpage using **tags**.

---

## ✅ **2. Basic HTML Document Structure**

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Page Title</title>
</head>
<body>
  <h1>Hello, World!</h1>
  <p>This is a paragraph.</p>
</body>
</html>
```

---

## ✅ **3. HTML Tags Overview**

### 📍 Headings

```html
<h1>Heading 1</h1> <!-- Largest -->
<h6>Heading 6</h6> <!-- Smallest -->
```

### 📍 Paragraph & Text Formatting

```html
<p>This is a paragraph.</p>
<b>Bold</b> <i>Italic</i> <u>Underline</u> <strong>Strong</strong>
```

### 📍 Line Breaks and Horizontal Lines

```html
<br> <!-- Line Break -->
<hr> <!-- Horizontal Line -->
```

---

## ✅ **4. Lists**

### 📍 Unordered List

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
```

### 📍 Ordered List

```html
<ol>
  <li>First</li>
  <li>Second</li>
</ol>
```

---

## ✅ **5. Links and Images**

### 📍 Anchor Tag

```html
<a href="https://example.com" target="_blank">Visit Example</a>
```

### 📍 Image Tag

```html
<img src="image.jpg" alt="An image" width="300" height="200">
```

---

## ✅ **6. Tables**

```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>John</td>
    <td>25</td>
  </tr>
</table>
```

---

## ✅ **7. Forms**

```html
<form action="/submit" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required>
  
  <label for="email">Email:</label>
  <input type="email" id="email" name="email">

  <input type="submit" value="Submit">
</form>
```

### 📍 Form Input Types

* `text`, `password`, `email`, `radio`, `checkbox`, `submit`, `reset`, `file`, `date`, `number`

---

## ✅ **8. Semantic HTML Elements**

| Tag         | Description                         |
| ----------- | ----------------------------------- |
| `<header>`  | Top section of a webpage            |
| `<nav>`     | Navigation menu                     |
| `<main>`    | Main content of the document        |
| `<section>` | Thematic grouping of content        |
| `<article>` | Independent, self-contained content |
| `<aside>`   | Sidebar or related content          |
| `<footer>`  | Footer of the document              |

---

## ✅ **9. Media Elements**

```html
<video controls>
  <source src="movie.mp4" type="video/mp4">
</video>

<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
</audio>
```

---

## ✅ **10. Iframes**

```html
<iframe src="https://example.com" width="600" height="400"></iframe>
```

---

## ✅ **11. HTML Entities**

| Symbol | Code     |
| ------ | -------- |
| `<`    | `&lt;`   |
| `>`    | `&gt;`   |
| `&`    | `&amp;`  |
| `"`    | `&quot;` |
| `'`    | `&apos;` |

---

## ✅ **12. HTML Comments**

```html
<!-- This is a comment -->
```

---

## ✅ **13. Linking CSS and JavaScript**

### 📍 CSS (Internal, External)

```html
<!-- External -->
<link rel="stylesheet" href="style.css">

<!-- Internal -->
<style>
  body {
    background-color: lightblue;
  }
</style>
```

### 📍 JavaScript

```html
<script>
  alert("Hello, JavaScript!");
</script>

<!-- Or link external -->
<script src="script.js"></script>
```

---

## ✅ **14. Block vs Inline Elements**

### 📍 Block Elements

* `<div>`, `<p>`, `<h1>`–`<h6>`, `<ul>`, `<ol>`, `<section>`, `<article>`

### 📍 Inline Elements

* `<span>`, `<a>`, `<img>`, `<b>`, `<i>`, `<strong>`, `<em>`

---

## ✅ **15. HTML5 New Elements**

* Semantic Tags: `<main>`, `<section>`, `<article>`, `<aside>`, `<nav>`, `<header>`, `<footer>`
* Media Tags: `<audio>`, `<video>`, `<source>`, `<track>`
* Form Enhancements: `required`, `placeholder`, `autofocus`, `pattern`

---

## ✅ **16. Accessibility in HTML**

* Use `alt` attributes for images.
* Use semantic tags for screen readers.
* Use `aria-` attributes where needed.

---

Let me know if you'd like this in **PDF format**, or want a **practice worksheet** or **example project**.
