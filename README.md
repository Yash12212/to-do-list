# ✨ Enhanced Todo List ✨

A modern, feature-rich, and accessible Todo List application built entirely with pure **HTML, CSS, and JavaScript**. No frameworks, no build steps required!

---

## 🌟 Key Features

This isn't just a basic todo list! It packs a punch with modern features:

### Core Functionality
*   ✅ **Add Tasks:** Quickly add new items to your list.
*   ✏️ **Edit Tasks:** Double-click or press `Enter` on a task to modify it inline.
*   ✔️ **Complete Tasks:** Mark tasks as done with a satisfying custom checkbox.
*   🗑️ **Remove Tasks:** Delete individual tasks or clear all completed ones.

### Enhanced User Experience (UX)
*   🌓 **Light/Dark Theme:** Toggle between themes with a dedicated button. Your preference is saved!
*   💾 **Local Storage Persistence:** Your tasks stay saved in your browser even after closing the tab.
*   🎬 **Smooth Animations:** Subtle fade-in/down animations for adding tasks and collapsing animations for removal.
*   📣 **Toast Notifications:** Get instant, non-intrusive feedback for actions (add, complete, remove, edit, errors) via Toastify.js.
*   🎉 **Confetti Effects:** Celebrate completing tasks (individual & bulk clear) with a fun confetti burst via Canvas Confetti!
*   📊 **Task Filtering:** View "All", "Active", or "Completed" tasks easily.
*   🔢 **Live Task Count:** Always know how many active items are left.

### Quality & Accessibility
*   🎨 **Modern CSS:** Styled with CSS Variables (Custom Properties) for easy theming and maintenance, plus Flexbox and responsive design.
*   캡 **Encapsulated JS:** Code is neatly organized within an IIFE (Immediately Invoked Function Expression) to avoid global scope pollution.
*   🧩 **HTML Template Tag:** Efficiently creates new task elements using the `<template>` element.
*   ⚡ **Event Delegation:** Uses efficient event handling on the main task list.
*   ⌨️ **Keyboard Accessible:** Fully navigable and usable with a keyboard (Tabbing, Enter/Space for actions, Esc to cancel edits).
*   🗣️ **ARIA Support:** Implements ARIA attributes for improved screen reader compatibility.
*   👀 **Focus Management:** Clear `:focus-visible` styles and logical focus shifts during actions like editing.

---

## 🤔 Why internal css & js

This project was built intentionally without frameworks (like React, Vue, Angular) or complex build tools to:

1.  **Focus on Fundamentals:** Deepen understanding of core Web APIs (DOM, Local Storage, Events).
2.  **Demonstrate Proficiency:** Showcase strong foundational HTML, CSS, and JavaScript skills.
3.  **Simplicity:** Show that rich UIs can be built without heavy dependencies.
4.  **Performance:** Lightweight with minimal overhead.
5.  **No Build Required:** Runs directly in any modern browser just by opening the HTML file.

---

## 🚀 Getting Started

No complex setup needed!

1.  **Clone or Download:**
    ```bash
    # If you use git
    git clone https://github.com/Yash12212/to-do-list.git
    cd YOUR_REPOSITORY_NAME

    # Or simply download the index.html file
    ```
2.  **Open `index.html`:** Double-click the file in your file explorer, or use your browser's `File > Open` menu.

That's it! The app will run directly in your browser.

---

## 🛠️ Tech Stack & Key Concepts Demonstrated

*   **Frontend:** HTML5, CSS3, JavaScript (ES6+)
*   **Libraries (via CDN):**
    *   [Toastify.js](https://github.com/apvarun/toastify-js): User notifications.
    *   [Canvas Confetti](https://github.com/catdad/canvas-confetti): Celebration effects.
*   **Key JavaScript Concepts:**
    *   DOM Manipulation (CRUD operations on elements)
    *   Event Handling (Listeners, Delegation, `event.target`)
    *   Local Storage API (Saving & Retrieving data)
    *   Array Methods (`map`, `filter`, `findIndex`, `splice`, `forEach`)
    *   ES6+ Features (Arrow functions, `const`/`let`, Template Literals, Spread Syntax)
    *   Immediately Invoked Function Expressions (IIFE) for scope control
    *   Conditional Rendering (based on filters and task state)
    *   Working with `<template>` elements
    *   Basic State Management (in-memory array `tasks`)
    *   Error Handling (e.g., `try...catch` for Local Storage)
*   **Key CSS Concepts:**
    *   CSS Variables (Custom Properties) for Theming
    *   Flexbox for Layout
    *   Transitions & Animations (`@keyframes`)
    *   Responsive Design (`@media` queries)
    *   Pseudo-classes (`:hover`, `:focus-visible`, `:checked`, `:empty`)
    *   Attribute Selectors (`[data-...]`)
    *   Custom Checkbox Styling

---

## 🔮 Potential Future Improvements

*   [ ] Drag-and-drop task reordering.
*   [ ] Add due dates or priority levels.
*   [ ] Implement unit/integration testing (e.g., using Vitest or Jest with JSDOM).
*   [ ] Refactor to use ES Modules (would require a simple local server or build step).
*   [ ] More sophisticated filtering/searching.
*   [ ] Add subtasks.
*   [ ] Add user accounts (would require a backend).

---

## 🤝 Contributing

Feedback and contributions are welcome! If you find a bug or have a suggestion, please open an issue on the GitHub repository (if applicable).

---
