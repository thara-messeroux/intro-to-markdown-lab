# 🧩 The Anatomy of a CSS Selector

A **CSS selector** tells the browser **which HTML elements to style**.

## 🧠 Basic Structure

```css
selector {
  property: value;
}
```
***Example:***

```css
p {
  color: blue;
}
```
> 👉 This means: **“Style all `<p>` elements.”**

## 🔍 Parts of a CSS Selector
![Anatomy of a CSS Rule](https://learnwebcode.com/wp-content/uploads/2010/02/anatomy-of-a-css-rule.gif)

### 1️⃣ Element Selector

Targets HTML tags.

```css
    p {
  font-size: 16px;
}
```
> ✔ Targets all `<p>` tags

### 2️⃣ Class Selector (.)

Targets elements with a specific class.

```css
.card {
  border: 1px solid black;
}
```
✔ Targets:

```html
<div class="card"></div>
```

### 3️⃣ ID Selector (#)

Targets one unique element.

```css
#header {
  background: gray;
}
```
✔ Targets:

```html
<div id="header"></div>
```
> ⚠️ Use IDs sparingly (only once per page)

### 4️⃣ Descendant Selector (space)
Targets elements inside other elements.
```css 
.card p {
  color: red;
}
```
> ✔ Targets `<p>` inside .card

### 5️⃣ Child Selector (>)

Targets direct children only.

```css
ul > li {
  list-style: none;
}
```
> ✔ Targets `<li>` directly inside `<ul>`

### 6️⃣ Attribute Selector

Targets elements with attributes.

```css
input[type="text"] {
  border: 2px solid blue;
}
```
> ✔ Targets text inputs only

### 7️⃣ Pseudo-class (:)
```css
button:hover {
  background: black;
}
```
> ✔ When the user hovers
### 8️⃣ Pseudo-element (::)






