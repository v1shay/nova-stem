# STEM Outreach Platform
> A lightweight web platform for running, organizing, and scaling hands-on STEM education programs.

---

## Features
- Static, fast-loading site built with plain HTML, CSS, and JavaScript  
- Program pages for workshops, curricula, and events  
- Clear separation between content, layout, and behavior  
- Easy to update without a backend or build tooling  
- Designed to be understandable and maintainable by students  

---

## Why This Exists
A lot of STEM outreach efforts fail not because the ideas are bad, but because the infrastructure is fragile. Sites are overengineered, hard to update, or dependent on tools that volunteers don’t know how to use.

This platform keeps things simple. It prioritizes clarity, accessibility, and ease of maintenance so the focus stays on teaching, not tooling.

---

## How It Works
The platform is intentionally minimal and transparent.

1. Content is written directly in HTML for clarity and control  
2. CSS handles layout and responsiveness without heavy frameworks  
3. JavaScript adds small interactive behaviors where needed  
4. The site can be deployed anywhere that supports static hosting  

There is no backend dependency, which makes the system easy to host, clone, and extend.

---

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **Hosting:** Static hosting (GitHub Pages, Vercel, Netlify, etc.)  
- **Architecture:** Static site with modular assets  

---

## Project Structure
```text
stem-platform/
├── index.html
├── programs/
│   └── workshops.html
├── css/
│   └── styles.css
├── js/
│   └── main.js
└── README.md
