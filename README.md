# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript.

## Features

- Responsive design that works on all screen sizes
- Dark/Light theme toggle with persistent storage
- Mobile-friendly navigation
- Project showcase section
- Contact form with validation
- Smooth scrolling and animations
- Back to top button

## Project Structure

```
portfolio-website/
├── assets/           # Images, icons, and other static files
├── css/             # Stylesheets
│   └── styles.css
├── js/              # JavaScript files
│   └── script.js
└── index.html       # Main HTML file
```

## Getting Started

1. Clone this repository
2. Open `index.html` in your web browser
3. Customize the content in `index.html` with your personal information
4. Modify the styles in `css/styles.css` to match your preferences
5. Add your own projects to the Projects section

## Customization

### Changing Colors

The color scheme can be customized by modifying the CSS variables in `css/styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    /* ... other color variables ... */
}
```

### Adding Projects

Add new projects by copying and modifying the existing project card structure in `index.html`:

```html
<div class="project-card">
    <h3>Project Name</h3>
    <p>Project description...</p>
    <div class="tech-stack">
        <span>Technology 1</span>
        <span>Technology 2</span>
    </div>
</div>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the MIT License.
