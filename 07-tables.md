# 🎬 7. HTML Tables (Complete Guide)

## 🚀 What are HTML Tables?

HTML tables are used to **display data in rows and columns**.

👉 Best for:

* Student data 📊
* Product lists 🛒
* Reports 📈

---

## 🧠 Real-Life Analogy

Think of:

* School result sheet
* Excel spreadsheet
* Attendance register

👉 All are **tables**

---

## 📦 Basic Table Structure

```html id="n2x8pl"
<table>
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>

  <tr>
    <td>Aviranjan</td>
    <td>20</td>
  </tr>

  <tr>
    <td>Rahul</td>
    <td>22</td>
  </tr>
</table>
```

---

## 🔍 Important Tags

---

### 🔹 `<table>`

* Main container
* Wraps the entire table

---

### 🔹 `<tr>` (Table Row)

* Creates a row

---

### 🔹 `<th>` (Table Header)

* Used for headings
* Bold & centered by default

---

### 🔹 `<td>` (Table Data)

* Normal data cells

---

## 📊 Structure Visualization

| Tag   | Meaning     |
| ----- | ----------- |
| table | Full table  |
| tr    | Row         |
| th    | Header cell |
| td    | Data cell   |

---

## 🌍 Simple Real-World Example

```html id="7y2nqk"
<h2>Student Data</h2>

<table>
  <tr>
    <th>Name</th>
    <th>Course</th>
  </tr>

  <tr>
    <td>Aviranjan</td>
    <td>Web Development</td>
  </tr>

  <tr>
    <td>Riya</td>
    <td>Data Science</td>
  </tr>
</table>
```

---

## ❌ Common Beginner Mistakes

* Missing `<tr>` ❌
* Using `<td>` instead of `<th>` for headers ❌
* Poor indentation ❌

---

## ⚠️ When to Use Tables (Important)

### ✅ Use tables for:

* Tabular data (rows + columns)
* Reports
* Data comparison

---

### ❌ Do NOT use tables for:

* Website layout (old method)
* Designing pages

👉 Use **CSS for layout**, not tables

---

## 🎯 Practice Task

Create a file: `table.html`

Add:

* A table with:

  * Name
  * Age
  * Course

---

## 💡 Pro Tips

* Always use `<th>` for headings
* Keep table clean & readable
* Add borders later using CSS

---

## 🔥 Summary

* `<table>` = container
* `<tr>` = rows
* `<th>` = headings
* `<td>` = data

👉 Tables = structured data display

---

## 🚀 Next Step

👉 Next lesson: **Semantic HTML (Write cleaner & professional code)**

---