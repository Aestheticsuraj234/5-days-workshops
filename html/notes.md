

### **1. Basic Structure of HTML**
The HTML document starts with `<!DOCTYPE html>`, which declares the document type and version of HTML (HTML5). It consists of `<html>`, `<head>`, and `<body>` tags.

#### Example:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document Title</title>
  </head>
  <body>
    <!-- Content goes here -->
  </body>
</html>
```

---

### **2. Headings (`<h1>` to `<h6>`)**
Headings are used to define titles or subtitles on a webpage. `<h1>` is the largest heading, while `<h6>` is the smallest.

#### Example:
```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
<h3>Smaller Subheading</h3>
```

---

### **3. Paragraphs (`<p>`)**
Paragraphs are used to display blocks of text.

#### Example:
```html
<p>This is a paragraph of text.</p>
<p><b>Bold Text</b> and <i>Italic Text</i> can be styled using tags.</p>
```

---

### **4. Lists**
There are two types of lists: ordered (`<ol>`) and unordered (`<ul>`).

#### Ordered List Example:
```html
<ol type="a">
  <li>First item</li>
  <li>Second item</li>
</ol>
```

#### Unordered List Example:
```html
<ul style="list-style-type: square;">
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
```

---

### **5. Hyperlinks (`<a>`)**
Hyperlinks allow navigation between pages or websites. The `href` attribute specifies the URL, and `target="_blank"` opens the link in a new tab.

#### Example:
```html
<a href="https://www.google.com" target="_blank">Visit Google</a>
```

---

### **6. Images (`<img>`)**
Images are added using the `<img>` tag. The `src` attribute specifies the image path, and `alt` provides alternative text if the image fails to load.

#### Example:
```html
<img src="./image.jpg" alt="Description of Image" height="150" width="150">
```

---

### **7. Forms (`<form>`)**
Forms collect user input. Common input types include `text`, `email`, `password`, `number`, `date`, and `submit`.

#### Example:
```html
<form action="#">
  <input type="text" placeholder="Enter your name" />
  <br /><br />
  <input type="email" placeholder="Enter your email" />
  <br /><br />
  <button type="submit">Submit</button>
</form>
```

---

### **8. Tables (`<table>`)**
Tables organize data into rows and columns. `<tr>` defines table rows, `<th>` defines headers, and `<td>` defines data cells.

#### Example:
```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>John</td>
    <td>25</td>
    <td>USA</td>
  </tr>
</table>
```

---

### **9. Semantic Tags**
Semantic tags like `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>` improve the structure and readability of the document.

#### Example:
```html
<header>
  <h1>Welcome to My Website</h1>
</header>

<main>
  <p>This is the main content of the page.</p>
</main>

<footer>
  <p>Copyright &copy; 2023</p>
</footer>
```

---

### **10. Audio and Video Elements**
These elements embed multimedia content into the webpage.

#### Audio Example:
```html
<audio controls>
  <source src="./audio.mp3" type="audio/mp3">
  Your browser does not support the audio element.
</audio>
```

#### Video Example:
```html
<video controls height="200" width="300" autoplay loop>
  <source src="./video.mp4" type="video/mp4">
  Your browser does not support the video element.
</video>
```

---

### **11. Inline Styling**
Inline styles can be applied directly to elements using the `style` attribute.

#### Example:
```html
<p style="color: red; font-size: 18px;">This text is styled inline.</p>
```

---

### **12. Special Characters**
Special characters like copyright (`&copy;`) and trademark (`&reg;`) symbols can be added using HTML entities.

#### Example:
```html
<p>Copyright &copy; 2023</p>
<p>Registered &reg; Trademark</p>
```

---

### **13. Comments**
Comments are ignored by browsers and used for documentation or notes within the code.

#### Example:
```html
<!-- This is a comment -->
```

---

### **14. Sections and IDs**
Sections group related content, and IDs uniquely identify elements for styling or scripting.

#### Example:
```html
<section id="skills">
  <h2>My Skills</h2>
  <ul>
    <li>HTML</li>
    <li>CSS</li>
  </ul>
</section>
```

---

### **15. Navigation Bar**
A navigation bar can be created using `<nav>` and a list of links.

#### Example:
```html
<nav>
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>
```

---

### **16. Horizontal Rules and Line Breaks**
`<hr>` creates a horizontal line, and `<br>` adds a line break.

#### Example:
```html
<p>Some text.<br>More text after the break.</p>
<hr>
<p>Another section separated by a horizontal line.</p>
```

---

### **17. Emphasis and Formatting**
Tags like `<b>`, `<i>`, and `<u>` format text as bold, italic, and underlined, respectively.

#### Example:
```html
<p><b>Bold</b>, <i>italic</i>, and <u>underlined</u> text.</p>
```

---

### **Summary**
Your code demonstrates several fundamental HTML concepts, including:
- Document structure
- Headings, paragraphs, and text formatting
- Lists and hyperlinks
- Images and multimedia
- Forms and tables
- Semantic tags and sections
- Inline styling and special characters

