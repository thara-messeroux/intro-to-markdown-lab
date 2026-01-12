# 🧩 The Anatomy of a CSS Selector

A ***CSS selector*** tells the browser **which HTML elements to style**.  
Selectors are the *foundation* of CSS. They decide **what gets styled** and **when**.

---

## 🧠 Basic Structure

```css
selector {
  property: value;
}
```

**Example:**

```css
p {
  color: blue;
}
```

👉🏾 This means: *“Style all `<p>` elements.”*

---

## 🔗 Helpful Links (Link Requirement)

Below are **two different Markdown link styles**:

- **Inline-style link:** [MDN CSS Selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_selectors)  
- **Reference-style link:** This is a reference link to [MDN Functions][mdn-functions]  

[mdn-functions]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions

---

## 🖼️ Visual Reference (Image Requirement)

![Anatomy of a CSS Rule](https://learnwebcode.com/wp-content/uploads/2010/02/anatomy-of-a-css-rule.gif)

---

## 🔍 Parts of a CSS Selector

### 1️⃣ Element Selector

Targets **HTML tags**.

```css
p {
  font-size: 16px;
}
```

✔ Targets all `<p>` elements

---

### 2️⃣ Class Selector (`.`)

Targets elements with a **specific class**.

```css
.card {
  border: 1px solid black;
}
```

```html
<div class="card"></div>
```

---

### 3️⃣ ID Selector (`#`)

Targets **one unique element**.

```css
#header {
  background: gray;
}
```

```html
<div id="header"></div>
```

⚠️ *IDs should be used only once per page.*

---

### 4️⃣ Descendant Selector (space)

Targets elements **inside** other elements.

```css
.card p {
  color: red;
}
```

✔ Targets `<p>` elements inside `.card`

---

### 5️⃣ Child Selector (`>`)

Targets **direct children only**.

```css
ul > li {
  list-style: none;
}
```

---

### 6️⃣ Attribute Selector

Targets elements with **specific attributes**.

```css
input[type="text"] {
  border: 2px solid blue;
}
```

---

### 7️⃣ Pseudo-class (`:`)

Targets an element’s **state**.

```css
button:hover {
  background: black;
}
```

---

### 8️⃣ Pseudo-element (`::`)

Targets **part of an element**.

```css
p::first-letter {
  font-size: 2em;
}
```

---

## 📌 Types of CSS Selectors (List Requirement)

Below is a **regular unordered Markdown list** demonstrating list syntax:

- Element selectors
- Class selectors
- ID selectors
- Descendant selectors
- Child selectors
- Attribute selectors
- Pseudo-classes
- Pseudo-elements

---

## 💬 Mental Model (Blockquote Requirement)

> Think of CSS selectors like filters.  
> You describe **what you want**, **where it lives**, and **when it applies**.

---

## 📊 Quick Cheat Sheet (Table Requirement)

| Selector | Meaning |
|--------|--------|
| `p` | element selector |
| `.box` | class selector |
| `#main` | ID selector |
| `div p` | descendant selector |
| `div > p` | child selector |
| `:hover` | pseudo-class |
| `::before` | pseudo-element |

---

## ☑️ Learning Checklist (Checklist Requirement)

Below is a **Markdown task list (checklist)**:

- [x] Understand element selectors  
- [x] Use class and ID selectors  
- [x] Apply descendant and child selectors  
- [x] Recognize pseudo-classes and pseudo-elements  
- [ ] Practice combining selectors  

---

## 🦋 Bonus: Real-World Selector Example

```css
nav ul > li a:hover {
  color: hotpink;
}
```

**Why this matters:**  
This selector combines **structure**, **hierarchy**, and **state** — exactly what you’ll see in real production codebases.

---

## ✨ Final Takeaway

CSS selectors are not just syntax. They are the *language CSS uses to understand your intent*.
