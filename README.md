# Amna Ghafoor - Personal Portfolio Website

A minimal, modern personal portfolio website inspired by Ali Abdaal's clean aesthetic. Built with pure HTML, CSS, and JavaScript.

## 🎨 Features

- **Minimal Design**: Soft pink and purple color scheme with rounded corners and smooth shadows
- **Fully Responsive**: Optimized for both desktop and mobile devices
- **Smooth Animations**: Fade-in effects on scroll and hover interactions
- **9 Project Showcase**: Interactive project cards with descriptions, tech stacks, and links
- **Contact Form**: Simple contact form with validation
- **No Dependencies**: Self-contained website with no external APIs

## 🚀 Quick Start

### Running Locally

The website is already configured to run on Replit. Simply click the "Run" button, and the website will be available at the provided URL.

If you want to run it locally on your machine:

1. Download all files (index.html, style.css, script.js)
2. Open a terminal in the project directory
3. Run a local server:
   ```bash
   # Python 3
   python3 -m http.server 5000
   
   # Python 2
   python -m SimpleHTTPServer 5000
   
   # Node.js
   npx http-server -p 5000
   ```
4. Open your browser and navigate to `http://localhost:5000`

### Files Structure

```
├── index.html          # Main HTML structure
├── style.css           # All styles and animations
├── script.js           # Interactive functionality
├── README.md           # This file
└── replit.md          # Project documentation
```

## 🎨 Color Palette

- **Light Pink Background**: `#FFF0F5`
- **Soft Section Background**: `#FCE4F3`
- **Light Purple Accent**: `#D8B4F8`
- **Dark Purple Text**: `#4B0082`

## 📱 Sections

1. **Navigation Bar**: Sticky navbar with smooth scrolling
2. **Hero Section**: Introduction with name, title, bio, and action buttons
3. **About Section**: Personal background and professional journey
4. **Projects Section**: 9 featured projects with interactive cards
5. **Skills Section**: Technical and soft skills in a responsive grid
6. **Contact Section**: Contact information and functional form
7. **Footer**: Copyright notice

## ✨ Customization

### Adding a New Project

Open `index.html` and add a new project card inside the `.projects-grid` div:

```html
<div class="project-card fade-in">
    <div class="project-icon">🎯</div>
    <h3 class="project-title">Your Project Title</h3>
    <p class="project-description">
        Your project description here.
    </p>
    <div class="project-tech">
        <span class="tech-tag">Technology 1</span>
        <span class="tech-tag">Technology 2</span>
    </div>
    <div class="project-links">
        <a href="your-github-url" target="_blank" class="project-link">GitHub</a>
        <a href="your-demo-url" target="_blank" class="project-link">Demo</a>
    </div>
</div>
```

### Updating Contact Information

Edit the contact details in `index.html` within the `#contact` section.

### Adding Your CV

To enable CV download:
1. Upload your CV file (e.g., `Amna_Ghafoor_CV.pdf`) to the project directory
2. Update the "Download CV" button in `index.html`:
   ```html
   <a href="Amna_Ghafoor_CV.pdf" download class="btn btn-secondary">Download CV</a>
   ```

### Changing Colors

Edit the CSS variables in `style.css`:

```css
:root {
    --color-bg-light: #FFF0F5;
    --color-bg-section: #FCE4F3;
    --color-accent: #D8B4F8;
    --color-text-dark: #4B0082;
}
```

## 🌐 Deployment

### Replit (Current)
The website is already deployed on Replit. Share your Replit URL with others.

### GitHub Pages
1. Create a GitHub repository
2. Upload all files
3. Go to Settings → Pages
4. Select main branch and root directory
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify
1. Sign up at [Netlify](https://www.netlify.com)
2. Drag and drop your project folder
3. Your site will be live instantly

### Vercel
1. Sign up at [Vercel](https://vercel.com)
2. Import your GitHub repository
3. Deploy with one click

## 📧 Contact

- **Email**: contact.amnaghafoor@gmail.com
- **LinkedIn**: [linkedin.com/in/amnaghafoor/](https://linkedin.com/in/amnaghafoor/)
- **Portfolio**: [amnaghafoor.carrd.co](https://amnaghafoor.carrd.co)
- **Location**: Faisalabad, Pakistan

## 📝 License

This project is open source and available for personal use.

---

© 2025 Amna Ghafoor
