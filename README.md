# Full Stack Conf — Bootstrap 5 Challenge

> **A responsive, single-page conference website built entirely with Bootstrap 5.**

![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.3-7952B3?logo=bootstrap&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Design-green)
![CDN](https://img.shields.io/badge/Delivered-CDN-blue)

---

## Project Overview

**Full Stack Conf** is a fictional two-day technology conference website, meticulously crafted as a replica using **pure Bootstrap 5** without any custom CSS frameworks or external JavaScript libraries.

This project demonstrates mastery of Bootstrap's component system, grid layout, utility classes, and responsive design principles — delivering a polished, production-quality landing page for a web development conference held in **Kigali, Rwanda** on **March 12–13, 2027**.

The website features a fixed navigation bar with scroll spy, an eye-catching hero section, speaker profiles, a detailed conference schedule, an interactive registration modal, and a comprehensive footer — all fully responsive across mobile, tablet, and desktop viewports.

---

## Features

### Navigation
- **Fixed-top navbar** with dark theme and yellow accent branding
- **Scroll spy** functionality that highlights the active section as you scroll
- **Responsive hamburger menu** that collapses on smaller screens
- Smooth anchor links to Home, About, Speakers, and Schedule sections

### Hero Section
- **Bold yellow-themed header** with conference title and tagline
- Event date and location displayed as dark badges
- **Call-to-action buttons**: "Meet the Speakers" and "Register Now"
- The "Register Now" button triggers the registration modal

### About Section
- Conference description highlighting talks, workshops, and networking
- Feature list showcasing 20+ speakers, hands-on workshops, and career opportunities
- **Statistics cards** displaying key numbers: 2 days, 20+ speakers, 10 workshops, 500+ attendees

### Speakers Grid
- **Responsive 4-column grid** that adapts to screen size (1 column on mobile, 2 on tablet, 4 on desktop)
- Speaker cards with profile images, names, roles, and descriptions
- Four featured speakers:
  - **Benjamin Niyomurinzi** — Front-End Engineer
  - **Prince Ndahiro** — Back-End Developer
  - **Chris Nkingi Gakindi** — UX Designer
  - **Benjamin Kettey-Tagoe** — DevOps Engineer

### Conference Schedule
- **Two-day schedule** displayed in side-by-side cards
- Day 1 (March 12): Registration, Keynote, CSS Workshop, Lunch, API Session
- Day 2 (March 13): UX Design, Node.js, Lunch, DevOps Workshop, Closing Ceremony
- Time-based layout with clear session descriptions

### Registration Modal
- **Interactive modal form** with yellow header theme
- Early bird registration alert notification
- **Basic Info**: Name, email, and job role selection
- **Topic Preferences**: Checkboxes for JavaScript Frameworks, Libraries, Node.js, Build Tools, and ES2015
- **Payment Section**: Card number, zip code, CVV, and expiration date fields
- Form validation with required fields and HTML5 autocomplete attributes

### Footer
- Dark-themed footer with conference branding
- Quick navigation links to all major sections
- Contact information including location, date, and email
- Copyright notice and "Back to top" link

---

##  Tech Stack

| Technology | Version | Purpose |
|------------|---------|---------|
| **HTML5** | — | Semantic markup and structure |
| **Bootstrap 5** | 5.3.3 | CSS framework and JavaScript components |
| **Bootstrap Icons** | — | Delivered via CDN |
| **CDN (jsDelivr)** | — | Fast, global delivery of Bootstrap assets |

### Why Bootstrap 5?
- **No jQuery dependency** — pure vanilla JavaScript
- **Extensive utility classes** for rapid styling
- **Built-in responsive grid system**
- **Pre-built components** like modals, navbars, cards, and forms
- **Custom properties (CSS variables)** for easy theming

---

## Project Structure

```text
boostrap-challenge/
│
├── 📄 index.html              # Main single-page application
├── 📖 README.md               # This documentation file
├── 🎬 project-demo.webm       # Reference demo video
└── 📝 .gitignore              # Git ignore rules
```

### File Descriptions

| File | Description |
|------|-------------|
| `index.html` | The complete single-page application containing all sections, components, and the registration modal |
| `project-demo.webm` | The reference video demonstrating the target design to replicate |
| `.gitignore` | Excludes unnecessary files from version control |

---

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, or Safari)
- A code editor (VS Code, WebStorm, or similar) — optional for viewing
- Internet connection (required for Bootstrap CDN and image assets)

