# 📄 HTML Revision Notes

Revision Of HTML

---

# 📚 Topics Covered

## 📅 Day 1

- HTML Boilerplate
- Headings
- Paragraph
- HTML Attributes
- HTML Entities
- Hyperlinks
- Images
- Lists

---

## 📅 Day 2

- Tables
- Table Layout
- Responsive Images
- Picture Tag
- Multimedia
- PDF Embed

---

## 📅 Day 3

- HTML Forms
- Input Types
- Form Attributes
- Validation
- GET vs POST
- Datalist

---

# 🧱 HTML Boilerplate

```html
<!DOCTYPE html>
<html>
<head>
    <title></title>
</head>
<body>

</body>
</html>
```

---

# 🔑 Frequently Used Tags

| Tag | Purpose |
|------|----------|
| `<html>` | Root Element |
| `<head>` | Metadata |
| `<body>` | Visible Content |
| `<h1> - <h6>` | Headings |
| `<p>` | Paragraph |
| `<a>` | Hyperlink |
| `<img>` | Image |
| `<table>` | Table |
| `<form>` | Form |
| `<input>` | User Input |
| `<select>` | Dropdown |
| `<textarea>` | Multi-line Text |
| `<button>` | Button |
| `<video>` | Video |
| `<audio>` | Audio |
| `<object>` | PDF / External Resource |
| `<iframe>` | Embed Webpage |

---

# 📝 Common Input Types

| Type | Purpose |
|------|----------|
| text | Text Input |
| password | Password |
| email | Email |
| number | Numbers |
| date | Date Picker |
| datetime-local | Date & Time |
| color | Color Picker |
| file | File Upload |
| hidden | Hidden Data |
| range | Slider |
| checkbox | Multiple Selection |
| radio | Single Selection |
| submit | Submit Form |
| reset | Reset Form |

---

# ⭐ Important Attributes

## Anchor

```html
href
target
download
```

---

## Image

```html
src
alt
width
height
```

---

## Input

```html
name
value
placeholder
required
readonly
disabled
min
max
step
maxlength
minlength
autocomplete
```

---

## Form

```html
action
method
autocomplete
novalidate
enctype
```

---

# 📌 GET vs POST

| GET | POST |
|------|------|
| Data visible in URL | Data hidden from URL |
| Less Secure | More Secure |
| Used for Searching | Used for Login/Register |
| Can Bookmark | Cannot Bookmark |

---

# 📌 readonly vs disabled

| readonly | disabled |
|-----------|----------|
| Cannot Edit | Cannot Edit |
| Submitted | Not Submitted |
| Focus Allowed | Focus Not Allowed |

---

# 📌 Radio vs Checkbox

| Radio | Checkbox |
|--------|----------|
| Single Selection | Multiple Selection |
| Same `name` Required | Multiple Selection Allowed |

---

# 📌 HTML Entities

| Entity | Output |
|---------|--------|
| `&copy;` | © |
| `&reg;` | ® |
| `&trade;` | ™ |
| `&#169;` | © |
| `&#174;` | ® |
| `&#8482;` | ™ |

---

# 📌 Semantic Tags

```html
<header>
<nav>
<main>
<section>
<article>
<aside>
<footer>
```

---

# 📌 Deprecated Tags / Attributes

Avoid using these in modern HTML.

```html
<center>

bgcolor

align

valign

background

text
```

Use CSS instead.

---

# 📌 HTML5 Multimedia

```html
<video>

<audio>

<source>

<object>

<iframe>

<picture>
```

---

# 📌 HTML Form Validation

```html
required

min

max

step

pattern

minlength

maxlength
```

---

# 📌 Browser Flow

```
HTML File
      │
      ▼
DOCTYPE
      │
      ▼
HEAD
      │
      ▼
BODY
      │
      ▼
DOM Creation
      │
      ▼
Render Page
```

---

# 🎯 Interview Questions

