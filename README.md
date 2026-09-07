# Mawira Captures - Graphic Design Portfolio

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

✨ **Modern Design**
- Clean, minimalist aesthetic with gradient accents
- Smooth animations and transitions
- Fully responsive mobile-first design

🎨 **Sections**
- **Hero Section**: Eye-catching introduction with animated blobs
- **Work Portfolio**: Showcase your best projects in a grid layout
- **About Section**: Share your story and highlight your skills
- **Contact Form**: Allow clients to reach out directly
- **Navigation**: Sticky navbar with smooth scrolling

📱 **Responsive**
- Desktop, tablet, and mobile optimized
- Mobile hamburger menu
- Flexible grid layouts

⚡ **Performance**
- Fast-loading optimized CSS and JavaScript
- Smooth scroll animations
- Intersection observer for lazy loading effects

## Customization

### Update Your Information

1. **Personal Details**
   - Replace "MAWIRA" in the logo with your name
   - Update the hero title and subtitle
   - Replace placeholder images with your photos

2. **Featured Work**
   - Edit the work cards with your projects
   - Change the gradient colors for each card
   - Update titles and descriptions

3. **About Section**
   - Write your bio and story
   - Update skills tags to match your expertise
   - Add your photo to replace the placeholder

4. **Contact**
   - The form captures messages (frontend only)
   - To receive emails, connect to a backend service like Formspree, EmailJS, or Netlify Forms

5. **Social Links**
   - Update social media links in the footer

### Colors

Edit the CSS variables in `styles.css` to customize colors:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f5576c;
    --dark-bg: #0f0f1e;
    --light-bg: #f8f9fa;
    --text-dark: #1a1a2e;
    --text-light: #666;
}
```

## Deployment

### GitHub Pages (Free)
1. Push your code to GitHub
2. Go to Settings → Pages
3. Select `main` branch as source
4. Your site will be live at `https://yourusername.github.io/portfolio`

### Netlify (Free with custom domain option)
1. Connect your GitHub repo
2. Set build command: (leave empty)
3. Set publish directory: `/` (root)
4. Deploy!

### Other Hosting
- Vercel
- Firebase Hosting
- AWS Amplify
- Any static hosting service

## Email Form Setup

To enable email notifications for form submissions, choose one:

### Option 1: Formspree
1. Go to [formspree.io](https://formspree.io)
2. Sign up and create a new form
3. Update the form action in `index.html`:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" class="contact-form">
```

### Option 2: EmailJS
1. Sign up at [emailjs.com](https://emailjs.com)
2. Add the script to `index.html`:
```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/index.min.js"></script>
```
3. Update the form handling in `script.js`

## File Structure

```
portfolio/
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Tips for Success

1. **Quality Over Quantity**: Showcase your best 6-10 projects
2. **Tell Stories**: Use project descriptions to explain your process
3. **High-Quality Images**: Use high-res images of your work
4. **Keep It Fast**: Optimize images to ensure quick loading
5. **Mobile First**: Test on mobile devices before launching
6. **Call to Action**: Make it easy for clients to contact you
7. **SEO**: Add meta descriptions and alt text to images
8. **Analytics**: Consider adding Google Analytics to track visitors

## License

Free to use and modify for your portfolio.

## Need Help?

The code is fully commented and uses modern, readable JavaScript. Feel free to customize everything to match your style!

Good luck with your portfolio! 🚀