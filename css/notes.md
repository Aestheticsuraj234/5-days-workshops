
## 🕐 **CSS Basics – 2 Hour Crash Course Notes**

---

### ✅ **1. What is CSS? (5 min)**

- **CSS = Cascading Style Sheets**
- It styles HTML elements (colors, spacing, fonts, layout)
- HTML = structure, CSS = presentation

```html
<!-- Example -->
<p>This is HTML</p>

<style>
  p {
    color: blue;
    font-size: 20px;
  }
</style>
```

---

### ✅ **2. Ways to Apply CSS (10 min)**

- **Inline CSS**
  ```html
  <p style="color: red;">Inline Style</p>
  ```
- **Internal CSS**
  ```html
  <style>
    p {
      color: green;
    }
  </style>
  ```
- **External CSS**
  ```html
  <link rel="stylesheet" href="styles.css" />
  ```

📌 **Use external CSS in real projects**

---

### ✅ **3. Selectors (15 min)**

- **Element selector**: `p { color: red; }`
- **Class selector**: `.title { font-weight: bold; }`
- **ID selector**: `#main { background: yellow; }`
- **Universal selector**: `* { margin: 0; }`
- **Group selector**: `h1, h2 { color: purple; }`
- **Nested selector**: `div p { color: orange; }`

```html
<p class="title" id="main">Styled text</p>
```

---

### ✅ **4. Properties and Values (25 min)**

#### ✨ Text Styling
```css
color: red;
font-size: 18px;
font-weight: bold;
text-align: center;
text-decoration: underline;
```

#### ✨ Box Model (Padding, Margin, Border)
```css
padding: 10px;
margin: 20px;
border: 1px solid black;
```

#### ✨ Background
```css
background-color: lightblue;
background-image: url("img.png");
```

#### ✨ Width & Height
```css
width: 200px;
height: 100px;
```

---

### ✅ **5. Classes vs IDs (10 min)**

- `.class` can be used **multiple times**
- `#id` should be used **once**

```css
.box {
  background: yellow;
}

#unique {
  background: pink;
}
```

---

### ✅ **6. Positioning and Display (30 min)**

#### 🧭 Positioning
```css
position: static | relative | absolute | fixed | sticky;
top, bottom, left, right
```

```css
.box {
  position: absolute;
  top: 10px;
  left: 20px;
}
```

#### 📦 Display
```css
display: block | inline | inline-block | flex | grid | none;
```

```css
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
```

---

### ✅ **7. Bonus: Hover & Transitions (15 min)**

#### 🖱️ Hover Effect
```css
button:hover {
  background-color: green;
  color: white;
}
```

#### ⏳ Transitions
```css
.box {
  transition: all 0.3s ease;
}
```

---

### ✅ Practice Mini Project (10 min)

Create a basic card:

```html
<div class="card">
  <h2>Card Title</h2>
  <p>This is a card.</p>
  <button>Click Me</button>
</div>
```

```css
.card {
  background: #f4f4f4;
  padding: 20px;
  width: 300px;
  border-radius: 10px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}
.card button:hover {
  background: blue;
  color: white;
}
```

---

## 📝 Summary Sheet (Revision)

| Topic | Key Concept |
|------|-------------|
| Selectors | `element`, `.class`, `#id`, `*`, `group` |
| Text | `color`, `font-size`, `text-align` |
| Box Model | `padding`, `margin`, `border` |
| Layout | `display: flex`, `position: relative` |
| Styling | `background-color`, `width`, `height` |
| Interaction | `:hover`, `transition` |

