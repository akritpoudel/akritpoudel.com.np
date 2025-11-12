# Akrit Poudel - Professional Website

**Live Website:** https://akritpoudel.github.io/akritpoudel.com.np/

Professional website for Akrit Poudel, Licensed Aircraft Maintenance Engineer (B1.1) specializing in ATR 72-500 and ATR 42-320 aircraft at Buddha Air, Nepal.

## Features

- Clean, professional design with aviation theme
- Animated aircraft and runway effects
- Floating clouds animation
- Responsive mobile design
- Professional timeline for work experience
- Skills showcase with interactive cards
- Education and certifications section
- Contact information

## Local Development

To run the website locally:

```bash
cd akritpoudel.com.np
python3 -m http.server 8888
```

Then open your browser and navigate to: `http://localhost:8888`

## File Structure

```
akritpoudel.com.np/
├── index.html          # Main HTML file with complete CV content
├── styles.css          # CSS with aviation-themed animations
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## Deployment Options

### Option 1: GitHub Pages

1. Create a new repository on GitHub
2. Push this code to the repository:
   ```bash
   cd akritpoudel.com.np
   git init
   git add .
   git commit -m "Initial commit: Professional website for Akrit Poudel"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/akritpoudel.com.np.git
   git push -u origin main
   ```
3. Go to repository Settings > Pages
4. Select "main" branch as source
5. Your site will be live at: `https://YOUR_USERNAME.github.io/akritpoudel.com.np`

### Option 2: Netlify

1. Go to [Netlify](https://netlify.com)
2. Sign up or log in
3. Drag and drop the `akritpoudel.com.np` folder to Netlify
4. Your site will be live instantly with a Netlify URL
5. Configure custom domain `akritpoudel.com.np` in Domain settings

### Option 3: Vercel

1. Go to [Vercel](https://vercel.com)
2. Sign up or log in
3. Import the project (from GitHub or upload folder)
4. Deploy with one click
5. Configure custom domain `akritpoudel.com.np` in Project settings

### Option 4: Traditional Web Hosting

1. Get web hosting service with your domain `akritpoudel.com.np`
2. Upload all files via FTP/SFTP to the public_html or www folder
3. Ensure index.html is in the root directory
4. Your site will be accessible at `https://akritpoudel.com.np`

## Domain Configuration

To use the domain `akritpoudel.com.np`:

1. Purchase or register the domain from a registrar that supports .com.np domains
2. Configure DNS settings:
   - For GitHub Pages: Add A records pointing to GitHub's IPs
   - For Netlify/Vercel: Add CNAME record or follow their DNS setup guide
   - For traditional hosting: Point A record to your hosting server IP

## Customization

### Update Contact Information

Edit the email and add LinkedIn profile in [index.html](index.html#L281-L286):

```html
<a href="mailto:poudel.akrit@gmail.com" class="contact-link">
    <span>📧</span> poudel.akrit@gmail.com
</a>
<a href="YOUR_LINKEDIN_URL" class="contact-link">
    <span>💼</span> LinkedIn
</a>
```

### Update Colors

Modify the color scheme in [styles.css](styles.css#L7-L17):

```css
:root {
    --primary-color: #0c4a6e;      /* Main blue color */
    --secondary-color: #075985;     /* Darker blue */
    --accent-color: #0ea5e9;        /* Light blue accent */
    /* ... other colors */
}
```

### Add More Content

- Add more timeline items in the Experience section
- Add more skills cards
- Add certifications to the list
- Update the About section with more details

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Technologies Used

- HTML5
- CSS3 (with animations and flexbox/grid)
- Vanilla JavaScript (no frameworks)
- SVG for aircraft icon
- Responsive design principles

## License

© 2025 Akrit Poudel. All rights reserved.

## Contact

For updates or modifications to this website, contact:
- Email: poudel.akrit@gmail.com
