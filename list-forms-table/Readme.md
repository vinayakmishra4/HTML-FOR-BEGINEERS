<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:E34F26,100:F7931E&height=190&section=header&text=Lists%20%7C%20Forms%20%7C%20Tables&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Module%204%20%E2%80%A2%20HTML%20FOR%20BEGINNERS&descSize=18&descAlignY=60" width="100%" alt="" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=E34F26&center=true&vCenter=true&width=600&lines=Organise+content+with+lists;Show+data+with+tables;Collect+input+with+forms;Embed+media+with+video" alt="Organise content with lists · Show data with tables · Collect input with forms · Embed media with video" />

<br />

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Level](https://img.shields.io/badge/Level-Beginner-2EA44F?style=for-the-badge)
![Files](https://img.shields.io/badge/Examples-4_Pages-8B5CF6?style=for-the-badge)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)

<br />

[📖 About](#-about) &nbsp;•&nbsp; [🧩 Topics](#-whats-inside) &nbsp;•&nbsp; [📝 Lists](#-1-lists) &nbsp;•&nbsp; [📊 Tables](#-2-tables) &nbsp;•&nbsp; [🧾 Forms](#-3-forms) &nbsp;•&nbsp; [🎬 Video](#-4-video) &nbsp;•&nbsp; [🚀 Start](#-getting-started) &nbsp;•&nbsp; [💡 Practice](#-practice-ideas)

</div>

---

## 📖 About

Almost every website uses these four building blocks:

> 📝 **Lists** group related items &nbsp;·&nbsp; 📊 **Tables** show data in rows and columns &nbsp;·&nbsp; 🧾 **Forms** collect input &nbsp;·&nbsp; 🎬 **Video** embeds media

Each topic has its own runnable page. **Open it, break it, fix it, and learn by doing.**

---

## 🧩 What's Inside

| | File | Topic | You'll learn |
| :-: | :--- | :--- | :--- |
| 📝 | [`list.html`](./list.html) | Lists | Ordered, unordered and definition lists |
| 📊 | [`table.html`](./table.html) | Tables | A styled table with caption, header and body |
| 🧾 | [`forms.html`](./forms.html) | Forms | A dark-themed registration form with 10 controls |
| 🎬 | [`vedio.html`](./vedio.html) | Video | Embedding a local video with `<video>` |
| 🎞️ | [`video.mp4`](./video.mp4) | Media | Sample clip used by the video page |
| 🗒️ | [`data.txt`](./data.txt) | Data | Placeholder text file |

### 🗺️ Suggested learning path

```mermaid
flowchart LR
    A[📝 Lists] --> B[📊 Tables] --> C[🧾 Forms] --> D[🎬 Video]
    style A fill:#E34F26,color:#fff,stroke:none
    style B fill:#F7931E,color:#fff,stroke:none
    style C fill:#8B5CF6,color:#fff,stroke:none
    style D fill:#1F6FEB,color:#fff,stroke:none
```

---

## 📝 1. Lists

📄 **File:** [`list.html`](./list.html)

HTML offers three kinds of lists, and the file has one example of each.

| Type | Tags | Best for | Example in the file |
| :--- | :--- | :--- | :--- |
| 🔢 **Ordered** | `<ol>` `<li>` | Steps, rankings | Steps to bake a cake |
| 🔘 **Unordered** | `<ul>` `<li>` | Items with no order | Groceries to buy |
| 📚 **Definition** | `<dl>` `<dt>` `<dd>` | Terms and meanings | Python, JavaScript, HTML, CSS |

```html
<ol>
    <li>Preheat the oven to 350°F (175°C).</li>
    <li>Mix the dry ingredients.</li>
</ol>
```

---

## 📊 2. Tables

📄 **File:** [`table.html`](./table.html)

A **Students Report** table, styled with CSS.

| Tag | Purpose |
| :---: | :--- |
| `<table>` | The table container |
| `<caption>` | The table's title |
| `<thead>` `<tbody>` | Header and body sections |
| `<tr>` | A row |
| `<th>` | A header cell |
| `<td>` | A data cell |

✨ **Styling tricks used**

- 🔵 A blue header row
- 🦓 Zebra stripes with `tbody tr:nth-child(even)`
- 🖱️ A row highlight on hover
- 🌫️ A soft box shadow and collapsed borders

```html
<table>
    <caption>Students Report</caption>
    <thead>
        <tr><th>Name</th><th>Grade</th></tr>
    </thead>
    <tbody>
        <tr><td>Rohan</td><td>A+</td></tr>
    </tbody>
</table>
```

---

## 🧾 3. Forms

📄 **File:** [`forms.html`](./forms.html)

A dark **"Dark Nexus" registration form** with a glowing purple-to-cyan gradient border, glass-style card and animated focus effects.

<details open>
<summary><b>🎛️ Form controls used (click to collapse)</b></summary>

<br />

| Field | Element | Type |
| :--- | :--- | :--- |
| 👤 Name | `<input>` | `text` |
| 📞 Phone | `<input>` | `tel` |
| 📧 Email | `<input>` | `email` |
| 🔒 Password | `<input>` | `password` |
| 📅 Date of birth | `<input>` | `date` |
| ⚧ Gender | `<select>` + `<option>` | dropdown |
| 💎 Subscription plan | `<input>` | `radio` (Basic, Premium, VIP) |
| 💬 Message | `<textarea>` | multi-line |
| ✅ Terms | `<input>` | `checkbox` |
| 🚀 Submit | `<button>` | `submit` |

</details>

<details>
<summary><b>🧠 Key concepts (click to expand)</b></summary>

<br />

- 🔗 `<label for="id">` links a label to its input and helps accessibility.
- ❗ `required` makes the browser validate the field before submitting.
- 💭 `placeholder` shows hint text in an empty field.
- 🔘 Radio buttons that share a `name` form a group, so only one can be picked.
- 📱 The layout is responsive, and the plan options stack on screens under 500px.

</details>

> [!NOTE]
> The form posts to `save.php`, which isn't in this repo. Submitting it won't store anything unless you add a backend. The page is for practising layout and form elements.

---

## 🎬 4. Video

📄 **File:** [`vedio.html`](./vedio.html)

```html
<video width="264" autoplay loop controls muted>
    <source src="video.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```

| Attribute | What it does |
| :---: | :--- |
| ▶️ `controls` | Shows play, pause and volume controls |
| ⚡ `autoplay` | Starts playing on its own |
| 🔇 `muted` | Starts silent (browsers usually need this for autoplay) |
| 🔁 `loop` | Restarts when it ends |
| 📏 `width` | Sets the player width in pixels |

> [!TIP]
> Keep `video.mp4` in the same folder as `vedio.html`, or the video won't load. The text inside the tag only shows in browsers that can't play video.

---

## 🚀 Getting Started

```bash
# 1️⃣ Clone the repository
git clone https://github.com/vinayakmishra4/HTML-FOR-BEGINEERS.git

# 2️⃣ Go into this module
cd HTML-FOR-BEGINEERS/list-forms-table
```

3️⃣ **Open any `.html` file** in your browser by double-clicking it.
4️⃣ **Edit it** in an editor like VS Code, save, and refresh to see your changes.

---

## 📁 Folder Structure

```text
📦 list-forms-table
 ┣ 📜 Readme.md     ← you are here
 ┣ 📝 list.html     ← ordered, unordered & definition lists
 ┣ 📊 table.html    ← styled students table
 ┣ 🧾 forms.html    ← Dark Nexus registration form
 ┣ 🎬 vedio.html    ← video embedding example
 ┣ 🎞️ video.mp4     ← sample video
 ┗ 🗒️ data.txt      ← placeholder data file
```

---

## 💡 Practice Ideas

- [ ] Add more students to the table and colour each grade differently
- [ ] Build a nested list, such as groceries with sub-items under "Vegetables"
- [ ] Group form fields with `<fieldset>` and `<legend>`
- [ ] Add `minlength` to the password and a `pattern` to the phone field
- [ ] Try the `<audio>` tag and compare it with `<video>`

---

## 📚 Resources

| Topic | Link |
| :--- | :--- |
| 📝 Lists | [MDN: HTML lists](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Lists) |
| 📊 Tables | [MDN: Table basics](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Table_basics) |
| 🧾 Forms | [MDN: Web forms](https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms) |
| 🎬 Video | [MDN: `<video>` element](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/video) |

<div align="center">

<br />

⬅️ **[Back to main repository](../README.md)**

⭐ *If this helped you, give the repo a star!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F7931E,100:E34F26&height=120&section=footer" width="100%" alt="" />

</div>