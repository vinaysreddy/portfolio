# Professional Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Features a dark/light theme toggle, smooth animations, and a fully responsive design.

## ✨ Features

- **Modern Design**: Clean, tech-focused aesthetic with dark/light theme support
- **Fully Responsive**: Mobile-first design that works on all devices
- **Smooth Animations**: Intersection Observer animations and smooth scrolling
- **Interactive Elements**: Theme toggle, scroll-to-top button, mobile navigation
- **Contact Form**: Validated contact form with real-time error messages
- **Skills Showcase**: Grid layout with technology logos and hover effects
- **Project Portfolio**: Showcase your projects with tech stack tags and links

## 🚀 Quick Start

1. **Clone or download** this repository
2. **Open** `index.html` in your web browser
3. **Customize** the content with your information

## 📝 Customization Guide

### Personal Information

1. **Hero Section** (`index.html`):
   - Update your name in the `.name` span
   - Change the role/title in `.hero-subtitle`
   - Modify the description in `.hero-description`

2. **Contact Information** (`index.html`):
   - Update email address in the contact section
   - Add your LinkedIn profile URL
   - Add your GitHub profile URL
   - Update social media links in the footer

3. **Projects** (`index.html`):
   - Replace placeholder projects with your actual projects
   - Update project titles, descriptions, and tech stacks
   - Add real GitHub repository links
   - Add live demo URLs (if available)

4. **Resume Download**:
   - Add your resume PDF file to the project folder
   - Update the resume button link in `script.js` (line ~200) or `index.html`

### Styling

- **Colors**: Modify CSS variables in `styles.css` (lines 3-30)
- **Fonts**: Change the Google Fonts import in `index.html` (line 11)
- **Accent Colors**: Update `--accent-primary` and `--accent-secondary` variables

### Skills

- Add or remove skills in the `.skills-grid` section
- Icons are from Font Awesome (already included via CDN)
- You can customize icons by changing the `<i>` class names

## 🌐 Deployment

### GitHub Pages

1. **Create a GitHub repository** (or use this one)
2. **Push your code** to the repository
3. **Go to Settings** → **Pages**
4. **Select source branch** (usually `main` or `master`)
5. **Select folder** (`/root`)
6. **Save** and wait for deployment
7. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify

1. **Sign up** for a free Netlify account
2. **Drag and drop** your project folder to Netlify
3. **Or connect** your GitHub repository for automatic deployments
4. Your site will be live instantly with a custom URL

### Vercel

1. **Sign up** for a free Vercel account
2. **Import** your GitHub repository
3. **Deploy** with default settings
4. Your site will be live with a custom URL

### Other Hosting Options

- **GitHub Pages**: Free, easy setup
- **Netlify**: Free tier, great for static sites
- **Vercel**: Free tier, excellent performance
- **AWS S3 + CloudFront**: For advanced users
- **Any web hosting service**: Upload files via FTP

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styles and themes
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## 🎨 Theme Customization

The website supports both dark and light themes. Users can toggle between them using the theme button in the navigation bar. The preference is saved in localStorage.

To customize colors:
- Edit CSS variables in `:root` and `[data-theme="light"]` selectors
- All colors are defined as CSS variables for easy customization

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern CSS with Flexbox, Grid, and CSS Variables
- **JavaScript (ES6+)**: Vanilla JavaScript, no frameworks
- **Font Awesome**: Icons for skills and social media
- **Google Fonts**: Inter font family

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🐛 Troubleshooting

### Form not submitting?
- The form currently shows a success message without actually sending emails
- To enable email sending, you'll need a backend service (e.g., Formspree, EmailJS, or your own API)

### Images not loading?
- Replace placeholder divs with actual `<img>` tags if you add project images
- Ensure image paths are correct

### Theme not persisting?
- Check browser localStorage support
- Clear browser cache if issues persist

## 📄 License

This project is open source and available under the MIT License. Feel free to use it for your own portfolio!

## 🤝 Contributing

Feel free to fork this project and customize it for your needs. If you make improvements, consider sharing them back!

## 📧 Support

If you have questions or need help customizing your portfolio, feel free to open an issue or reach out!

---

**Made with ❤️ for developers who want a beautiful portfolio**