### Quick Start

1. **Clone the repository:**

```bash
git clone https://github.com/benjaminketteytagoe-alu/boostrap-challenge.git
cd boostrap-challenge
```

2. **Open the project:**

Simply open `index.html` in your web browser, or use a local development server:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js
npx serve

# Using PHP
php -S localhost:8000
```

3. **Visit the page:**

Navigate to `http://localhost:8000` in your browser to view the website.

---

## Bootstrap Components Used

This project leverages the following Bootstrap 5 components and utilities:

### Layout
- **Container** — Centers and constrains content width
- **Grid System** — Responsive row and column layouts (`row-cols-1`, `row-cols-sm-2`, `row-cols-lg-4`)
- **Spacing Utilities** — Padding and margin classes (`py-5`, `mb-4`, `g-4`)

### Navigation
- **Navbar** — Fixed-top responsive navigation bar
- **Navbar Toggler** — Hamburger menu for mobile views
- **Scroll Spy** — Automatic active link highlighting on scroll

### Content
- **Cards** — Speaker profiles, schedule days, and statistics
- **Badges** — Event date and location indicators
- **List Groups** — Schedule items with time and description

### Forms
- **Form Controls** — Text inputs, email fields
- **Form Select** — Dropdown menus for role and expiration date
- **Form Check** — Checkbox inputs for topic preferences
- **Input Groups** — Organized payment form layout

### Interactive
- **Modal** — Registration form popup with header, body, and form
- **Alert** — Dismissible early bird registration notice
- **Buttons** — Primary, dark, and outline variants

### Utilities
- **Display** — Large heading sizes (`display-3`, `display-6`)
- **Colors** — Background and text color utilities (`bg-dark`, `bg-warning`, `text-primary`)
- **Sizing** — Width and height utilities (`w-100`, `h-100`)
- **Flexbox** — Alignment and justification utilities
- **Shadows** — Card elevation effects (`shadow-sm`)
- **Typography** — Font weight, text transformation, and truncation

---

## Responsive Design

The website is fully responsive and adapts to three main breakpoints:

| Breakpoint | Screen Size | Layout |
|------------|-------------|--------|
| **Mobile** | < 576px | Single column, collapsed navbar, stacked schedule |
| **Tablet** | ≥ 768px | Two-column speaker grid, expanded navbar |
| **Desktop** | ≥ 992px | Four-column speaker grid, side-by-side schedule cards |

---

## Team

| Name |
|------|
| **Benjamin Niyomurinzi** |
| **Prince Ndahiro** |
| **Chris Nkingi Gakindi** |
| **Benjamin Kettey-Tagoe** |

---

## Challenge Requirements

✅ **Bootstrap 5 only** — No custom CSS frameworks or external JavaScript
✅ **CDN delivery** — Bootstrap loaded via jsDelivr CDN
✅ **Single HTML file** — All content in one `index.html` file
✅ **Responsive design** — Works on mobile, tablet, and desktop
✅ **Interactive components** — Modal, scroll spy, and responsive navbar
✅ **Replica accuracy** — Matches the design shown in `project-demo.webm`

---

## Links

- **Repository**: [GitHub Repository](https://github.com/benjaminketteytagoe-alu/boostrap-challenge)
- **Bootstrap 5 Docs**: [getbootstrap.com/docs/5.3](https://getbootstrap.com/docs/5.3)
- **Demo Video**: See `project-demo.webm` in the repository root

---

## License

This project is a learning challenge and is open for educational purposes.

---

## Acknowledgments

- **Bootstrap 5** — The incredible CSS framework that made this project possible
- **Paragraph** — The organization powering this challenge
- **Full Stack Conf** — The fictional conference that inspired this design

---
