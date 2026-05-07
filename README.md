# Cloud Portfolio Project

A modern, responsive portfolio website showcasing cloud infrastructure and development projects.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Navigation**: Smooth scrolling between sections
- **Modern Styling**: Gradient backgrounds and smooth animations
- **Project Showcase**: Display your cloud projects in an attractive card layout
- **Intersection Observer**: Animated project cards as they come into view

## File Structure

```
cloud-portfolio-project/
├── index.html      # Main HTML file
├── style.css       # Styling and responsive design
├── script.js       # JavaScript for interactivity
├── README.md       # This file
└── images/         # Directory for project images
```

## Usage

1. Clone the repository
2. Open `index.html` in your web browser
3. Customize the content with your own information
4. Add your project images to the `images/` folder

## Customization

### Update Personal Information
Edit the following sections in `index.html`:
- Hero section title and subtitle
- About section content
- Contact information

### Add Projects
Add new project cards in the `.project-grid` section:
```html
<div class="project-card">
    <h3>Your Project Title</h3>
    <p>Project description</p>
</div>
```

### Modify Colors
Update the gradient colors in `style.css`:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Gradients)
- Vanilla JavaScript (Intersection Observer API)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT License - feel free to use this project for personal or commercial purposes.

## Contact

For questions or feedback, please reach out through the contact section in the portfolio.
