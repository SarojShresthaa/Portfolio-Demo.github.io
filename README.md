# Modern Developer Portfolio Website

A beautiful, responsive developer portfolio website with a retro-tech aesthetic, built using HTML, CSS, JavaScript, and Bootstrap.

## 🚀 Features

- **Modern Design**: Clean, professional layout with retro-tech vibes
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth animations, hover effects, and transitions
- **Retro Terminal**: Animated terminal illustration in the hero section
- **Project Showcase**: Responsive grid layout for displaying projects
- **Skills Section**: Organized skills with icons and hover animations
- **Contact Form**: Functional contact form with validation
- **Smooth Scrolling**: Seamless navigation between sections
- **Loading Animation**: Professional loading screen
- **Particle Effects**: Subtle background animations

## 🎨 Design Features

- **Color Scheme**: Dark theme with cyan accents (#64ffda)
- **Typography**: JetBrains Mono for headings, Inter for body text
- **Animations**: CSS transitions and JavaScript-powered effects
- **Gradients**: Subtle gradients for visual appeal
- **Shadows**: Layered shadow system for depth
- **Icons**: Font Awesome icons throughout

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Setup Instructions

1. **Download/Clone** the files to your local machine
2. **Open** `index.html` in your web browser
3. **Customize** the content as needed (see customization guide below)
4. **Deploy** to your preferred hosting service

## ✏️ Customization Guide

### Personal Information

Update the following sections in `index.html`:

#### Hero Section
```html
<!-- Replace [Your Name] with your actual name -->
<span class="name">I'm [Your Name]</span>
<p class="hero-subtitle">Full-Stack Developer & Tech Enthusiast</p>
```

#### About Section
```html
<!-- Update the about text -->
<p class="about-text">
    I'm a passionate developer who loves creating meaningful digital experiences...
</p>

<!-- Update statistics -->
<div class="stat-item">
    <span class="stat-number">3+</span>
    <span class="stat-label">Years Experience</span>
</div>
```

#### Contact Information
```html
<!-- Update email and location -->
<p>your.email@example.com</p>
<p>Your City, Country</p>
```

### Projects

Replace the placeholder projects with your own:

```html
<div class="project-card">
    <div class="project-image">
        <!-- Replace with your project screenshot -->
        <img src="path/to/your/project-image.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3 class="project-title">Your Project Name</h3>
        <p class="project-description">Your project description...</p>
        <div class="project-tech">
            <span class="tech-badge">Technology 1</span>
            <span class="tech-badge">Technology 2</span>
        </div>
    </div>
</div>
```

### Skills

Update the skills section with your technologies:

```html
<div class="skill-item">
    <i class="fab fa-html5"></i>
    <span>HTML5</span>
</div>
```

### Social Links

Update the social media links:

```html
<!-- In the navigation -->
<a href="https://linkedin.com/in/yourprofile" class="nav-link">
    <i class="fab fa-linkedin"></i>
</a>

<!-- In the contact section -->
<a href="https://linkedin.com/in/yourprofile" class="social-link">
    <i class="fab fa-linkedin"></i>
</a>
```

### Colors and Styling

Customize the color scheme in `styles.css`:

```css
:root {
    --primary-color: #64ffda;      /* Main accent color */
    --background-color: #0a192f;   /* Background color */
    --surface-color: #112240;      /* Card/section backgrounds */
    --text-primary: #ccd6f6;       /* Primary text color */
    --text-secondary: #8892b0;     /* Secondary text color */
}
```

## 🎯 Key Sections

### 1. Hero Section
- Bold greeting and introduction
- Animated retro terminal
- Call-to-action buttons

### 2. About Section
- Personal bio and experience
- Statistics/achievements
- Code window illustration

### 3. Projects Section
- Responsive project cards
- Hover effects and overlays
- Technology badges

### 4. Skills Section
- Organized by category
- Interactive skill items
- Icon-based display

### 5. Contact Section
- Contact information
- Social media links
- Functional contact form

## 🔧 Technical Features

### JavaScript Functionality
- Smooth scrolling navigation
- Scroll-triggered animations
- Terminal typing effect
- Form validation and submission
- Interactive hover effects
- Loading screen management

### CSS Features
- CSS Grid and Flexbox layouts
- CSS Custom Properties (variables)
- Smooth transitions and animations
- Responsive design with media queries
- Modern CSS features (backdrop-filter, etc.)

### Bootstrap Integration
- Responsive grid system
- Navigation components
- Form styling
- Utility classes

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints for:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🚀 Deployment

### GitHub Pages
1. Create a new repository
2. Upload the files
3. Go to Settings > Pages
4. Select source branch and save

### Netlify
1. Drag and drop the folder to Netlify
2. Or connect your GitHub repository

### Vercel
1. Import your GitHub repository
2. Deploy automatically

## 📝 Customization Tips

1. **Images**: Replace placeholder images with your project screenshots
2. **Content**: Update all text content to reflect your experience
3. **Colors**: Modify the CSS variables to match your brand
4. **Fonts**: Change fonts by updating the Google Fonts link
5. **Icons**: Add or remove Font Awesome icons as needed

## 🤝 Contributing

Feel free to fork this project and customize it for your own use. If you make improvements, consider sharing them back!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [Bootstrap](https://getbootstrap.com/) for the responsive framework
- [Font Awesome](https://fontawesome.com/) for the icons
- [Google Fonts](https://fonts.google.com/) for the typography
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) for the monospace font

---

**Happy coding! 🚀**
