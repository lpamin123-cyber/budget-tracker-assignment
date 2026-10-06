# Personal Budget Tracker - Visual Identity

A responsive visual interface for tracking personal expenses, created for the Week 3 Visual Identity CSS Assignment.

## 🎨 Visual Identity & Architecture

### 1. Intentional Color Palette (25%)
- **Primary Accent (`#0D9488` Deep Teal):** Used for primary section headers, action buttons, and table headers.
- **Background (`#F4F6F8` Light Gray):** Soft contrast background separating content sections.
- **Card Fill (`#FFFFFF` White):** Clean container background for readability.
- **Danger Action (`#EF4444` Soft Red):** Strictly reserved for destructive actions (Delete button).

### 2. Typography & Hierarchy (20%)
- **Headings:** Google Font **Poppins** (Bold, 600/700 weight) for sharp title hierarchy.
- **Body & Controls:** Google Font **Inter** (Regular/Medium) for readable text, form controls, and table data.

### 3. Form & Table Styling (30%)
- Form fields include internal padding, clear focus highlights, and unified layout gaps.
- The expense log table uses structured padding, highlighted header styling, border divisions, and `nth-child(even)` zebra striping.

### 4. CSS Box Model Strategy (25%)
- Utilizes explicit **margins** (`1.5rem`) to create distinct spacing between page areas.
- Applies consistent **padding** (`1.5rem`) inside each `.card` container.
- Defines **border-radius** (`8px`) for modern rounded edges on containers, inputs, and table headers.
