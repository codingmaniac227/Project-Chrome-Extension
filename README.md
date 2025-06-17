
# 🔗 Leads Tracker Chrome Extension 🔗  
This Chrome extension is a sleek, user-friendly tool for saving and managing useful links (or “leads”). With a focus on speed and simplicity, users can manually input URLs or instantly save the current browser tab — all stored persistently in local storage for easy access.

---

## ✨ Features

### 📥 One-Click Link Saving  
- Instantly capture the current browser tab’s URL with a single button click.  
- Manually input and save any custom URL to your personal list.

### 🔁 Persistent Storage  
- All saved links are stored in the browser's `localStorage`, keeping them available even after closing the browser.

### ❌ Simple Management  
- Easily clear all saved leads with a double-click on the "Delete All" button.

---

## 🧱 Tech Stack

### HTML
- Semantic elements for structure and accessibility.  
- Organized layout with input fields, buttons, and list rendering.

### CSS
- Flexbox for clean and responsive layout alignment.  
- Custom styling with hover-ready buttons, accent color themes, and clear spacing.

### JavaScript
- DOM manipulation and dynamic rendering of list items.  
- Event handling for user interaction.  
- Integration with Chrome's Tabs API and LocalStorage.

### Chrome Extension API
- `manifest.json` setup (v3) with `tabs` permission to capture browser activity.  
- Indexed HTML popup with linked styles and script logic.

---

## 📁 File Overview

| File            | Purpose                                      |
|-----------------|----------------------------------------------|
| `index.html`    | Popup UI with input field, buttons, and list |
| `index.css`     | Styling for layout, spacing, colors          |
| `index.js`      | Core logic: DOM, storage, event handling     |
| `manifest.json` | Chrome Extension config (v3 format)          |

---

## 🚀 Future Enhancements

These enhancements are designed to evolve the project into a robust, scalable application:

### ✅ Frontend Enhancements
- Refactor into a modern **React** frontend with component-based rendering.
- Add **form validation**, custom alerts, and animation effects.

### 🔐 Authentication & Personalization
- Add user authentication with token-based login.
- Allow users to view and manage their own saved leads securely.

### ☁️ Backend Integration
- Build a **Node.js + Express** backend with a connected database.
- Replace `localStorage` with persistent server-side storage (e.g., MongoDB, PostgreSQL).

### 🔄 API Design & Scaling
- Implement a RESTful API for CRUD operations on leads.
- Add **rate limiting** and **caching** strategies for efficient scaling.

### 🧪 Testing & DevOps
- Add unit and integration testing with **Jest/Vitest**.
- Use **Docker** for containerization and deploy using **CI/CD pipelines** (Render, Netlify, GitHub Actions).

---

## 🪞 Reflection

This project is an exercise in combining functional JavaScript, browser APIs, and clean UI design to solve a practical problem. It lays the foundation for a future-ready, fullstack-capable app — capable of scaling into a personalized, persistent bookmarking system with user accounts, cloud sync, and more.
