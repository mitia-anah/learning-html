# HTML Learning Lab 🎓

A hands-on lab designed to help you master the fundamentals of HTML through structured exercises and real-world examples.

## 📚 About This Lab

This comprehensive lab provides 7 progressive exercises covering essential HTML concepts including:
- Semantic HTML structure
- Proper element nesting
- HTML attributes and their rules
- Best practices for writing HTML
- Common HTML5 elements

## 🎯 Learning Objectives

By completing this lab, you will:
- Understand proper HTML document structure
- Master semantic HTML5 elements
- Learn correct nesting and indentation
- Apply HTML attributes correctly
- Follow HTML coding best practices
- Create well-structured, accessible web pages

## 📋 Prerequisites

- Basic understanding of what HTML is
- A text editor (VS Code, Sublime Text, Atom, etc.)
- A web browser (Chrome, Firefox, Safari, etc.)
- Basic command line knowledge (optional)

## 🚀 Getting Started

### 1. Clone or Download This Repository

```bash
git clone https://github.com/mitia-anah/learning-html.git
cd learning-html
```

### 2. Open in Your Text Editor

```bash
code .  # If using VS Code
```

### 3. Start with the Index Page

Open `index.html` in your browser to see the list of all exercises.

### 4. Complete the Exercises

Navigate to the `exercises/` folder and start with `01-homepage.html`. Each file contains:
- HTML structure with TODO comments
- Clear instructions on what to implement
- Guidance on which elements to use

### 5. View Your Progress

Open each exercise file in your browser to see your work as you build it.

### 6. Check Your Solutions

When you complete an exercise, compare your work with the corresponding file in the `solutions/` folder.

## 📁 Project Structure

```
learning-html/
├── index.html                  # Main landing page with exercise list
├── README.md                   # This file
├── exercises/                  # Starter files with TODO instructions
│   ├── 01-homepage.html
│   ├── 02-learning-html.html
│   ├── 03-nesting-rules.html
│   ├── 04-attribute-rules.html
│   ├── 05-list-of-rules.html
│   ├── 06-tips-for-writing.html
│   └── 07-html-elements-table.html
├── solutions/                  # Completed examples for reference
│   ├── 01-homepage.html
│   ├── 02-learning-html.html
│   ├── 03-nesting-rules.html
│   ├── 04-attribute-rules.html (to be completed)
│   ├── 05-list-of-rules.html
│   ├── 06-tips-for-writing.html
│   └── 07-html-elements-table.html
└── resources/                  # Shared resources
    └── sections.css           # Styling for all pages
```

## 🔢 Exercise Overview

### Exercise 1: Creating a Homepage
Learn to structure a basic homepage with header, main content, and footer.

**Key Concepts:** `<header>`, `<main>`, `<article>`, `<footer>`, `<nav>`

### Exercise 2: Learning HTML Structure
Build a more complex page with multiple sections and navigation.

**Key Concepts:** `<section>`, `<nav>`, linking between pages, `<abbr>`

### Exercise 3: Understanding Nesting Rules
Practice proper element nesting with lists and other nested structures.

**Key Concepts:** Correct nesting order, nested lists, `<fieldset>`, `<label>`

### Exercise 4: Working with Attributes
Learn attribute rules and how to apply them correctly.

**Key Concepts:** Attribute syntax, quoting values, boolean attributes

### Exercise 5: HTML Writing Rules
Create a comprehensive page listing all HTML writing rules.

**Key Concepts:** Ordered lists, inline elements, internal linking

### Exercise 6: Tips for Writing HTML
Build a tips page with practical advice for HTML development.

**Key Concepts:** Multiple sections, semantic structure, abbreviations

### Exercise 7: HTML Elements Reference Table
Create a detailed table documenting common HTML elements.

**Key Concepts:** Tables, `<table>`, `<thead>`, `<tbody>`, `<caption>`

## 💡 Tips for Success

1. **Read the TODO comments carefully** - They provide specific instructions
2. **Work sequentially** - Each exercise builds on previous concepts
3. **Test frequently** - Open your file in a browser after each change
4. **Use the browser inspector** - Right-click → Inspect to see your HTML structure
5. **Don't peek too early** - Try to complete exercises before checking solutions
6. **Validate your HTML** - Use the [W3C Validator](https://validator.w3.org/)
7. **Experiment** - Try adding extra elements to deepen your understanding

## 🔍 How to Test Your Work

### Method 1: Direct Browser Opening
1. Right-click on any HTML file
2. Select "Open with" → Your browser
3. View the rendered page

### Method 2: Live Server (VS Code)
1. Install the "Live Server" extension in VS Code
2. Right-click on an HTML file
3. Select "Open with Live Server"
4. Changes will auto-reload in the browser

### Method 3: Command Line
```bash
# Navigate to the project directory
cd learning-html

# Open index.html in your default browser (Linux)
xdg-open index.html

# Or for specific exercise
xdg-open exercises/01-homepage.html
```

## 🎨 Customization

Feel free to:
- Modify the CSS in `resources/sections.css`
- Add additional exercises
- Extend existing exercises with more content
- Create your own variations

## 📖 Additional Resources

- [MDN HTML Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [HTML5 Specification](https://html.spec.whatwg.org/)
- [W3C HTML Tutorial](https://www.w3schools.com/html/)
- [HTML Semantic Elements Guide](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

## 🐛 Common Issues & Solutions

**Q: My styles aren't loading**
- Check that the CSS path in your `<link>` tag is correct: `href="../resources/sections.css"`

**Q: My links don't work**
- Verify the file paths in your `<a href="">` attributes
- Remember to use relative paths from the current file location

**Q: My page looks different from the solution**
- That's okay! Focus on getting the HTML structure correct
- Visual differences are normal with different content

## 📝 Validation

Before considering an exercise complete:
1. Open the HTML file in your browser - does it display correctly?
2. Check the browser console (F12) - are there any errors?
3. Validate your HTML at [validator.w3.org](https://validator.w3.org/)
4. Compare structure (not necessarily content) with the solution

## 🤝 Contributing

This is a learning lab, but suggestions for improvements are welcome! If you find errors or have ideas for new exercises, feel free to open an issue or submit a pull request.

## 📧 Contact

For questions or feedback: [rratsianompo@gmail.com](mailto:rratsianompo@gmail.com)

## 📜 License

This project is open source and available for educational purposes.

---

**Happy Learning! Start with `index.html` and enjoy mastering HTML! 🚀**
