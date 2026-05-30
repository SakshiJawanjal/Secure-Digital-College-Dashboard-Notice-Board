# 🎓 Secure Digital College Dashboard & Notice Board

A modern, lightweight, single-file web application designed for campus display monitors, TVs, and tablets. It displays a dynamic daily class timetable and a live announcement board, restricted by an admin password lock to prevent unauthorized edits.

## 🚀 Key Features

- **Standardised Academic Timetable**: Formatted for a 10:00 AM to 05:00 PM schedule with built-in recess slot handlers.
- **Dynamic Daily Rotation**: Matrix layout pre-configured with distinct subjects varying on a daily basis (Mon-Fri).
- **Admin Authentication**: Secure toggle lock mechanism (`Password: admin123`) to switch between student-view and staff management console.
- **Inline Live Editing**: Admin users can click directly inside any timetable cell to update course profiles or room listings instantly.
- **Local State Retention**: Uses browser `localStorage` to permanently retain custom notice feeds and timetable variations through page updates and restarts without needing an external database setup.
- **TV/Monitor Optimized UI**: Crafted with a responsive dark-mode layout designed to minimize eye strain and screen burn-in during continuous operations.

## 🛠️ Built With

- **HTML5** (Structured semantic data matrix)
- **CSS3** (Responsive Grid blueprints & high-contrast dark theme presets)
- **JavaScript** (Vanilla DOM state handling & local browser memory allocation)

## 📦 Fast Installation

1. Clone or download this repository.
2. Save the code file as `index.html`.
3. Double-click the file to launch it instantly in any web browser (Chrome, Edge, Safari, Firefox)—**no server installation required.**
