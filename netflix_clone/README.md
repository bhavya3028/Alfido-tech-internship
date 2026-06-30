# UI Clone Challenge: Netflix Homepage

## 📌 Goal
Clone the Netflix homepage UI to demonstrate proficiency in HTML, CSS, and responsive design. Focus on layout, styling, and user experience without relying on a backend.

## 🛠️ Tech Used
- HTML5 (Semantic structure)
- CSS3 (Flexbox, Grid, Animations, Gradients)
- Vanilla JavaScript (Smooth scrolling, navbar effects)
- SVG & CSS Gradients (for visual effects)

## ✨ Features
- **Navigation Bar** — Sticky navbar with smooth animation on scroll
- **Hero Section** — Large featured content area with CTA buttons
- **Carousel Sections** — Horizontal scrollable movie cards (Trending, Popular, Coming Soon)
- **Movie Cards** — Hover effects with overlay information
- **Responsive Layout** — Mobile-first design, works on all screen sizes
- **Footer** — Multi-column footer with organized links
- **Smooth Scrolling** — Navigation links scroll smoothly to sections
- **Custom Scrollbar** — Styled scrollbar for carousels

## 📂 Project Structure
```
netflix_clone/
│
├── index.html          # Single file with HTML, CSS, and JavaScript
├── README.md           # This file
└── screenshots/        # Place your screenshots here
    ├── desktop_home.png
    ├── hero_section.png
    ├── carousel_view.png
    └── mobile_view.png
```

## ▶️ How to Run
1. **Open the file** — Double-click `index.html` or right-click → "Open with Browser"
2. **Or serve locally**:
   ```
   python -m http.server 8000
   # Then open http://localhost:8000 in browser
   ```
3. **Test responsiveness** — Resize browser or open DevTools (F12) → Toggle device toolbar

## 🎨 Design Features
- **Color Scheme** — Dark theme (Netflix style) with red accents (#e50914)
- **Typography** — Clean, modern sans-serif fonts with proper hierarchy
- **Spacing** — Consistent padding and margins for visual balance
- **Shadows** — Subtle box-shadows for depth and hierarchy
- **Gradients** — Linear gradients for modern visual appeal
- **Animations** — Hover effects on cards and buttons
- **Media Queries** — Optimized for mobile (768px breakpoint)

## 🧠 Key Learning Concepts Demonstrated
- **CSS Flexbox** — Navbar, buttons, and sections layout
- **CSS Grid** — Footer multi-column layout
- **Responsive Design** — Mobile-first approach with media queries
- **CSS Animations** — Hover effects, scaling, transitions
- **Semantic HTML** — Proper structure with nav, footer, sections
- **CSS Gradients** — Background gradients and overlay effects
- **Smooth Scrolling** — JavaScript for smooth navigation
- **CSS Pseudo-classes** — :hover, ::-webkit-scrollbar for custom styling

## 📐 Responsive Breakpoints
- **Desktop** (1200px+) — Full layout with 4 columns in footer
- **Tablet** (768px - 1199px) — Adjusted spacing and navigation
- **Mobile** (< 768px) — Stacked layout, 2-column footer, hamburger-friendly

## 🚀 Potential Enhancements
- Add a working search bar with autocomplete
- Implement actual Netflix API (requires API key)
- Add modal popup when clicking a movie card
- Add video player functionality
- Implement user authentication
- Add profile management
- Create multiple pages (Browse, My List, Account, etc)
- Add user ratings and reviews
- Dark/Light mode toggle

