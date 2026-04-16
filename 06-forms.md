# 🎬 6. HTML Forms & Inputs (Complete Guide)

## 🚀 What are HTML Forms?

HTML forms are used to **collect user data**.

👉 Examples:

* Login page 🔐
* Signup form 📝
* Contact form 📩

---

## 🧠 Real-Life Analogy

Think of a form like a **paper application form**:

* You enter details
* Submit it
* Someone processes it

👉 Same concept in websites

---

## 📦 Basic Form Structure

```html id="z9x3op"
<form>
  <label>Name:</label>
  <input type="text" />

  <label>Password:</label>
  <input type="password" />

  <label>Email:</label>
  <input type="email" />

  <button>Submit</button>
</form>
```

---

## 🔍 Important Elements

---

### 🔹 `<form>`

* Wraps all input fields
* Sends data to server (later with backend)

---

### 🔹 `<input>` Types

#### 1. Text Input

```html id="2r8cql"
<input type="text" placeholder="Enter your name" />
```

👉 Used for names, usernames

---

#### 2. Password Input

```html id="y3q7ne"
<input type="password" />
```

👉 Hides characters (security)

---

#### 3. Email Input

```html id="g6k1vx"
<input type="email" />
```

👉 Validates email automatically

---

### 🔹 `<label>`

```html id="x9b2td"
<label for="name">Name:</label>
<input id="name" type="text" />
```

👉 Improves:

* Accessibility ♿
* User experience

---

### 🔹 `<button>`

```html id="9b3kqz"
<button type="submit">Submit</button>
```

👉 Submits the form

---

## 🌍 Real-World Example

```html id="q7d1mk"
<h2>Contact Form</h2>

<form>
  <label for="name">Name:</label>
  <input id="name" type="text" placeholder="Your name" />

  <label for="email">Email:</label>
  <input id="email" type="email" placeholder="Your email" />

  <label for="password">Password:</label>
  <input id="password" type="password" />

  <button type="submit">Send</button>
</form>
```

---

## ❌ Common Beginner Mistakes

* Not using `<label>` ❌
* Missing `type` in `<input>` ❌
* Forgetting `for` and `id` connection ❌
* No placeholder or guidance ❌

---

## 🎯 Practice Task

Create a file: `form.html`

Add:

* Name (text input)
* Email (email input)
* Password (password input)
* Submit button

---

## 💡 Pro Tips

* Always use labels
* Use correct input types
* Keep forms simple

👉 Good forms = better user experience

---

## 🔥 Summary

* `<form>` collects user data
* `<input>` takes input
* `<label>` improves usability
* `<button>` submits data

---

## 🚀 Next Step

👉 Next lesson: **Semantic HTML (Write like a pro developer)**
