# Harvey Wrigg - Software Developer Portfolio

A modern, responsive portfolio website showcasing software development skills and experience. Built with clean, accessible code and designed to demonstrate professional capabilities to potential employers.

## Overview

This portfolio website demonstrates my ability to create accessible, modern web applications with clean code and exceptional user experiences. The site itself serves as a practical example of my development capabilities, featuring responsive design, smooth animations, and professional presentation.

## Features

- **Modern Design**: Clean, professional layout with cybersecurity-inspired color scheme
- **Responsive Layout**: Fully optimized for desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth scrolling navigation, hover effects, and dynamic content
- **Professional Sections**: 
  - Hero section with animated introduction
  - About section with personal information and statistics
  - Skills showcase with visual progress indicators
  - Project portfolio with detailed descriptions
  - Experience timeline
  - Contact form with validation
- **Performance Optimized**: Fast loading times and efficient code structure
- **Accessible Design**: Clean HTML structure for better user experience

## Technical Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with CSS Grid and Flexbox
- **Fonts**: Inter font family from Google Fonts
- **Icons**: Font Awesome for consistent iconography
- **Animations**: CSS transitions and JavaScript-powered effects

## Local Development

To run the website locally:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Customization Guide

### Personal Information

Update the following sections in `index.html`:

#### Navigation & Header
```html
<div class="nav-logo">
    <i class="fas fa-shield-alt"></i>
    <span>Your Name</span>
</div>
```

#### Hero Section
```html
<h1 class="hero-title">
    Software Developer
</h1>
<p class="hero-subtitle">
    Creating accessible, modern web applications with clean code and exceptional user experiences.
</p>
```

#### About Section
```html
<p>
    I am a BSc (Hons) Cyber Security graduate with a passion for software development 
    and creating exceptional digital experiences. My technical background combines 
    cybersecurity knowledge with practical programming skills.
</p>
```

#### Profile Card
```html
<div class="profile-info">
    <h3>Your Name</h3>
    <p>Software Developer</p>
    <div class="profile-links">
        <a href="mailto:your.email@example.com" class="social-link">
            <i class="fas fa-envelope"></i>
        </a>
        <a href="tel:+1234567890" class="social-link">
            <i class="fas fa-phone"></i>
        </a>
        <a href="#" class="social-link">
            <i class="fab fa-linkedin"></i>
        </a>
    </div>
</div>
```

### Skills Section

Update your technical skills with appropriate percentages:

```html
<div class="skill-category">
    <h3><i class="fas fa-code"></i> Web Development</h3>
    <div class="skill-items">
        <div class="skill-item">
            <span>HTML5 & CSS3</span>
            <div class="skill-bar">
                <div class="skill-progress" style="width: 95%"></div>
            </div>
        </div>
        <!-- Add more skills -->
    </div>
</div>
```

### Projects Section

Replace with your actual projects:

```html
<div class="project-card">
    <div class="project-header">
        <i class="fas fa-palette"></i>
        <h3>Project Name</h3>
    </div>
    <p>
        Project description highlighting your technical skills and achievements.
    </p>
    <div class="project-tech">
        <span class="tech-tag">Technology Used</span>
    </div>
    <div class="project-links">
        <a href="#" class="project-link">
            <i class="fab fa-github"></i> Code
        </a>
        <a href="#" class="project-link">
            <i class="fas fa-external-link-alt"></i> Live Demo
        </a>
    </div>
</div>
```

### Experience Section

Update with your work experience and education:

```html
<div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
        <h3>Job Title</h3>
        <p class="timeline-company">Company Name</p>
        <p class="timeline-date">2020 - 2024</p>
        <ul>
            <li>Key responsibility or achievement</li>
            <li>Another significant contribution</li>
        </ul>
    </div>
</div>
```

### Contact Information

Update your contact details:

```html
<div class="contact-details">
    <div class="contact-item">
        <i class="fas fa-envelope"></i>
        <span>your.email@example.com</span>
    </div>
    <div class="contact-item">
        <i class="fas fa-phone"></i>
        <span>+44 1234 567890</span>
    </div>
    <div class="contact-item">
        <i class="fas fa-map-marker-alt"></i>
        <span>Your Location</span>
    </div>
</div>
```

## Styling Customization

### Color Scheme

The website uses CSS custom properties for easy customization. Update colors in `styles.css`:

```css
:root {
    --primary-color: #00ff88;
    --secondary-color: #0066ff;
    --accent-color: #ff0066;
    --bg-dark: #0a0a0a;
    --bg-darker: #050505;
    --bg-light: #1a1a1a;
    --text-primary: #ffffff;
    --text-secondary: #b0b0b0;
    --text-muted: #666666;
    --border-color: #333333;
}
```

### Fonts

To change fonts, update the Google Fonts link in `index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

And update the font-family in `styles.css`:

```css
body {
    font-family: 'YourFont', sans-serif;
}
```

## Technical Features

### JavaScript Functionality

- Smooth scrolling navigation
- Mobile menu toggle
- Scroll-triggered animations
- Form validation
- Interactive skill bars
- Typing animation for hero title
- Parallax effects
- Active navigation highlighting

### Performance Optimizations

- Efficient CSS animations
- Optimized assets
- Minimal JavaScript footprint
- Fast loading times

## Deployment

### GitHub Pages

1. Create a new repository on GitHub
2. Upload your files to the repository
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify

1. Drag and drop your project folder to Netlify
2. Your site will be deployed automatically
3. Customize your domain if needed

### Vercel

1. Connect your GitHub repository to Vercel
2. Deploy automatically on every push
3. Get a custom domain and SSL certificate

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── assets/             # Images and other assets (optional)
    ├── images/
    └── icons/
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## About This Portfolio

This portfolio website demonstrates my software development capabilities through practical implementation. The clean, professional design showcases my ability to create accessible, modern web applications that deliver exceptional user experiences.

My background in cybersecurity provides a unique perspective on secure coding practices and data protection, which I apply to all development projects. This portfolio serves as both a demonstration of my technical skills and a practical example of my development approach.

---

**Built with clean code and modern design principles**
