# 🧱 2. HTML Structure Explained (Full Guide)

## 🚀 What is HTML Structure?

HTML structure is the **standard layout of every web page**.

👉 It tells the browser:

* Where content goes
* How elements are organized
* What should load first

Think of it as the **blueprint of a website** 🏗️

---

## 🧠 Real-Life Analogy

* Structure = Building plan
* HTML tags = Rooms (kitchen, bedroom, etc.)

👉 Without structure → everything becomes messy

---

## 📦 Standard HTML Template

Every HTML page follows this structure:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Website</title>
  </head>

  <body>
    <h1>Hello World</h1>
    <p>This is my website</p>
  </body>
</html>
```

---

## 🔍 Breakdown of Each Part

### 1. `<!DOCTYPE html>`

* Declares HTML5
* Prevents browser confusion

---

### 2. `<html>`

* Root element
* Wraps entire webpage

👉 `lang="en"` helps SEO & accessibility

---

### 3. `<head>`

Contains **invisible but important data**:

#### 🔹 `<meta charset="UTF-8">`

* Supports all characters (important!)

#### 🔹 `<meta name="viewport">`

* Makes site responsive on mobile 📱

#### 🔹 `<title>`

* Shows on browser tab

---

### 4. `<body>`

👉 This is what users actually see:

* Headings
* Paragraphs
* Images
* Links
* Buttons

---

## ⚡ Why HTML Structure Matters

✔ Proper rendering in browser
✔ Better SEO ranking
✔ Easier debugging
✔ Clean & maintainable code

👉 Bad structure = broken websites ❌

---

## ❌ Common Beginner Mistakes

* Forgetting `<!DOCTYPE html>`
* Writing content outside `<body>`
* Missing closing tags
* Ignoring viewport meta tag

---

## 🧪 Example: Clean vs Messy

### ❌ Wrong Way

```html
<html>
<h1>Hello</h1>
<body>
<p>Test</p>
```

👉 Missing structure → unpredictable output

---

### ✅ Correct Way

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Correct</title>
  </head>
  <body>
    <h1>Hello</h1>
    <p>Test</p>
  </body>
</html>
```

---

## 🎯 Practice Task

Try this:

1. Create a file: `structure.html`
2. Add:

   * Title: Your Name
   * Heading: “Welcome to My Website”
   * Paragraph: About yourself

---

## 💡 Pro Tips

* Always use proper indentation
* Keep code clean & readable
* Follow standard structure every time

👉 Clean code = professional developer

---

## 🔥 Summary

* Every HTML page has a fixed structure
* `<head>` = invisible data
* `<body>` = visible content
* Proper structure = better websites

---