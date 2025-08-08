# 📱 Task 4: Make a Website Mobile-Friendly Using CSS Media Queries

This task involves converting a desktop-only HTML page into a **responsive, mobile-friendly website** using **CSS media queries**.

---

## ✅ Objective

Transform the layout to work on smaller screens (like phones and tablets) by:
- Stacking columns vertically
- Scaling images properly
- Adjusting font sizes
- Making the nav menu mobile-friendly

---

## 🧰 Tools Used

- 🧠 HTML, CSS (Vanilla)
- 💻 Visual Studio Code (VS Code)
- 🌐 Chrome DevTools (Device Toolbar)

---

## 📁 Project Structure

ElevateLabs_Task1/
├── index.html
├── about.html
├── style.css
├── logo.png
└── README.md

yaml
Copy
Edit

---

## 🧩 Key CSS Changes

### ✅ Media Query Used
```css
@media (max-width: 768px) {
  /* Mobile-specific styles go here */
}
✅ Responsive Fixes Included
Reduced font sizes for smaller screens

Set flex-direction: column for layout containers

Made nav ul stack vertically

Ensured all img tags scale within their containers:

css
Copy
Edit
img {
  max-width: 100%;
  height: auto;
}
Fixed overflow issues by setting widths to 100%

🧪 How to Test Responsiveness
Open the project in VS Code

Right-click index.html → Open in browser

Open Chrome DevTools (Right-click → Inspect)

Toggle device toolbar (Cmd + Shift + M on Mac)

Choose a mobile device (e.g., iPhone SE, Pixel 5)

Observe how:

Layout stacks vertically

Navigation adjusts

Fonts and images scale

📌 Notes
All changes are done via media queries in style.css

No JavaScript or frameworks used

Site is now fully responsive for widths below 768px
