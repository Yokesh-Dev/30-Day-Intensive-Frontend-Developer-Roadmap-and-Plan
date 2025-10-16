---
## 🧩 Project: Personal Portfolio + Contact Page

### 🎯 Goal
Create a **single HTML page** that showcases your personal brand, skills, projects, and includes a contact form—using semantic structure, forms, validation, and accessibility.
---

## 🧱 Page Layout Overview

### 1. **Header**

- Contains your name or logo
- Navigation menu with links to: Home, About, Projects, Contact

### 2. **Hero Section**

- A welcoming message or tagline
- A profile image with `alt` text
- Use `<section>` and `<figure>`

### 3. **About Me**

- Short bio in a `<section>`
- List of skills using `<ul>` or `<dl>`
- Use semantic tags like `<h2>`, `<p>`, `<strong>`

### 4. **Projects**

- Use `<section>` and `<article>` for each project
- Include:
  - Project title
  - Description
  - Link to live demo or GitHub
  - Screenshot with `alt` text

### 5. **Contact Form**

- Use `<form>` with:
  - Name, Email, Message fields
  - Submit button
- Apply:
  - `required`, `minlength`, `pattern` for validation
  - `<label>` for each input
  - `aria-describedby` or `aria-label` for accessibility

### 6. **Footer**

- Social media links
- Copyright notice
- Use `<footer>`

---

## 🧪 Bonus (Optional)

- Use `<main>` to wrap all content
- Add `<datalist>` for skill suggestions
- Include `<time>` to show last updated date
- Use ARIA attributes for better accessibility

---

## 🛠️ Instructions

- Use only HTML (no CSS or JS yet)
- Focus on clean, semantic structure
- Validate your HTML using [W3C Validator](https://validator.w3.org/)
- Test keyboard navigation and screen reader friendliness

---

Once you’ve built it, feel free to paste your code here—I’ll review it and help you improve it! Ready to level up with styling next? I’ve got you covered.



Fantastic! You've built a solid foundation in HTML—now it's time to put it all together with a **mini project** that tests every concept you've learned.

---

## 🧩 Mini Project: Build a Personal Portfolio + Contact Page

### 🎯 Objective  
Create a **multi-section personal website** that showcases your profile, skills, projects, and includes a fully accessible and validated contact form.

---

## 🧱 Project Requirements

### 1. **Semantic Structure**
Use semantic tags to organize your page:
- `<header>`: Site title and navigation
- `<nav>`: Links to sections (Home, About, Projects, Contact)
- `<main>`: Wraps all primary content
- `<section>`: For each major content block
- `<article>`: For individual projects
- `<footer>`: Social links and copyright

---

### 2. **About Section**
- Use headings and paragraphs to describe yourself
- Include a list of skills using `<ul>` or `<dl>`
- Add a profile image with proper `alt` text

---

### 3. **Projects Section**
- Showcase at least 2 projects using `<article>`
- Include:
  - Title and description
  - Link to live demo or GitHub
  - Screenshot with `alt` text

---

### 4. **Contact Form**
Use a form with:
- Name (`<input type="text">`)
- Email (`<input type="email">`)
- Message (`<textarea>`)
- Submit button (`<button type="submit">`)

Apply:
- `required`, `minlength`, and `pattern` for validation
- `<label>` for each input
- `aria-describedby` for helper text
- Optional: `<fieldset>` and `<legend>` for grouping

---

### 5. **Accessibility**
- Use semantic tags for structure
- Ensure all images have `alt` attributes
- Use `aria-label`, `aria-describedby`, or `role` where needed
- Make sure the form is keyboard-navigable

---

### 🧪 Bonus Features
- Add a `<datalist>` for skill suggestions
- Include a live region (`aria-live`) to show form submission status
- Use `<time>` to show when the site was last updated

---

## 🚀 Extra Credit
- Make navigation links anchor to sections using `id`
- Add a downloadable resume link (`<a href="resume.pdf" download>`)
- Include social media links in the footer

---

Once you’ve built it, paste your code here and I’ll review it for you. Want help styling it with CSS or making it responsive next? I’d love to guide you through that too!