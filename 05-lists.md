# 🎬 5. HTML Lists (Complete Guide)

## 🚀 What are HTML Lists?

HTML lists are used to **group related items together** in a structured way.

👉 They make content:

* Easy to read 👀
* Well-organized 📚
* Professional-looking 💻

---

## 🧠 Real-Life Analogy

Think of daily life:

* Shopping list 🛒
* To-do list ✅
* Recipe steps 🍳

👉 All of these are **lists**

---

## 🔢 Ordered List (`<ol>`)

Used when **order matters** (steps, ranking, instructions)

```html id="f2s9xp"
<ol>
  <li>Wake up</li>
  <li>Study HTML</li>
  <li>Practice coding</li>
</ol>
```

### ⚡ Output:

1. Wake up
2. Study HTML
3. Practice coding

---

## 🔘 Unordered List (`<ul>`)

Used when **order does NOT matter**

```html id="9xv2gk"
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>
```

### ⚡ Output:

* HTML
* CSS
* JavaScript

---

## 📦 List Items (`<li>`)

* `<li>` = List Item
* Used inside both `<ol>` and `<ul>`

👉 Without `<li>`, list will not work properly

---

## 🔁 Nested Lists (Important 🔥)

Lists inside lists → used for **hierarchy**

```html id="uxs3o8"
<ul>
  <li>Frontend
    <ul>
      <li>HTML</li>
      <li>CSS</li>
    </ul>
  </li>
  <li>Backend</li>
</ul>
```

---

## 🌍 Real-World Example

```html id="74r9xk"
<h2>My Daily Routine</h2>

<ol>
  <li>Morning
    <ul>
      <li>Exercise</li>
      <li>Breakfast</li>
    </ul>
  </li>
  <li>Work</li>
  <li>Study</li>
</ol>
```

---

## ❌ Common Beginner Mistakes

* Not using `<li>` ❌
* Mixing `<ol>` and `<ul>` incorrectly ❌
* Poor indentation ❌

---

## 🎯 Practice Task

Create a file: `lists.html`

Add:

* One ordered list (your daily routine)
* One unordered list (your skills)
* One nested list (Frontend & Backend)

---

## 💡 Pro Tips

* Use `<ol>` for steps/instructions
* Use `<ul>` for general items
* Always indent nested lists

👉 Clean structure = clean thinking

---

## 🔥 Summary

* `<ol>` → Ordered list (numbered)
* `<ul>` → Unordered list (bullets)
* `<li>` → List items
* Nested lists → hierarchy

---

## 🚀 Next Step

👉 Next lesson: **Tables (Display Data in Rows & Columns)**

---
