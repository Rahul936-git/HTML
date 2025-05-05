# HTML Notes

## Basic Structure

<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <!-- Content goes here -->
</body>
</html>
```

## Common Elements

### Headings

<h1>Main Heading</h1>
<h2>Subheading</h2>
<h3>Sub-subheading</h3>
<!-- Goes up to h6 -->
```

### Paragraphs

<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

### Links

<a href="https://example.com">Visit Example</a>
```

### Images

<img src="image.jpg" alt="Description of image">
```

### Lists
**Ordered List:**

<ol>
    <li>First item</li>
    <li>Second item</li>
</ol>
```

**Unordered List:**

<ul>
    <li>Item</li>
    <li>Another item</li>
</ul>
```

### Tables

<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
    </tr>
</table>
```

## Forms

<form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name"><br>
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email"><br>
    
    <input type="submit" value="Submit">
</form>
```

### Form Elements
- `<input type="text">` - Text field
- `<input type="password">` - Password field
- `<input type="checkbox">` - Checkbox
- `<input type="radio">` - Radio button
- `<select>` - Dropdown list
- `<textarea>` - Multi-line text input
- `<button>` - Clickable button

## Semantic Elements

<header>Header content</header>
<nav>Navigation links</nav>
<main>Main content</main>
<section>Section of content</section>
<article>Independent content</article>
<aside>Side content</aside>
<footer>Footer content</footer>
```

## Attributes
Common attributes:
- `class` - For CSS styling
- `id` - Unique identifier
- `style` - Inline CSS
- `src` - Source for images/scripts
- `href` - Hyperlink reference
- `alt` - Alternative text for images

## Comments

<!-- This is a comment -->
```

## HTML5 Features
- `<video>` and `<audio>` elements
- `<canvas>` for drawing
- Local storage
- Geolocation API
- Web Workers

## Meta Tags

<meta charset="UTF-8">
<meta name="description" content="Free Web tutorials">
<meta name="keywords" content="HTML, CSS, JavaScript">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

## Best Practices
- Always include `<!DOCTYPE html>`
- Use semantic elements
- Include `alt` text for images
- Validate your HTML
- Keep nesting clean and consistent
- Separate content (HTML), presentation (CSS), and behavior (JavaScript)