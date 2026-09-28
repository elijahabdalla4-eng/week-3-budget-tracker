# 💰 Budget Tracker - Visual Identity & Design

A clean, modern, and accessible interface design for a Personal Budget Tracker web application. This project focuses on enhancing user experience through intentional CSS styling, custom typography, color systems, and the CSS Box Model.

---

## 📌 Project Overview

The objective of this assignment was to transform an unstyled Budget Tracker HTML layout into a visually cohesive and professional user interface. All visual enhancements were achieved exclusively using standard CSS without altering the foundational structure or introducing complex JavaScript.

---

## 🎨 Visual Identity & Features

### 1. Intentional Color Palette
The application uses CSS Custom Properties (`:root`) to maintain visual harmony:
- **Primary Color (`#1b5e20`):** Forest Green applied to main headings, table headers, primary buttons, and focus outlines to represent finance and clarity.
- **Interactive State (`#144417`):** Darker green applied on button hover states for interactive visual feedback.
- **Page Background (`#f4f6f8`):** A soft, light gray background that minimizes contrast strain and elevates content cards.
- **Card Background (`#ffffff`):** Pure white container backgrounds for structured section distinction.
- **Text Hierarchy (`#1f2937` / `#6b7280`):** Charcoal dark gray for main body readability and medium gray for secondary labels.

---

### 2. Custom Typography
Google Fonts were integrated to build a clear hierarchy:
- **Headings Font:** `Poppins` (Semi-bold & Bold) — applied to `<h1>`, `<h2>`, and section headers for modern title presentation.
- **Body & Inputs Font:** `Inter` (Regular & Medium) — applied across all body text, input fields, labels, buttons, and table rows for high screen legibility.

---

### 3. Form & Table Styling
- **Add Expense Form:** Form controls feature consistent vertical padding, soft border-radius, explicit hover/focus outlines, and clear field labeling.
- **Expense Log Table:** Designed with a dark green uppercase header, explicit cell padding (`12px 16px`), horizontal row dividers, and zebra striping (`tbody tr:nth-child(even)`) for clear row tracking.
- **Buttons:** Styled with rounded corners, white text over dark green, centered padding, and smooth transition effects on hover.

---

### 4. CSS Box Model & Card Structure
The page layout uses the CSS Box Model (`margin`, `padding`, `border`, `border-radius`, and `box-shadow`) to organize the app into three visual **card containers**:
1. **Header Card:** Houses the page title and descriptive tagline.
2. **Form Card:** Contains the "Add New Expense" form inputs and submit button.
3. **Table Card:** Encloses the expense transaction table with responsive overflow handling.

---

## 📁 File Structure

```text
budget-tracker/
├── index.html        # Main HTML structure with Google Fonts link
├── style.css         # Complete stylesheet containing variables, box model rules, and component styles
└── README.md         # Documentation explaining design decisions and project features
