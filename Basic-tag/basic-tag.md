# 🌐 Basic HTML Tags

> A beginner-friendly guide to **30 commonly used HTML tags**, including their purpose, syntax, and examples.

---

## 📖 Definition

**HTML (HyperText Markup Language)** is the standard markup language used to create and structure content on web pages.

HTML uses **elements and tags** to define different types of content such as headings, paragraphs, links, images, lists, tables, and forms.

---

# 🏷️ Different Types of HTML Tags

HTML tags can generally be divided into two main categories.

### 1. 🔒 Paired / Container Tags

These tags have an **opening tag** and a **closing tag**.

**Syntax:**

```html
<tagname>Content</tagname>
```

**Example:**

```html
<p>This is a paragraph.</p>
```

---

### 2. ⚡ Empty / Void Tags

These tags do not contain content and do not normally require a closing tag.

**Syntax:**

```html
<tagname>
```

**Examples:**

```html
<br>
<img>
<hr>
<input>
```

---

# 📚 30 Different HTML Tags

> 💡 **Tip:** Click on any tag below to expand its explanation, syntax, and example.

<details>
<summary><strong>1. 🏠 &lt;html&gt; — HTML Root Element</strong></summary>

### 📌 Description

The `<html>` tag is the root element of an HTML document. Other HTML elements are placed inside it.

### 💻 Syntax

```html
<html>
    Content
</html>
```

### 🧪 Example

```html
<html>
    <body>
        Hello World
    </body>
</html>
```

</details>

---

<details>
<summary><strong>2. 🧠 &lt;head&gt; — Document Information</strong></summary>

### 📌 Description

The `<head>` element contains metadata and other information about the webpage that is not normally displayed as page content.

### 💻 Syntax

```html
<head>
    Content
</head>
```

### 🧪 Example

```html
<head>
    <title>My Website</title>
</head>
```

</details>

---

<details>
<summary><strong>3. 🏷️ &lt;title&gt; — Page Title</strong></summary>

### 📌 Description

The `<title>` tag defines the title of the webpage, usually displayed in the browser tab.

### 💻 Syntax

```html
<title>Title</title>
```

### 🧪 Example

```html
<title>My Website</title>
```

</details>

---

<details>
<summary><strong>4. 👁️ &lt;body&gt; — Page Content</strong></summary>

### 📌 Description

The `<body>` tag contains the main visible content of a webpage.

### 💻 Syntax

```html
<body>
    Content
</body>
```

### 🧪 Example

```html
<body>
    <h1>Welcome</h1>
    <p>Hello World!</p>
</body>
```

</details>

---

<details>
<summary><strong>5. 🔠 &lt;h1&gt; — Main Heading</strong></summary>

### 📌 Description

The `<h1>` tag defines the highest-level heading on a webpage.

HTML provides headings from `<h1>` to `<h6>`.

### 💻 Syntax

```html
<h1>Heading</h1>
```

### 🧪 Example

```html
<h1>Basic HTML Tags</h1>
```

</details>

---

<details>
<summary><strong>6. 📝 &lt;p&gt; — Paragraph</strong></summary>

### 📌 Description

The `<p>` tag is used to define a paragraph of text.

### 💻 Syntax

```html
<p>Paragraph text</p>
```

### 🧪 Example

```html
<p>This is a simple paragraph.</p>
```

</details>

---

<details>
<summary><strong>7. ↩️ &lt;br&gt; — Line Break</strong></summary>

### 📌 Description

The `<br>` tag inserts a line break.

It is a **void element**, so it does not require a closing tag.

### 💻 Syntax

```html
<br>
```

### 🧪 Example

```html
Hello<br>
World
```

</details>

---

<details>
<summary><strong>8. ➖ &lt;hr&gt; — Horizontal Rule</strong></summary>

### 📌 Description

The `<hr>` tag represents a thematic break between sections of content.

### 💻 Syntax

```html
<hr>
```

### 🧪 Example

```html
<p>Section One</p>
<hr>
<p>Section Two</p>
```

</details>

---

<details>
<summary><strong>9. 🔗 &lt;a&gt; — Hyperlink</strong></summary>

### 📌 Description

The `<a>` tag creates a hyperlink to another webpage, file, or location.

### 💻 Syntax

```html
<a href="URL">Link Text</a>
```

### 🧪 Example

```html
<a href="https://www.example.com">
    Visit Example
</a>
```

</details>

---

<details>
<summary><strong>10. 🖼️ &lt;img&gt; — Image</strong></summary>

### 📌 Description

The `<img>` tag displays an image on a webpage.

It is a **void element**.

### 💻 Syntax

```html
<img src="image.jpg" alt="Description">
```

### 🧪 Example

