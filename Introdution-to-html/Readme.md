# 🌐 Introduction to HTML

> **HTML is the foundation of every webpage.**  
> It provides the structure that browsers use to display content on the web.

---

## 📚 Table of Contents

- [1. Introduction](#1-introduction)
- [2. Features](#2-features)
- [3. HTML Boilerplate](#3-html-boilerplate)
- [4. HTML + CSS + JavaScript](#4-html--css--javascript)

---

# 1. 🚀 Introduction

**HTML** stands for **HyperText Markup Language**.

It is the standard **markup language** used to create and structure webpages.

HTML is responsible for defining the **structure and content** of a webpage, such as:

- 📝 Headings
- 📄 Paragraphs
- 🔗 Links
- 🖼️ Images
- 📋 Lists
- 📊 Tables
- 📝 Forms
- 🎥 Multimedia

### 💡 Simple Example

```html
<h1>Hello World!</h1>

<p>Welcome to my first HTML page.</p>
```

The browser reads these HTML elements and displays the content as a webpage.

---

# 2. ✨ Features of HTML

HTML provides many useful features for creating webpages.

| Feature | Description |
|---|---|
| 🟢 **Easy to Learn** | HTML has a simple and readable syntax. |
| 🏗️ **Page Structure** | Used to structure the content of webpages. |
| 🌍 **Platform Independent** | HTML works across different operating systems. |
| 🎨 **CSS Support** | Can be combined with CSS for styling. |
| ⚡ **JavaScript Support** | Can be combined with JavaScript for interactivity. |
| 🖼️ **Multimedia** | Supports images, audio, and video. |
| ♿ **Semantic Elements** | Provides meaningful elements such as `<header>`, `<main>`, and `<footer>`. |
| 🌐 **Browser Support** | Supported by all modern web browsers. |

---

# 3. 🧱 HTML Boilerplate

An **HTML boilerplate** is the basic structure that we use when starting an HTML document.

```html
<!DOCTYPE html> <!-- Specifies that this is an HTML5 document -->

<html lang="en"> <!-- Root element of the HTML document -->

<head> <!-- Contains metadata and other information -->

    <meta charset="UTF-8">
    <!-- Specifies the character encoding -->

    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Makes the webpage responsive on different devices -->

    <title>Document</title>
    <!-- Specifies the title displayed in the browser tab -->

    <link rel="stylesheet" href="style.css">
    <!-- Connects the external CSS file -->

</head>

<body> <!-- Contains the visible content of the webpage -->

    <h1>Introduction to HTML</h1>
    <!-- Main heading -->

    <p>This is my first HTML page.</p>
    <!-- Paragraph -->

    <script src="script.js"></script>
    <!-- Connects the external JavaScript file -->

</body>

</html>
```

---

## 🔍 Boilerplate Structure

```text
                    HTML DOCUMENT
                          │
                          ▼
                  <!DOCTYPE html>
                          │
                          ▼
                     <html>
                    /      \
                   /        \
                  ▼          ▼
              <head>       <body>
                │             │
                │             ├── <h1>
                │             ├── <p>
                │             └── <script>
                │
                ├── <meta>
                ├── <meta>
                ├── <title>
                └── <link>
```

---

# 4. 🎨 HTML + CSS + JavaScript

Modern webpages commonly use three technologies together:

```text
        🌐 WEBPAGE
            │
    ┌───────┼────────┐
    │       │        │
    ▼       ▼        ▼
   HTML    CSS       JS
    │       │        │
    ▼       ▼        ▼
Structure Style   Behavior
```

### 🏗️ HTML

Defines the **structure and content**.

```html
<h1>Hello World</h1>
<p>Welcome to my website.</p>
```

### 🎨 CSS

Controls the **appearance and design**.

```css
h1 {
    color: blue;
}
```

### ⚡ JavaScript

Adds **behavior and interactivity**.

```javascript
alert("Hello World!");
```

### 🧠 Remember

> **HTML → Structure 🏗️**  
> **CSS → Style 🎨**  
> **JavaScript → Behavior ⚡**

---

## 📁 Basic Project Structure

A simple HTML project can look like this:

```text
📦 my-project
│
├── 📄 index.html
├── 🎨 style.css
└── ⚡ script.js
```

| File | Purpose |
|---|---|
| `index.html` | 🏗️ Webpage structure |
| `style.css` | 🎨 Webpage styling |
| `script.js` | ⚡ Webpage functionality |

---

## 🎯 Quick Summary

```text
HTML
 │
 ├── Structure
 ├── Content
 ├── Elements
 └── Semantic Meaning
       │
       ├──────────────┐
       ▼              ▼
      CSS             JS
      🎨              ⚡
    Styling        Behavior
```

> 🌟 **HTML is the starting point of web development. Learn the structure first, then make it beautiful with CSS and interactive with JavaScript.**

---