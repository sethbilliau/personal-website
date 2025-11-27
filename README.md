# Personal Website

A modern, responsive personal website built with HTML, CSS, and JavaScript. This is a static website that can be easily hosted on various platforms without requiring a content management system.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Fast Loading**: Lightweight static files for optimal performance
- **Easy to Customize**: Simple HTML/CSS/JS structure that's easy to modify
- **No Dependencies**: Pure vanilla JavaScript - no frameworks required

## Project Structure

```
personal-website/
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Customization

### Updating Content

1. **Personal Information**: Edit the content in `index.html`:
   - Update the hero section with your name and tagline
   - Modify the "About Me" section with your story
   - Add your actual projects in the "Projects" section
   - Update contact links (email, LinkedIn, GitHub) in the contact section

2. **Styling**: Customize colors and fonts in `styles.css`:
   - Modify CSS variables in the `:root` selector to change the color scheme
   - Adjust fonts by changing the Google Fonts import in `index.html`

3. **Functionality**: Add features in `script.js`:
   - The code is well-commented and easy to extend

### Adding Projects

To add a new project, copy one of the existing project cards in the projects section and update:
- Project title
- Project description
- Technology tags
- Project link URL

### Changing Colors

Edit the CSS variables at the top of `styles.css`:

```css
:root {
    --primary-color: #2563eb;    /* Main brand color */
    --primary-dark: #1e40af;      /* Darker shade for hover states */
    --secondary-color: #64748b;   /* Secondary text color */
    --text-color: #1e293b;        /* Main text color */
    --bg-color: #ffffff;          /* Background color */
    /* ... */
}
```

## Deployment Options

### Option 1: GitHub Pages (Free & Recommended)

1. Push your code to a GitHub repository
2. Go to repository Settings → Pages
3. Select the branch (usually `main`) and folder (`/root`)
4. Your site will be live at `https://yourusername.github.io/repository-name`
5. To use a custom domain, add a `CNAME` file with your domain name

### Option 2: Netlify (Free)

1. Sign up at [netlify.com](https://www.netlify.com)
2. Drag and drop your project folder, or connect your GitHub repository
3. Your site will be deployed automatically
4. Add your custom domain in the domain settings

### Option 3: Vercel (Free)

1. Sign up at [vercel.com](https://www.vercel.com)
2. Import your GitHub repository or upload your project
3. Deploy with one click
4. Add your custom domain in project settings

### Option 4: Traditional Web Hosting

Upload all files (`index.html`, `styles.css`, `script.js`) to your web hosting provider via FTP or their file manager.

## Domain Transfer from Wix

To transfer your domain (sethbilliau.com) from Wix:

1. **Unlock your domain** in Wix account settings
2. **Get the EPP/Authorization code** from Wix
3. **Choose a new registrar** (Namecheap, GoDaddy, Google Domains, etc.)
4. **Initiate the transfer** with your new registrar using the EPP code
5. **Update DNS settings** to point to your new hosting provider

**Note**: Domain transfers can take 5-7 days to complete.

## Local Development

To view the website locally:

1. Simply open `index.html` in your web browser
2. Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have it installed)
   npx serve
   ```
3. Open `http://localhost:8000` in your browser

## Browser Support

This website works on all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available for personal use.

## Support

If you need help customizing or deploying your website, feel free to:
- Check the code comments for guidance
- Modify the HTML/CSS/JS files to match your needs
- Refer to documentation for your chosen hosting platform

---

Built with ❤️ using vanilla HTML, CSS, and JavaScript