```html
<img src="photo.jpg" alt="My Photo" width="300">
```

</details>

---

<details>
<summary><strong>11. 💪 &lt;strong&gt; — Strong Importance</strong></summary>

### 📌 Description

The `<strong>` tag indicates that the content has strong importance. Browsers commonly display it in bold.

### 💻 Syntax

```html
<strong>Important text</strong>
```

### 🧪 Example

```html
<strong>This is important.</strong>
```

</details>

---

<details>
<summary><strong>12. ✨ &lt;em&gt; — Emphasized Text</strong></summary>

### 📌 Description

The `<em>` tag represents emphasized text. Browsers commonly display it in italic.

### 💻 Syntax

```html
<em>Emphasized text</em>
```

### 🧪 Example

```html
<em>This text is emphasized.</em>
```

</details>

---

<details>
<summary><strong>13. 🔤 &lt;b&gt; — Bold Text</strong></summary>

### 📌 Description

The `<b>` tag draws attention to text without indicating that the text has special importance.

### 💻 Syntax

```html
<b>Bold text</b>
```

### 🧪 Example

```html
<b>Hello World</b>
```

</details>

---

<details>
<summary><strong>14. 🖋️ &lt;i&gt; — Italic Text</strong></summary>

### 📌 Description

The `<i>` tag represents text in an alternate voice or mood and is commonly displayed in italic.

### 💻 Syntax

```html
<i>Italic text</i>
```

### 🧪 Example

```html
<i>This is italic text.</i>
```

</details>

---

<details>
<summary><strong>15. 🔽 &lt;u&gt; — Underlined Text</strong></summary>

### 📌 Description

The `<u>` tag represents text with an underline or other non-textual annotation.

### 💻 Syntax

```html
<u>Underlined text</u>
```

### 🧪 Example

```html
<u>This text is underlined.</u>
```

</details>

---

<details>
<summary><strong>16. 🖍️ &lt;mark&gt; — Highlighted Text</strong></summary>

### 📌 Description

The `<mark>` tag represents text that is highlighted or marked for reference.

### 💻 Syntax

```html
<mark>Highlighted text</mark>
```

### 🧪 Example

```html
<p>This is <mark>important</mark> information.</p>
```

</details>

---

<details>
<summary><strong>17. 🔎 &lt;small&gt; — Smaller Text</strong></summary>

### 📌 Description

The `<small>` tag represents side comments or text that should be displayed smaller than normal text.

### 💻 Syntax

```html
<small>Small text</small>
```

### 🧪 Example

```html
<small>Copyright 2026</small>
```

</details>

---

<details>
<summary><strong>18. ⬇️ &lt;sub&gt; — Subscript</strong></summary>

### 📌 Description

The `<sub>` tag displays text below the normal baseline.

### 💻 Syntax

```html
<sub>Text</sub>
```

### 🧪 Example

```html
H<sub>2</sub>O
```

### 📤 Output

H₂O

</details>

---

<details>
<summary><strong>19. ⬆️ &lt;sup&gt; — Superscript</strong></summary>

### 📌 Description

The `<sup>` tag displays text above the normal baseline.

### 💻 Syntax

```html
<sup>Text</sup>
```

### 🧪 Example

```html
x<sup>2</sup>
```

### 📤 Output

x²

</details>

---

<details>
<summary><strong>20. 📋 &lt;pre&gt; — Preformatted Text</strong></summary>

### 📌 Description

The `<pre>` tag preserves spaces, tabs, and line breaks as written in the HTML source.

### 💻 Syntax

```html
<pre>
    Text
    Text
</pre>
```

### 🧪 Example

```html
<pre>
This is written.
    using pre
    tag
</pre>
```

</details>

---

<details>
<summary><strong>21. 📦 &lt;div&gt; — Division / Container</strong></summary>

### 📌 Description

The `<div>` tag is a general-purpose block-level container used to group HTML elements.

### 💻 Syntax

```html
<div>
    Content
</div>
```

### 🧪 Example

```html
<div>
    <h2>About Me</h2>
    <p>I am a student.</p>
</div>
```

</details>

---

<details>
<summary><strong>22. 🔹 &lt;span&gt; — Inline Container</strong></summary>

### 📌 Description

The `<span>` tag is an inline container commonly used to group or style a small part of text.

### 💻 Syntax

```html
<span>Content</span>
```

### 🧪 Example

```html
<p>This is <span>important</span> text.</p>
```

</details>

---

<details>
<summary><strong>23. 🔵 &lt;ul&gt; — Unordered List</strong></summary>

### 📌 Description

The `<ul>` tag creates an unordered list, normally displayed using bullet points.

### 💻 Syntax

```html
<ul>
    <li>Item</li>
</ul>
```

