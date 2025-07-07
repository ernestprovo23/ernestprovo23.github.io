# Ernest Provo - Portfolio Website

A modern, responsive portfolio website showcasing my work as a Full Stack Developer and AI Engineer.

## 🚀 Features

- **Responsive Design**: Works seamlessly across desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth scrolling, animations, and hover effects
- **Project Showcase**: Highlights key projects with technology tags and links
- **Skills Visualization**: Organized display of technical skills and expertise
- **Performance Optimized**: Fast loading with clean, semantic HTML

## 🛠 Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: CSS Grid, Flexbox, CSS Animations
- **Icons**: Font Awesome
- **Deployment**: GitHub Pages

## 📁 Project Structure

```
portfolio/
├── index.html          # Main portfolio page
├── style.css           # Styles and responsive design
├── script.js           # Interactive functionality
└── README.md          # This file
```

## 🔧 Local Development

1. Clone this repository
2. Open `index.html` in your browser
3. Make changes to HTML, CSS, or JS files
4. Refresh browser to see updates

## 🌐 GitHub Pages Deployment

### Option 1: Deploy from this repository
1. Push this portfolio to a new GitHub repository
2. Go to repository Settings > Pages
3. Select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click Save
6. Your portfolio will be available at `https://yourusername.github.io/repository-name`

### Option 2: Deploy to username.github.io
1. Create a new repository named `yourusername.github.io`
2. Push these files to the main branch
3. Your portfolio will be available at `https://yourusername.github.io`

## 📝 Customization

### Adding New Projects
Edit the `projects-grid` section in `index.html`:

```html
<div class="project-card">
    <div class="project-header">
        <h3>Project Name</h3>
        <div class="project-links">
            <a href="github-link" class="project-link">
                <i class="fab fa-github"></i>
            </a>
        </div>
    </div>
    <p>Project description...</p>
    <div class="project-tech">
        <span class="tech-tag">Technology</span>
    </div>
</div>
```

### Updating Skills
Modify the `skills-grid` section in `index.html` to add new skills or categories.

### Changing Colors
Update the CSS color variables in `style.css`:
- Primary: `#3498db`
- Secondary: `#2c3e50`
- Accent: `#667eea`

## 🎨 Design Philosophy

- **Clean & Professional**: Minimalist design that highlights content
- **Accessible**: Semantic HTML and proper contrast ratios
- **Modern**: Contemporary design trends with subtle animations
- **Performance**: Optimized for fast loading and smooth interactions

## 📊 Analytics Integration

To add Google Analytics, include this in the `<head>` section:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🔗 GitHub Gists Integration

This portfolio is designed to work with GitHub Gists for code examples:

1. Create Gists for your code snippets
2. Embed them in project descriptions
3. Link to them from project cards

## 📱 Mobile Optimization

- Responsive grid layouts
- Touch-friendly navigation
- Optimized font sizes
- Mobile-first CSS approach

## 🚀 Performance Tips

1. **Images**: Optimize images before adding them
2. **CDN**: Font Awesome is loaded from CDN
3. **Minification**: Consider minifying CSS/JS for production
4. **Caching**: GitHub Pages provides automatic caching

## 🔧 Future Enhancements

- [ ] Add dark mode toggle
- [ ] Include project screenshots
- [ ] Add contact form
- [ ] Implement blog section
- [ ] Add more interactive animations

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio!