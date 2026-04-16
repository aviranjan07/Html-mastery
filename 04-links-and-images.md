# 🎬 4. HTML Links & Images (Complete Guide)

## 🚀 What are Links & Images?

Links and images make your website:

* 🔗 **Interactive** (users can navigate)
* 🖼️ **Visual** (more engaging & attractive)

👉 Without them, a website feels **dead and boring**

---

## 🔗 HTML Links (`<a>` tag)

The `<a>` tag is used to create **clickable links**.

```html
<a href="https://google.com">Visit Google</a>
```

---

## 🔍 `href` Attribute

* `href` = **Hypertext Reference**
* It tells the browser **where to go**

### 📌 Types of Links

#### 1. External Link

```html
<a href="https://google.com">Google</a>
```

#### 2. Internal Link

```html
<a href="about.html">About Page</a>
```

#### 3. Open in New Tab

```html
<a href="https://google.com" target="_blank">Open Google</a>
```

---

## 🖼️ HTML Images (`<img>` tag)

Used to display images on a webpage.

```html
<img src="image.jpg" alt="Description">
```

---

## 🔍 Important Attributes

### 🔹 `src`

* Source of the image (file path or URL)

---

### 🔹 `alt` (Very Important ⚠️)

* Describes the image
* Shows if image fails to load
* Helps **screen readers (accessibility)**
* Improves **SEO**

```html
<img src="cat.jpg" alt="Cute cat sitting on a sofa">
```

👉 Always use meaningful `alt` text

---

## 🌍 Real-World Example

```html
<h1>My Portfolio</h1>

<p>Visit my <a href="https://github.com">GitHub</a></p>

<img src="profile.jpg" alt="Profile picture of Aviranjan">
```

---

## ❌ Common Beginner Mistakes

* Missing `href` in `<a>` ❌
* Using wrong file path ❌
* Not adding `alt` attribute ❌
* Broken image links ❌

---

## 🎯 Practice Task

Create a file: `links-images.html`

Add:

* A link to your favorite website
* A link to another page (internal)
* One image with proper `alt` text

---

## 💡 Pro Tips

* Use `target="_blank"` for external links
* Keep `alt` text short but meaningful
* Optimize image size for faster loading

👉 Fast + accessible = professional website

---

## 🔥 Summary

* `<a>` creates links
* `href` defines destination
* `<img>` displays images
* `alt` improves SEO & accessibility

---

## 🚀 Next Step

👉 Next lesson: **Lists & Tables (Organizing Data)**
