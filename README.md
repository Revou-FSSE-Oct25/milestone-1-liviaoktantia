# Personal Landing Page — Livia Oktantia

A minimalist, one-page personal website to introduce my profile, showcase early projects, and provide a simple way to contact me. Built as part of the **RevoU Software Engineering** learning journey using **plain HTML5 with inline styles** (no external CSS frameworks, no JavaScript).

---

## Overview

This landing page is my first digital profile. It presents:
- A concise **hero** introducing who I am and what this page is for.
- An **About Me** section with a short bio and (on larger screens) a side-by-side layout for photo and text using simple HTML.
- A **Projects** section listing early software engineering exercises and several digital marketing works in a semantic table.
- A **Contact** section with an accessible HTML form (client-side only, no backend) so visitors can draft a message.

The goal is to practice clean structure, semantic HTML, and basic styling while keeping the page easy to read and extend.

---

## Deployed Site & How to Use

**Live URL:**  
https://revou-fsse-oct25.github.io/milestone-1-liviaoktantia/

**Navigation**
- Use the top navigation (Home / About me / Projects / Contact) to jump between sections on the same page.
- External links (e.g., LinkedIn, portfolio download) open in a new tab.

**What you can do on the page**
- **Read the intro** in the Hero section to understand the site’s purpose.
- **Explore About Me** to learn my background and areas of expertise.
- **Browse Projects** to see placeholder software items and selected digital marketing highlights.  
  - There is a link to **download a group portfolio PDF** from the table.
- **Use the Contact form** to draft a message.  
  - The form uses basic HTML validation (required fields and email input type).  
  - No backend is connected yet, so submitting the form does not send messages.

---

## Features

- **Semantic HTML5**
  - Proper sectioning elements (`<header>`, `<main>`, `<section>`, `<footer>`).
  - Descriptive headings (`<h1>` … `<h4>`) with a clear hierarchy.
  - `<nav aria-label="Primary">` for better accessibility.
  - `<figure>` and `<img alt="">` for the profile picture.

- **Meta & Accessibility Basics**
  - Mobile-friendly viewport.
  - Meta tags for description, keywords, and author.
  - Descriptive link text and `rel="noopener"` on external links.

- **About Me Layout (no flex/grid)**
  - Simple **presentation table** to position the photo on the left and text on the right (keeps to assignment constraints).

- **Projects Table**
  - Semantic table with `<caption>`, `<thead>`, and column headers.
  - Consistent cell padding and readable contrast.
  - Example link to a downloadable PDF.

- **Contact Form (HTML-only)**
  - Labeled inputs for first name, last name, email, and message.
  - Basic validation via `required` and `type="email"`.
  - Grouped with `<fieldset>` and `<legend>` for clarity.

- **Inline Styling Only**
  - All styles applied via `style` attributes (no external stylesheets).
  - Consistent, minimal color use anchored by **Castleton Green (#005C46)**.

---

## Technologies Used

- **HTML5** (structure, semantics, accessibility fundamentals)
- **Inline CSS** (basic visual styling only; no external CSS files, no frameworks)
- **Assets**
  - Images (e.g., `image/livia-oktantia.webp`, social icons in `image/`)
  - PDF download link from the Projects table
- **Hosting / Deployment**
  - **GitHub Pages** for static site hosting
- **Tooling (development)**
  - **VS Code** (editing)
  - **Git & GitHub** (version control, collaboration)
  - **Command Prompt (Windows CMD)** for git/CLI work

---

## Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/revou-fsse-oct25/milestone-1-liviaoktantia.git
   cd milestone-1-liviaoktantia