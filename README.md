# 🚀 Modern Interactive Portfolio

A premium, high-performance portfolio website built with modern web technologies. Featuring dynamic animations, a sleek dark mode aesthetic, and a fully functional contact form system.

![Portfolio Preview Showcase](https://atharvaachareresume.vercel.app/)

## ✨ Key Features

- **Dynamic Hero Section**: Interactive typewriter effect and fluid particle background.
- **Modern UI/UX**: Glassmorphism components, sleek dark mode, and vibrant amethyst/cyan gradients.
- **Interactive Animations**: 
  - Scroll-triggered reveal animations.
  - Animated skill bars with intersection observer logic.
  - Smooth parallax-style particle interactions.
  - Advanced micro-animations on buttons and social icons.
- **Comprehensive Sections**: 
  - **About Me**: Professional summary with key stats.
  - **Experience**: Clean vertical timeline for career history.
  - **Technical Proficiency**: Categorized skills with percentage bars.
  - **Portfolio**: Grid of projects with direct links to GitHub.
- **Email Integration**: Integrated with **EmailJS** for serverless, frontend-only email delivery.
- **Fully Responsive**: Optimized for Desktop, Tablet, and Mobile viewports.

## 🛠️ Tech Stack

- **Core**: HTML5, Vanilla JavaScript (ES6+).
- **Styling**: Vanilla CSS3, Tailwind CSS (via CDN).
- **Icons**: Google Material Symbols, Custom Brand SVGs.
- **Fonts**: Google Fonts (Inter, Outfit).
- **Email Service**: [EmailJS](https://www.emailjs.com/) (Serverless Integration).

## 📂 Project Structure

```text
├── index.html     # Main structural document
├── script.js      # Global logic (Animations, Intersection Observers, EmailJS)
├── styles.css     # Custom design system and utility classes
└── README.md      # Project documentation
```

## 🚀 Quick Start

1. **Clone the repository**:
   ```bash
   git clone https://github.com/atharvachare/portfolio.git
   ```
2. **Open the project**:
   Simply open `index.html` in any modern web browser.

## ✉️ EmailJS Configuration

To make the contact form active:

1. Create a free account at [EmailJS.com](https://www.emailjs.com/).
2. Set up your **Email Service** (e.g., Gmail) and **Email Template**.
3. In `script.js`:
   - Uncomment `emailjs.init("YOUR_PUBLIC_KEY")` and paste your key.
   - Replace `serviceID` and `templateID` with your actual IDs.

## 👤 Author

**Atharva Achare**
- GitHub: [@atharvachare](https://github.com/atharvachare)
- LinkedIn: [Atharva Achare](https://www.linkedin.com/in/atharvaachare/)
- Instagram: [@atharva_achare](https://www.instagram.com/atharva_achare/)

---
*Made with ❤️ by Atharva Achare*
