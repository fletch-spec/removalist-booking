# Mylo Removalist Website – Local Hosting Edition

A beginner-friendly project to learn **HTML, CSS, and modular web design**, hosted locally using **Python’s built-in HTTP server**.  
The site includes three main pages: **Landing**, **Services**, and **Contact**, with features like responsive layout, image galleries, and a contact form.

---

## 🚀 Project Objectives

- Design and build a clean, simple HTML/CSS business website.
- Practice responsive layouts, modular file structure, and JavaScript interactivity.
- Host locally with Python’s `http.server` module.
- Apply best practices in accessibility, UX, and styling consistency.

---

## 🗂️ Directory Structure

```
/MyloWebsite
  /css
    style.css
  /img
    gallery1.jpg, ...
  /js
    gallery.js
  index.html
  services.html
  contact.html
```

---

## ✅ Completed Tasks

### 🔧 Setup
- [x] Python installed and HTTP server tested:
  ```bash
  python -m http.server 8000
  ```
- [x] Project and Git initialized

### 🧱 Structure
- [x] CSS and JS organized into separate folders
- [x] HTML pages linked and modular

### 🏠 Landing Page
- [x] Header and navbar setup
- [x] Image gallery (JavaScript) rotates images every 5s
- [x] Responsive, centered layout with proper spacing

### 🛠️ Services Page
- [x] Three service sections with titles, descriptions, and booking buttons
- [x] Consistent layout and styling
- [x] Buttons autofill contact form

### ✉️ Contact Page
- [x] Contact form (name, email, message)
- [x] Validation and highlighting of empty fields
- [x] Autofill message box from service selection
- [x] Reset highlighting on user input

### 📎 Footer
- [x] Contains location (left), email/phone (right), and centered contact button
- [x] Fully responsive and mobile-friendly

### 🌐 Hosting
- [x] Works locally using Python server
- [x] Loads on other devices via local IP (if firewall permits)

---

## 📝 Future Improvements

- [ ] Add favicon and custom tab title icon
- [ ] Smooth gallery animation/pagination
- [ ] Modular navbar with JS/HTML templates (advanced)
- [ ] Backend form handling (optional future upgrade)
- [ ] Final polish & accessibility pass
- [ ] Create screenshots for portfolio use

---

## 📦 How to Run Locally

1. Clone or unzip project into a directory:
   ```bash
   cd MyloWebsite
   ```
2. Start the server:
   ```bash
   python -m http.server 8000
   ```
3. Open `http://localhost:8000` in your browser.

---

© 2025 Mylo Removalist Website. Built for learning and deployment practice.