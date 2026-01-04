# Marketing Portfolio - Miruna

A modern, responsive marketing portfolio website showcasing professional work, services, and expertise.

## Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI** - Clean and professional design with smooth animations
- **Sections Included**:
  - Hero section with call-to-action
  - About section with statistics
  - Services showcase
  - Portfolio/Projects section
  - Contact section
  - Sticky navigation

## Files

- `index.html` - Main HTML structure
- `styles.css` - All styling and responsive design
- `script.js` - JavaScript for interactivity and animations

## How to Use

### Quick Start
1. Open `index.html` in your web browser
2. The site will load with all features ready to use

### Customization

#### Update Personal Information
Edit `index.html`:
- Change "Miruna" in the navbar and footer to your name
- Update the hero section text with your headline
- Modify the about section description
- Update LinkedIn URL in contact section

#### Update Services
Edit the services section in `index.html`:
- Modify service titles and descriptions
- Change emoji icons as needed
- Add or remove service cards

#### Update Portfolio Projects
Edit the portfolio section in `index.html`:
- Update project titles and descriptions
- Replace placeholder images with actual project images
- Adjust grid layout if needed

#### Customize Colors
Edit `styles.css` CSS variables at the top:
```css
:root {
    --primary-color: #0066ff;      /* Main brand color */
    --secondary-color: #667eea;    /* Accent color */
    --dark-color: #1a1a1a;         /* Dark backgrounds */
    --light-color: #f5f5f5;        /* Light backgrounds */
    --text-color: #333;            /* Body text */
    --border-color: #e0e0e0;       /* Borders */
}
```

## Hosting Options

### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Push these files to the repository
3. Enable GitHub Pages in repository settings
4. Your site will be live at `https://yourusername.github.io/repo-name`

### Option 2: Netlify (Free with custom domain)
1. Sign up at netlify.com
2. Drag and drop this folder to deploy
3. Get a free subdomain or connect your custom domain

### Option 3: Vercel (Free)
1. Sign up at vercel.com
2. Import the repository
3. Site deploys automatically on each push

### Option 4: Local Web Server
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js with http-server
npm install -g http-server
http-server
```

Then visit `http://localhost:8000` in your browser.

## Adding Real Images

Replace the placeholder gradient boxes in the portfolio section:

```html
<!-- Instead of -->
<div class="portfolio-image">
    <div class="placeholder">Project 1</div>
</div>

<!-- Use -->
<div class="portfolio-image">
    <img src="path/to/your/image.jpg" alt="Project 1">
</div>
```

Add this CSS rule to `styles.css`:
```css
.portfolio-image img {
    width: 100%;
    height: 250px;
    object-fit: cover;
}
```

## SEO Optimization

Update in `index.html` `<head>`:
```html
<meta name="description" content="Your professional marketing portfolio description">
<meta name="keywords" content="marketing, strategy, digital, growth">
<meta name="author" content="Your Name">
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Tips for Success

1. **Add Case Studies** - Create detailed case study pages for each portfolio item
2. **Include Testimonials** - Add a testimonial section with client quotes
3. **Keep Content Updated** - Regularly update your portfolio with new work
4. **Professional Photos** - Use high-quality images and professional headshots
5. **SEO** - Add relevant keywords naturally throughout your content
6. **Analytics** - Add Google Analytics to track visitor engagement
7. **Mobile Testing** - Test on actual devices, not just browser dev tools

## Next Steps

1. Personalize all text content with your actual information
2. Add your professional photo or brand image
3. Upload portfolio project images
4. Update the LinkedIn and email links
5. Test on mobile devices
6. Deploy to your preferred hosting platform

---

**Note:** This portfolio template is fully customizable. Feel free to modify the structure, colors, and content to match your brand and style.
