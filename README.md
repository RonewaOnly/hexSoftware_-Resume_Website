# HTML Resume Website

A clean, responsive single-page resume website built with pure HTML and CSS. This project provides a professional way to showcase your skills, experience, and professional background on the web.

![Resume Website Preview](/api/placeholder/800/400)

## Features

- 🎯 **Single Page Design** - All important information accessible without page navigation
- 📱 **Fully Responsive** - Looks great on all devices (mobile, tablet, desktop)
- 🎨 **Modern Layout** - Clean and professional design
- ⚡ **No Dependencies** - Built with pure HTML and CSS
- 🔧 **Easy to Customize** - Well-structured code with clear comments

## Sections

1. **Header**
   - Professional headshot/avatar
   - Name and title
   - Clean, attention-grabbing design

2. **About Me**
   - Professional summary
   - Current role and expertise
   - Personal brand statement

3. **Skills**
   - Organized in a grid layout
   - Categorized by type (Programming Languages, Web Development, Tools)
   - Clean visual presentation

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/html-resume-website.git
```

2. Open `index.html` in your preferred browser to view the website.

3. Customize the content:
   - Replace the placeholder text in `index.html` with your information
   - Update the styles in the `<style>` section to match your preferred color scheme
   - Add your profile picture (recommended size: 200x200px)

## Customization

### Adding Your Profile Picture

Replace the placeholder in the header section:

```html
<div class="profile-img">
    <img src="path/to/your/photo.jpg" alt="Your Name">
</div>
```

### Changing Colors

The main colors can be customized in the CSS. Key color variables:

```css
header {
    background: #2c3e50; /* Main header background */
}

h1, h2 {
    color: #2c3e50; /* Heading colors */
}

.skill-category {
    background: #f8f9fa; /* Skills section background */
}
```

### Adding New Sections

To add a new section, follow this template:

```html
<section class="section" id="your-section-name">
    <h2>Section Title</h2>
    <div class="content">
        <!-- Your content here -->
    </div>
</section>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Best Practices

1. **Images**
   - Optimize images before uploading
   - Use appropriate alt text for accessibility
   - Maintain aspect ratio for profile picture

2. **Content**
   - Keep text concise and professional
   - Use bullet points for better readability
   - Update information regularly

3. **Performance**
   - Minimize inline CSS when possible
   - Optimize images for web
   - Keep code clean and well-commented

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Author

Your Name - [Your Website](https://yourwebsite.com)

## Acknowledgments

- Inspiration from modern resume designs
- Built with best practices in HTML5 and CSS3
- Focused on accessibility and responsiveness
