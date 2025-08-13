# HTML + CSS Crash Session — Class Repo Readme

## HTML + CSS Crash Session (15‑Minute Blitz)

Welcome! This repo is your starting point for an introduction to HTML & CSS followed by a paired challenge. You’ll install VS Code extensions, fork this repo, complete a technical quiz, and do an HTML + CSS Challenge with tiers (**Easy → Medium → Hard**).

---

## 0) Prereqs

- **VS Code installed**
- **Git + GitHub account** (logged in)

---

## 1) Install these VS Code extensions

Open VS Code → Extensions → search & install:

- **Live Preview** (Microsoft)
- **Live Server** (Ritwick Dey)
- **Prettier – Code Formatter**
- **vscode-icons**

> **Tip:** After installing Prettier, set it as default formatter:  
> Command Palette → “Format Document With…” → “Configure Default Formatter”

---

## 2) Fork & Clone this Repo

1. Click **Fork** (GitHub)
2. Open GitHub Desktop.
3. File → Clone Repository → select your fork.
4. Choose a local folder and click Clone.
5. Open in VS Code from GitHub Desktop.

Use VS Code to edit and GitHub Desktop to commit and push.

---

## 3) 15‑Minute Blitz (Teacher‑led)

We’ll cover:

- **HTML skeleton:**  
  `<!doctype html>`, `<html>`, `<head>`, `<meta>`, `<title>`, `<body>`
- **Headings & text:**  
  `<h1>`…`<h6>`, `<p>`, `<strong>`, `<em>`
- **Lists & links:**  
  `<ul>`, `<ol>`, `<li>`, `<a href target rel>`
- **Images & media:**  
  `<img alt>`, `<figure>`, `<figcaption>`
- **Semantic structure:**  
  `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`
- **Tables & forms:**  
  `<table>`, `<thead>`, `<tbody>`, `<th scope>`, `<form>`, `<label for>`, inputs
- **CSS basics:**  
  selectors, properties, linking CSS (`<link rel="stylesheet" href="styles.css">`)

Start a preview with **Live Preview** or **Live Server**:  
Right‑click `index.html` → **Open with Live Server**.

---

## 4) Technical Quiz (warm‑up)

1. Open `technicalQuiz.md` and answer questions.
2. When done, make sure to commit and push your new changes

---

## 5) The HTML + CSS Challenge

Choose tasks from each tier. **Complete at least 4 Easy, 3 Medium, 2 Hard.**  
If done early, continue or polish with CSS.

### ✅ Rules
- Work in pairs (swap every ~10 mins)
- Make small commits with clear messages
- Prioritize accessibility (alt text, labels, heading order)

### 🧩 Deliverables
- `index.html` (main page)
- Additional HTML files as needed (e.g., `about.html`)
- `styles.css` for styling

### 📦 Submission Checklist

---

## 🟢 **Easy** (pick at least 4)

- 🟢 **HTML Skeleton + Basic Styling:**  
  Add CSS to change background color.
- 🟢 **Headings & Paragraphs with CSS:**  
  Add H1, subheading, two paragraphs. Style headings with font sizes and colors.
- 🟢 **Lists with CSS:**  
  Add one unordered list (3+ items) and one ordered list (3+ items). Style markers and spacing.
- 🟢 **Links with Hover Effects:**  
  Add external link opening in new tab (`target="_blank"` + `rel="noopener"`). Style color and hover.
- 🟢 **Image with Alt and Caption Styling:**  
  Add image with alt inside `<figure>` and `<figcaption>`. Style figure and caption.
- 🟢 **Contact Links with CSS:**  
  Add `mailto:` and `tel:` links. Style colors and underline on hover.
- 🟢 **Page Sections with Basic Layout:**  
  Use `<header>`, `<main>`, `<section>`, `<footer>`. Add padding and background colors.

---

## 🟡 **Medium** (pick at least 3)

- 🟡 **Internal Navigation Bar with Flexbox:**  
  Add `<nav>` with anchor links to sections. Use flexbox for horizontal bar with spacing and hover.
- 🟡 **Two‑Page Site with Styled Links:**  
  Create `about.html` and link to it from `index.html` and back. Style navigation links consistently.
- 🟡 **Accessible Form with Styled Inputs:**  
  Create contact form with `<label for>`, required inputs, placeholder, and name. Include radio or checkbox group in `<fieldset>` with `<legend>`. Style inputs and buttons.
- 🟡 **Table with Semantics and Styling:**  
  Build table with `<caption>`, `<thead>`, `<tbody>`, `<th scope>`. Add borders, alternating row colors, styled headers.
- 🟡 **Media Embed with Styled Container:**  
  Embed YouTube video or audio with `<iframe>` or `<audio controls>`; add description. Style container with borders, padding, responsive width.
- 🟡 **Responsive Images with CSS:**  
  Use `<picture>` or `srcset` for responsive image. Add CSS for max-width, margins, display.
- 🟡 **Metadata and Social Preview:**  
  Add `<meta name="description">` and social preview tags (Open Graph: `og:title`, `og:description`).

---

## 🔴 **Hard** (pick at least 2)

- 🔴 **Multi‑Section Landing Page with Styled Layout:**  
  Use `<header>`, `<nav>`, `<main>`, `<article>`, `<aside>`, `<footer>` with 4+ sections and skip‑to‑content link. Use CSS grid or flexbox for layout.
- 🔴 **Advanced Form with Validation and Styling:**  
  Add pattern validation (e.g., NZ phone), `<datalist>` suggestions, and title tooltips. Style inputs with borders, shadows, error states.
- 🔴 **Accessible and Styled Table Pro:**  
  Add table with multi‑level headers using `<colgroup>` or correct `scope`. Ensure screen reader usability. Style with hover effects, fixed headers, responsive.
- 🔴 **Cards Grid (HTML + CSS):**  
  Mark up grid of 6+ cards (image + heading + text + link) using semantic tags. Use CSS grid or flexbox for responsive layout with spacing and hover.
- 🔴 **Inline SVG Icon with Styling and Accessibility:**  
  Add inline SVG icon (e.g., star) in two places with `aria-hidden` or `<title>`. Style color, size, hover.
- 🔴 **Figure Gallery with Responsive CSS:**  
  Create gallery with multiple `<figure>` + `<figcaption>` inside semantic container with heading. Use CSS grid or flexbox for responsive layout with gaps and hover.
- 🔴 **Blog Article Page with Styled Content:**  
  Create `post.html` with `<article>` containing title, byline (`<address>` or metadata), publish date (`<time datetime>`), and code snippet (`<pre><code>`). Style typography, spacing, and code.

---

> **CSS is required for challenge tasks to improve structure and presentation**
