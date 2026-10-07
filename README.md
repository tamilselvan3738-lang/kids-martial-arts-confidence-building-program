# Kids Martial Arts & Confidence Building Program - Navbar & Footer

A responsive navigation and footer system built with **3D tactile buttons**, **Framer Motion spring physics**, **Dark Mode**, and **Right-to-Left (RTL)** layout support.

---

## 🥋 Project Structure

```text
KIDS MARTIAL ARTS & CONFIDENCE BUILDING PROGRAM
│
├── assets/
│   ├── logo.svg              # Standalone high-res vector logo
│   └── logo-icon.svg         # Standalone martial arts shield & flying-kick emblem
│
├── navbar.html               # Floating island navbar + clean matching footer columns
│
└── README.md                 # Documentation & design specifications
```

---

## 🧭 Navbar Specifications

1. **Laptop View (`≥ 1024px`)**:
   * **Left**: Compact Scaled Logo (`28px` martial arts crest + athletic typography).
   * **Center (Contiguous Menu Flow)**:
     * **Home**: Hover reveals **only** `Home 1` and `Home 2`.
     * **About**
     * **Programs**: Direct single link (**no dropdown on hover**).
     * **Belt System**: Includes interactive rank color indicator.
     * **Instructors**
     * **Events**
     * **Safety** (with emerald shield icon).
     * **Contact**
     * **Dashboard**: Placed **immediately following Contact with no gap**; hover reveals **only** `Admin Dashboard` and `User Dashboard`.
   * **Right (Utility Controls)**:
     * **Prominent Gap**: Placed cleanly **after the Dashboard button**, separating it from the utility tools.
     * **Dark Mode Switch**: Tactile 3D button with 360° spring spin.
     * **RTL Switch**: Tactile 3D button displaying **only the right-left icon** with 3D 180° flip.
     * **3D Login Button**: Crimson tactile push button with mechanical depth.

2. **Mobile & Tablet View (`< 1024px`)**:
   * **Header Left**: Compact Logo.
   * **Header Right**: **Only the 3D Hamburger Button**.
   * **Drawer Header**: Features the **exact navbar logo** (martial arts shield emblem + brand typography).
   * **Inside Slide-Over Drawer**: All navigation links, dashboards, display preferences (Dark Mode & RTL), and the 3D Login button.

---

## 🦶 Clean Footer Content Columns (Based on Navbar)

* **Column 1: Brand & Mission**:
  * Scaled logo lockup and youth mission statement.
  * Trust badges (*Certified Safe Dojo*, *Black Belt Mentors*, *Bully-Proof Guarantee*).
  * 3D tactile social media buttons (*Instagram, Facebook, YouTube, TikTok, WhatsApp*).
* **Column 2: Navigation**:
  * Home 1 (Dojo Hero), Home 2 (Fun Ninjas), About, Programs, Belt System, Instructors.
* **Column 3: Academy & Safety**:
  * Dojo Safety Standards, Belt Graduations & Camps, Contact, Admin Portal, Student / Parent Portal.
* **Column 4: Dojo Location & Direct Contact**:
  * Physical address, phone hotline, operating hours, and 3D Member Portal login button.
