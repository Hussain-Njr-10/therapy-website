# Therapy Website – React Frontend Assignment

A clean, responsive single-page therapy website built using **React** and **plain CSS**, designed to match real-world mental health product requirements and align closely with the assignment content and structure.

---

## 🌐 Live Demo

- **Live Site:** https://YOUR-NETLIFY-LINK.netlify.app  
- **GitHub Repository:** https://github.com/YOUR-USERNAME/therapy-website  

---

## 📌 Project Overview

This project is a therapist landing page focused on clarity, trust, and usability.  
The website visually represents the same copy, tone, and structure used in the assignment form submission, ensuring strong alignment between **content strategy and frontend implementation**.

The goal was to build a calm, professional UI suitable for a mental health platform without relying on heavy UI or animation libraries.

---

## 🛠️ Tech Stack

- React (Vite)
- JavaScript (ES6+)
- HTML5
- CSS (single global `index.css`)
- Netlify (deployment)

**No Tailwind. No UI libraries. No animation libraries.**  
This was a deliberate choice to demonstrate strong frontend fundamentals.

---

## ✨ Features

- Full-screen hero section with primary CTA
- Sticky navigation bar on scroll
- Vertically stacked layout (Hero → About → Services → CTA)
- Smooth fade-in animations using `IntersectionObserver`
- Fully responsive design (mobile, tablet, desktop)
- Clean typography and spacing suitable for mental health products

---

## 🎯 Design & UX Decisions

- Used subtle animations to maintain a calm and non-distracting experience
- Chose `IntersectionObserver` over scroll listeners for better performance
- Kept a minimal color palette and generous spacing to improve readability
- Ensured all website copy matches the assignment answers exactly

---

## 🚀 Performance Considerations

- No continuous scroll event listeners
- Animations trigger only once when elements enter the viewport
- Minimal DOM manipulation
- CSS transitions limited to `opacity` and `transform` for smooth rendering

---

## 📱 Responsiveness

- Layout adapts cleanly across screen sizes
- Text scales down appropriately on mobile devices
- Services stack vertically on smaller screens
- Navigation simplifies for mobile view

---

## 📂 Project Structure

src/
 ├─ components/
 │   ├─ Navbar.jsx
 │   ├─ Hero.jsx
 │   ├─ About.jsx
 │   ├─ Services.jsx
 │   └─ CTA.jsx
 ├─ App.jsx
 ├─ main.jsx
 └─ index.css

---

## 📦 Deployment

The project is deployed using **Netlify** with continuous deployment from GitHub.

**Build settings:**
- Build command: `npm run build`
- Publish directory: `dist`

---

## 🧩 What This Project Demonstrates

- Strong React fundamentals
- Clean separation of concerns
- Attention to UX and performance
- Ability to convert written requirements into a real UI
- Practical, real-world frontend development approach

---

## 👤 Author

**Hussain Ahmad**  
Frontend Developer (React)  
CSE (AI & ML) Undergraduate