- Difference between HTML and HTML5?
- What is Semantic HTML?
- Difference between `id` and `class`?
- Difference between GET and POST?
- Difference between `readonly` and `disabled`?
- Difference between Radio and Checkbox?
- Difference between `<div>` and `<span>`?
- Difference between `<section>` and `<article>`?
- Difference between `<iframe>` and `<object>`?
- Difference between `src` and `href`?
- What is `alt` attribute?
- What is `placeholder`?
- What is `autocomplete`?
- What is `novalidate`?
- What is `enctype`?
- Difference between `required`, `min`, `max`, and `step`?

---



| Tag | Short Description |
|------|-------------------|
| `<html>` | Root element of an HTML document. |
| `<head>` | Stores metadata and page information. |
| `<title>` | Sets the browser tab title. |
| `<body>` | Contains all visible webpage content. |
| `<h1> - <h6>` | Defines headings of different sizes. |
| `<p>` | Defines a paragraph. |
| `<br>` | Inserts a line break. |
| `<hr>` | Creates a horizontal line. |
| `<a>` | Creates a hyperlink. |
| `<img>` | Displays an image. |
| `<picture>` | Displays responsive images. |
| `<source>` | Specifies media source files. |
| `<video>` | Embeds a video. |
| `<audio>` | Embeds audio. |
| `<object>` | Embeds external resources like PDFs. |
| `<iframe>` | Embeds another webpage. |
| `<table>` | Creates a table. |
| `<tr>` | Defines a table row. |
| `<td>` | Defines a table data cell. |
| `<th>` | Defines a table header cell. |
| `<thead>` | Groups table header rows. |
| `<tbody>` | Groups table body rows. |
| `<tfoot>` | Groups table footer rows. |
| `<caption>` | Adds a title to a table. |
| `<colgroup>` | Groups table columns. |
| `<col>` | Defines column properties. |
| `<ul>` | Creates an unordered list. |
| `<ol>` | Creates an ordered list. |
| `<li>` | Defines a list item. |
| `<dl>` | Creates a description list. |
| `<dt>` | Defines a description term. |
| `<dd>` | Defines description details. |
| `<form>` | Collects user input. |
| `<input>` | Creates an input field. |
| `<label>` | Provides a label for form elements. |
| `<select>` | Creates a drop-down list. |
| `<option>` | Defines a drop-down option. |
| `<optgroup>` | Groups related options. |
| `<textarea>` | Creates a multi-line text box. |
| `<button>` | Creates a clickable button. |
| `<fieldset>` | Groups related form controls. |
| `<legend>` | Adds a title to a fieldset. |
| `<datalist>` | Provides autocomplete options. |
| `<output>` | Displays calculation results. |
| `<div>` | Defines a block-level container. |
| `<span>` | Defines an inline container. |
| `<header>` | Defines the page header. |
| `<nav>` | Defines navigation links. |
| `<main>` | Defines the main content. |
| `<section>` | Defines a content section. |
| `<article>` | Defines independent content. |
| `<aside>` | Defines sidebar content. |
| `<footer>` | Defines the page footer. |
| `<figure>` | Groups media with a caption. |
| `<figcaption>` | Adds a caption to a figure. |
| `<strong>` | Displays important text. |
| `<b>` | Displays bold text. |
| `<em>` | Displays emphasized text. |
| `<i>` | Displays italic text. |
| `<mark>` | Highlights text. |
| `<small>` | Displays smaller text. |
| `<sub>` | Displays subscript text. |
| `<sup>` | Displays superscript text. |
| `<code>` | Displays computer code. |
| `<pre>` | Displays preformatted text. |
| `<blockquote>` | Displays a long quotation. |
| `<q>` | Displays an inline quotation. |
| `<abbr>` | Defines an abbreviation. |
| `<address>` | Displays contact information. |
| `<cite>` | Defines a citation. |
| `<time>` | Represents date or time. |
| `<meta>` | Provides metadata about the page. |
| `<link>` | Links external resources like CSS. |
| `<style>` | Adds internal CSS. |
| `<script>` | Adds JavaScript code. |
| `<noscript>` | Displays content when JavaScript is disabled. |

# 🚀 Repository Goal

- HTML Revision
- Interview Preparation
- Web Development Fundamentals
- MERN Stack Journey

---

⭐ This folder is part of my **MERN Stack Journey** repository.