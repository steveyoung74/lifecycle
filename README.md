# Lifecycle Systems Website

Enterprise automation for independent wealth managers

## Website Overview

This is a professional static website for Lifecycle Systems, showcasing automation services for financial services firms.

### Pages Included:
- **index.html** - Homepage with value proposition, problem/solution, and case study highlight
- **services.html** - Detailed service offerings (Assessment & Full Implementation)
- **case-studies.html** - Full case study with measurable results
- **about.html** - Company background and founder expertise
- **contact.html** - Contact form and information
- **styles.css** - Professional styling with clean, trustworthy design

## Deploying to GitHub Pages

### Option 1: Quick Deploy (Recommended)

1. **Create a new GitHub repository**
   ```bash
   # In your terminal, navigate to where you want to create the repo
   git init lifecycle-systems-website
   cd lifecycle-systems-website
   ```

2. **Copy these files into your repository**
   - Copy all HTML files (index.html, services.html, about.html, case-studies.html, contact.html)
   - Copy styles.css
   - Copy this README.md

3. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit - Lifecycle Systems website"
   git remote add origin https://github.com/YOUR-USERNAME/lifecycle-systems-website.git
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click "Settings"
   - Scroll down to "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click "Save"
   - Your site will be live at: `https://YOUR-USERNAME.github.io/lifecycle-systems-website/`

### Option 2: Using GitHub Desktop

1. Create a new repository using GitHub Desktop
2. Copy all files into the repository folder
3. Commit the changes
4. Publish to GitHub
5. Enable GitHub Pages in repository settings (see step 4 above)

## Customization Needed

Before going live, you'll want to customize:

1. **Contact Information**
   - Update email address in contact.html (currently: hello@lifecyclesystems.co.uk)
   - Add phone number if desired
   - Update location if needed

2. **Form Handling**
   - The contact form currently has a demo handler
   - Replace with a real form service like:
     - Formspree (https://formspree.io)
     - Netlify Forms (if using Netlify instead of GitHub Pages)
     - EmailJS (https://www.emailjs.com)

3. **Analytics** (Optional)
   - Add Google Analytics tracking code if desired
   - Add in the `<head>` section of each HTML file

4. **Domain Name** (Optional)
   - Purchase a custom domain (e.g., lifecyclesystems.co.uk)
   - Configure in GitHub Pages settings

## File Structure

```
lifecycle-systems-website/
│
├── index.html              # Homepage
├── services.html           # Services page
├── case-studies.html       # Case studies page
├── about.html             # About page
├── contact.html           # Contact page
├── styles.css             # Main stylesheet
└── README.md              # This file
```

## Browser Compatibility

The website is built with modern, standard HTML5 and CSS3 and works on:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Key Features

- **Fully Responsive** - Works on desktop, tablet, and mobile
- **Fast Loading** - Static site with optimized CSS
- **Professional Design** - Clean, trustworthy aesthetic appropriate for financial services
- **SEO-Friendly** - Semantic HTML with proper meta tags
- **Easy to Maintain** - Simple HTML/CSS structure, no complex build process

## Future Enhancements

Consider adding:
- Blog section for thought leadership
- Client testimonials page
- Additional case studies as you complete projects
- Resources/downloads section
- Newsletter signup

## Support

For questions about deployment or customization:
- GitHub Pages documentation: https://docs.github.com/en/pages
- HTML/CSS reference: https://developer.mozilla.org/

## License

All content is proprietary to Lifecycle Systems.
