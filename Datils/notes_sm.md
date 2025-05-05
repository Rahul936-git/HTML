Here's the extracted and organized content from the "Class Notes.pdf" file:

### **HTML Class Notes - Structured Outline**

---

#### **1. Introduction to Web Technologies**
- **HTML**: Structure/layout
- **CSS**: Style
- **JavaScript**: Logic

---

#### **2. HTML Basics**
- **Definition**: HyperText Markup Language
  - Used to structure web pages with **tags**.
- **First HTML File**: `index.html` (default homepage name).

---

#### **3. Basic HTML Page Structure**
```html
<!DOCTYPE html>  <!-- HTML5 declaration -->
<html>
<head>
    <title>My First Page</title>  <!-- Metadata container -->
</head>
<body>
    <p>Hello World</p>  <!-- Content rendered by browser -->
</body>
</html>
```
- **Key Points**:
  - `<html>`: Root element (parent of `<head>` and `<body>`).
  - Most tags have opening/closing tags (e.g., `<p>...</p>`).
  - Void tags (no closing): `<br>`, `<img>`.
  - **Case Insensitive**: `<html>` = `<HTML>`.

---

#### **4. Common HTML Tags**
| Tag | Purpose | Example |
|------|---------|---------|
| `<h1>`-`<h6>` | Headings | `<h1>Title</h1>` |
| `<p>` | Paragraph | `<p>Text</p>` |
| `<a>` | Hyperlink | `<a href="url">Link</a>` |
| `<img>` | Image | `<img src="image.png" alt="Desc">` |
| `<br>` | Line break | `<br>` |
| `<b>`, `<i>`, `<u>` | Text formatting | `<b>Bold</b>` |
| `<big>`, `<small>` | Text size | `<big>Large</big>` |
| `<hr>` | Horizontal rule | `<hr>` |
| `<sub>`, `<sup>` | Subscript/Superscript | `H<sub>2</sub>O` |
| `<pre>` | Preformatted text | `<pre>Text</pre>` |

---

#### **5. Page Layout & Semantic Tags**
- **Semantic Structure**:

  <header>...</header>
  <main>
      <section>...</section>
      <article>...</article>
      <aside>...</aside>
  </main>
  <footer>...</footer>
  ```
- **Container Tags**:
  - **Block-level (full width)**: `<div>`, `<p>`, `<section>`.
  - **Inline (width as needed)**: `<span>`, `<a>`, `<img>`.

---

#### **6. Lists & Tables**
- **Lists**:

  <ul>  <!-- Unordered -->
      <li>Item</li>
  </ul>
  <ol>  <!-- Ordered -->
      <li>Item</li>
  </ol>
  ```
- **Tables**:

  <table>
      <caption>Student Data</caption>
      <thead>
          <tr><th>Name</th><th>Roll No</th></tr>
      </thead>
      <tbody>
          <tr><td>Shradha</td><td>1664</td></tr>
      </tbody>
  </table>
  ```
  - **Attributes**: `colspan="2"` (merge columns).

---

#### **7. Forms & Input Elements**
- **Basic Form**:

  <form action="/submit" method="post">
      <input type="text" placeholder="Name">
      <textarea placeholder="Feedback"></textarea>
      <select>
          <option value="Delhi">Delhi</option>
      </select>
      <input type="submit" value="Submit">
  </form>
  ```
- **Input Types**:
  - Text, Password, Radio, Checkbox, Date, File, etc.
- **Labels**:

  <label for="id1">
      <input type="radio" id="id1" name="option">
  </label>
  ```

---

#### **8. Multimedia & Advanced Tags**
- **Video**:

  <video src="myVid.mp4" controls></video>
  ```
  - Attributes: `autoplay`, `loop`, `width`.
- **Iframe**:

  <iframe src="external-site.html"></iframe>
  ```

---

#### **9. Key Attributes**
- **Global**:
  - `class`, `id`, `style`, `lang="en"`.
- **Anchor Tag**:
  - `target="_blank"` (open in new tab).
- **Image Tag**:
  - `height="50px"`, `width="50px"`.

---

#### **10. Best Practices**
1. **Comments**: `<!-- This is a comment -->`.
2. **Accessibility**:
   - Use `alt` for images: `<img alt="Description">`.
   - Semantic tags (`<header>`, `<nav>`).
3. **Validation**: Ensure tags are properly closed.
4. **Responsive Design**: Use viewport meta tag:
 
   <meta name="viewport" content="width=device-width, initial-scale=1">
   ```

---

#### **11. Pro Tips**
- **VS Code Shortcuts**: Use Emmet (e.g., `ul>li*5` → 5 list items).
- **Indentation**: Maintain clean, readable code.
- **Practice**: Build projects to reinforce concepts.

---

**Final Note**:  
"All the very best in your future journey."  

--- 

This structured extraction covers all key topics from the PDF, organized for clarity and quick reference. Let me know if you need further refinements!