### 🧪 Example

```html
<ul>
    <li>Apple</li>
    <li>Banana</li>
    <li>Mango</li>
</ul>
```

</details>

---

<details>
<summary><strong>24. 🔢 &lt;ol&gt; — Ordered List</strong></summary>

### 📌 Description

The `<ol>` tag creates an ordered list, normally displayed using numbers.

### 💻 Syntax

```html
<ol>
    <li>Item</li>
</ol>
```

### 🧪 Example

```html
<ol>
    <li>First</li>
    <li>Second</li>
    <li>Third</li>
</ol>
```

</details>

---

<details>
<summary><strong>25. 📌 &lt;li&gt; — List Item</strong></summary>

### 📌 Description

The `<li>` tag represents an individual item inside an ordered or unordered list.

### 💻 Syntax

```html
<li>Item</li>
```

### 🧪 Example

```html
<ul>
    <li>HTML</li>
    <li>CSS</li>
</ul>
```

</details>

---

<details>
<summary><strong>26. 📊 &lt;table&gt; — Table</strong></summary>

### 📌 Description

The `<table>` tag creates a table for displaying data in rows and columns.

### 💻 Syntax

```html
<table>
    Table Content
</table>
```

### 🧪 Example

```html
<table>
    <tr>
        <td>John</td>
        <td>20</td>
    </tr>
</table>
```

</details>

---

<details>
<summary><strong>27. ↔️ &lt;tr&gt; — Table Row</strong></summary>

### 📌 Description

The `<tr>` tag defines a row inside an HTML table.

### 💻 Syntax

```html
<tr>
    Table Cells
</tr>
```

### 🧪 Example

```html
<tr>
    <td>John</td>
    <td>20</td>
</tr>
```

</details>

---

<details>
<summary><strong>28. 🧮 &lt;td&gt; — Table Data Cell</strong></summary>

### 📌 Description

The `<td>` tag defines a normal data cell inside a table row.

### 💻 Syntax

```html
<td>Data</td>
```

### 🧪 Example

```html
<tr>
    <td>John</td>
    <td>20</td>
</tr>
```

</details>

---

<details>
<summary><strong>29. 📝 &lt;form&gt; — Form</strong></summary>

### 📌 Description

The `<form>` tag is used to create a form for collecting user input.

### 💻 Syntax

```html
<form>
    Form Elements
</form>
```

### 🧪 Example

```html
<form>
    <input type="text" placeholder="Enter your name">
</form>
```

</details>

---

<details>
<summary><strong>30. ⌨️ &lt;input&gt; — Input Field</strong></summary>

### 📌 Description

The `<input>` tag creates an input field. It can be used for text, passwords, checkboxes, radio buttons, and other types of user input.

It is a **void element**.

### 💻 Syntax

```html
<input type="text">
```

### 🧪 Example

```html
<input 
    type="text" 
    placeholder="Enter your name"
>
```

</details>

---

# 📋 Quick Reference

| # | Tag | Purpose |
|---:|:---:|---|
| 01 | `<html>` | Root element |
| 02 | `<head>` | Document information |
| 03 | `<title>` | Page title |
| 04 | `<body>` | Visible content |
| 05 | `<h1>` | Main heading |
| 06 | `<p>` | Paragraph |
| 07 | `<br>` | Line break |
| 08 | `<hr>` | Thematic break |
| 09 | `<a>` | Hyperlink |
| 10 | `<img>` | Image |
| 11 | `<strong>` | Strong importance |
| 12 | `<em>` | Emphasis |
| 13 | `<b>` | Bold text |
| 14 | `<i>` | Italic text |
| 15 | `<u>` | Underlined text |
| 16 | `<mark>` | Highlighted text |
| 17 | `<small>` | Smaller text |
| 18 | `<sub>` | Subscript |
| 19 | `<sup>` | Superscript |
| 20 | `<pre>` | Preformatted text |
| 21 | `<div>` | Block container |
| 22 | `<span>` | Inline container |
| 23 | `<ul>` | Unordered list |
| 24 | `<ol>` | Ordered list |
| 25 | `<li>` | List item |
| 26 | `<table>` | Table |
| 27 | `<tr>` | Table row |
| 28 | `<td>` | Table data cell |
| 29 | `<form>` | Form |
| 30 | `<input>` | Input field |

---

## 🎯 Conclusion

HTML is the foundation of modern web pages. Learning HTML tags is the first step toward creating structured and accessible websites.

This README covers **30 commonly used HTML tags**, with each tag including:

- 📌 **Description**
- 💻 **Syntax**
- 🧪 **Example**
- 📤 **Output** where useful

> 🚀 **Keep learning, keep building, and keep experimenting with HTML!**