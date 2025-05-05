Here is the extracted text from the provided PDF:

---

# Ultimate HTML Cheatsheet: 


---

## Boilerplate  

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    <!-- Body -->
</body>
</html>
```

---

## Headings  
There are six headings available in HTML, `<h1>` is the largest among all, and `<h6>` is the smallest.  

### `<h1>` Tag  

<h1>Heading 1</h1>
```

### `<h2>` Tag  

<h2>Heading 2</h2>
```

### `<h3>` Tag  

<h3>Heading 3</h3>
```

### `<h4>` Tag  

<h4>Heading 4</h4>
```

### `<h5>` Tag  

<h5>Heading 5</h5>
```

### `<h6>` Tag  

<h6>Heading 6</h6>
```

---

## Container Tags  
Container tags are the tags that contain some data such as text, image, etc.  

### `<div>` Tag  
The `<div>` tag or division tag is used to make blocks or divisions in the document.  

<div> This is div block </div>
```

### `<span>` Tag  
The `<span>` is a container for inline content.  

<span> This is span block </span>
```

### `<p>` Tag  
The `<p>` tag is used to create a paragraph in HTML.  

<p> This is a paragraph </p>
```

### `<pre>` Tag  
The `<pre>` tag represents pre-formatted text.  

<pre> Hello World </pre>
```

### `<code>` Tag  
The `<code>` tag is used to represent source codes in HTML.  

<code>
import python
</code>
```

---

## Text Formatting  
Text formatting tags are used to format text or data in HTML documents.  

### `<b>` Tag  

<b>I'm bold text</b>
```

### `<strong>` Tag  

<strong>I'm important text</strong>
```

### `<i>` Tag  

<i>I'm italic text</i>
```

### `<em>` Tag  

<em>Emphasized text</em>
```

### `<sub>` Tag  

<sub>Subscript</sub>
```

### `<sup>` Tag  

<sup>Superscript</sup>
```

---

## Lists  
Lists can be either numerical, alphabetic, bullet, or other symbols.  

### Ordered List (`<ol>`)  

<ol>
    <li>Data 1</li>
    <li>Data 2</li>
    <li>Data 3</li>
</ol>
```

### Unordered List (`<ul>`)  

<ul>
    <li>Your Data</li>
    <li>Your Data</li>
</ul>
```

---

## Media  
Media is anything that is present in digital form such as image, video, audio, etc.  

### `<audio>` Tag  

<audio controls>
    <source src="demo.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>
```

### `<img>` Tag  

<img src="Source_of_image" alt="Alternate text">
```

### `<video>` Tag  

<video width="480" height="320" controls>
    <source src="demo_move.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```

---

## Table  
A table is a collection of rows and columns.  

### Table Structure  

<table>
    <caption>Demo Table</caption>
    <thead>
        <tr>
            <th>Column1</th>
            <th colspan="2">Column2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Data1</td>
            <td>Data2</td>
            <td>Data2</td>
        </tr>
        <tr>
            <td>Data1</td>
            <td>Data2</td>
            <td>Data2</td>
        </tr>
    </tbody>
</table>
```

---

## Links  
Links are clickable text that can redirect you to some other page.  

### `<a>` Tag  

<a href="https://www.codewithharry.com/">Visit CodewithHarry.com!</a>
```

---

## Form  
The form is used to collect the user's input.  

### Basic Form  

<form action="/action.php" method="post">
    <textarea cols="20" name="comments" rows="5">Comment</textarea><br />
    <label><input name="terms" type="checkbox" value="tandc" />Accept terms</label><br />
    <input type="submit" value="Submit" />
</form>
```

### Form Elements  
- Text Input:  
  
  <input type="text" name="username" placeholder="Enter Username">
  ```
- Password Input:  
  
  <input type="password" name="password" placeholder="Enter Password">
  ```
- Checkbox:  
  
  <input type="checkbox" name="subscribe" value="yes"> Subscribe
  ```
- Radio Button:  
  
  <input type="radio" name="gender" value="male"> Male<br>
  <input type="radio" name="gender" value="female"> Female
  ```
- Submit Button:  
  
  <input type="submit" value="Submit">
  ```
- Button:  
  
  <button type="button">Click Me</button>
  ```
- Dropdown List:  
  
  <select name="country">
      <option value="usa">United States</option>
      <option value="uk">United Kingdom</option>
  </select>
  ```
- Textarea:  
  
  <textarea name="comments" rows="4" cols="50">Enter comments here</textarea>
  ```
- File Input:  
  
  <input type="file" name="fileupload">
  ```
- Range Input:  
  
  <input type="range" name="volume" min="0" max="100">
  ```
- Number Input:  
  
  <input type="number" name="quantity" min="1" max="10">
  ```
- Email Input:  
  
  <input type="email" name="email" placeholder="Enter Email">
  ```
- Search Input:  
  
  <input type="search" name="query" placeholder="Search">
  ```
- URL Input:  
  
  <input type="url" name="website" placeholder="Enter URL">
  ```
- Date Input:  
  
  <input type="date" name="birthdate">
  ```

---

## Characters & Symbols  
Some symbols are not directly present on the keyboard.  

- Copyright Symbol (©): `&copy;`  
- Less than (<): `&lt;`  
- Greater than (>): `&gt;`  
- Ampersand (&): `&amp;`  
- Dollar ($): `&dollar;`  

---

## Semantic Elements  
Semantic elements convey their meaning and purpose clearly.  

### `<section>` Tag  

<section>This is a section</section>
```

### `<article>` Tag  

<article> Enter your data here </article>
```

### `<aside>` Tag  

<aside> Your data </aside>
```

---

## Meta Tags  

<meta name="description" content="This is a description of the page">
<meta name="keywords" content="HTML, CSS, JavaScript">
<meta name="author" content="Author Name">
```

---

## CSS Integration  

<style>
    body { background-color: lightblue; }
</style>
<link rel="stylesheet" type="text/css" href="styles.css">
```

---

## Accessibility  

<img src="image.jpg" alt="Description of Image">
<label for="name">Name:</label> <input type="text" id="name" name="name">
```

---

## Responsive Design  

<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
    @media (max-width: 600px) {
        body { font-size: 18px; }
    }
</style>
```

---

## JavaScript Integration  

<script>
    alert('Hello, World!');
</script>
<script src="script.js"></script>
```

---

## Comments  

<!-- This is a comment -->
```

---

## Other Tips for HTML Beginners  
1. **Use a Modern Text Editor** (e.g., VS Code with Emmet).  
2. **Indent Your Code** for readability.  
3. **Always Close Tags** to avoid rendering issues.  
4. **Learn CSS and JavaScript** for dynamic websites.  
5. **Practice Regularly** to improve skills.  
6. **Learn Responsive Design** for all devices.  

---
 

--- 

This extracted text covers all the essential HTML elements, tags.