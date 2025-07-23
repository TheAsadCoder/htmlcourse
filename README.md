# HTML & Web Development Full Course Notes (Beginner to Advanced)

This course covers everything you need to know to become confident in HTML and the structure of modern web pages. Ideal for beginners.

---

## Module 1: Introduction to Web Development

### Lesson 1.1: What is the Internet and How Does It Work?

The **Internet** is a network of networks that connects millions of computers globally. It lets people share and access information.

#### Key Concepts:

* **Client**: The user’s device that sends a request (browser, mobile app, etc.)
* **Server**: A computer that stores websites and responds to requests
* **IP Address**: A numeric label for each device on a network
* **DNS**: Translates website names into IP addresses
* **Browser**: Chrome, Firefox – used to access websites

#### Assignment:

Draw a diagram of how the internet delivers a webpage from server to client.

---

### Lesson 1.2: What is Web Development?

**Web Development** means creating and maintaining websites.

#### Types of Development:

* **Frontend**: User-facing (HTML, CSS, JS)
* **Backend**: Server-side logic (PHP, Python, etc.)
* **Full Stack**: Both frontend and backend

#### Tools:

* VS Code, browser, version control (Git), etc.

#### Assignment:

List 5 frontend and 5 backend technologies.

---

### Lesson 1.3: What is a Website?

A **website** is a collection of interlinked web pages accessible via a browser.

#### Static vs Dynamic Websites:

* Static: Simple HTML files
* Dynamic: Connected to databases and server scripts

#### Assignment:

Compare static and dynamic websites in a table.

---

### Lesson 1.4: Why Learn HTML?

HTML forms the basic structure of a webpage. It's the foundation of all websites.

#### Analogy:

* HTML: Structure
* CSS: Design
* JS: Behavior

#### Assignment:

Write a paragraph about HTML’s role in web development.

---

## Module 2: Getting Started with HTML

### Lesson 2.1: Setting Up the Environment

#### Tools:

* Install VS Code
* Install Live Server extension

#### Assignment:

Create a file `index.html` and open with Live Server

---

### Lesson 2.2: Basic HTML Page Structure

```html
<!DOCTYPE html>
<html>
<head>
  <title>My Page</title>
</head>
<body>
  <h1>Hello World</h1>
</body>
</html>
```

#### Explanation:

* DOCTYPE, html, head, body, title

#### Assignment:

Replace heading with your name.

---

## Module 3: HTML Elements & Structure

### Lesson 3.1: Basic Tags

* `<h1>` to `<h6>`
* `<p>`
* `<br>`, `<hr>`
* `<b>`, `<i>`, `<strong>`, `<em>`

#### Assignment:

Use each tag in a simple page.

---

### Lesson 3.2: Links and Images

* `<a href="">`
* `<img src="" alt="">`

#### Assignment:

Create a page with two links and one image.

---

### Lesson 3.3: Lists

* Ordered List `<ol>`
* Unordered List `<ul>`
* List Item `<li>`

#### Assignment:

Make a shopping list and recipe list.

---

### Lesson 3.4: Tables

```html
<table>
  <tr><th>Name</th><th>Age</th></tr>
  <tr><td>Aya</td><td>20</td></tr>
</table>
```

#### Assignment:

Create a table with your friend’s names and ages.

---

## Module 4: HTML Forms and Input Elements

### Lesson 4.1: Form Basics

```html
<form action="/submit" method="post">
  <!-- form elements -->
</form>
```

* `action`: Where data goes
* `method`: GET or POST

---

### Lesson 4.2: Input Types

* `text`, `email`, `password`, `number`, `submit`

#### Example:

```html
<label>Name: <input type="text"></label>
```

---

### Lesson 4.3: Other Form Controls

* `<textarea>`
* `<select><option>`
* `checkbox`, `radio`

---

### Lesson 4.4: Form Grouping

* `<fieldset>`
* `<legend>`

#### Assignment:

Create a registration form using all input types.

---

## Module 5: Semantic HTML

### Lesson 5.1: Why Semantic Tags?

Semantic tags give meaning to HTML for better SEO and accessibility.

### Common Tags:

* `<header>`, `<footer>`
* `<main>`, `<article>`, `<section>`
* `<aside>`, `<nav>`

#### Assignment:

Rewrite a basic layout using semantic tags.

---

## Module 6: HTML Media Elements

### Lesson 6.1: Audio and Video Tags

```html
<audio controls>
  <source src="sound.mp3" type="audio/mpeg">
</audio>
```

```html
<video controls>
  <source src="movie.mp4" type="video/mp4">
</video>
```

#### Assignment:

Embed a video and audio file in a webpage.

---

## Module 7: Advanced HTML Topics

### Lesson 7.1: Input Validation

* `required`, `min`, `max`, `pattern`, `maxlength`

```html
<input type="text" required pattern="[A-Za-z]+">
```

### Lesson 7.2: Meta Tags

* `<meta charset="UTF-8">`
* `<meta name="viewport">`
* SEO and responsiveness

### Lesson 7.3: Entities and Symbols

* `&nbsp;`, `&copy;`, `&lt;`, `&gt;`

#### Assignment:

Use at least 5 HTML entities in a page.

---

## Module 8: Final Project & Assessment

### Project Task:

Create a personal webpage including:

* Introduction (use headings, paragraph)
* Image and links
* List of skills
* A contact form
* Proper use of semantic HTML

### Self-Checklist:

* Page is well structured
* All common HTML tags are used
* Forms and media elements included

### Bonus:

Ask friends to review your page for feedback.

🎓 **Congratulations!** You've completed the full beginner course in HTML. You're now ready to start learning CSS or JavaScript next!

### Skills Sikhao - Learn & Teach with Confidence

All rights reserved © 2025 SkillsSikhao.com
