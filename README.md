# Keriwala from Girwala - Mango Farm Website

Premium mangoes from Bagasara, Gujarat. This is a fully responsive website built with HTML5, CSS3, and JavaScript that works perfectly on GitHub Pages.

## Website Features

✅ **Modern, Responsive Design** - Works on all devices (desktop, tablet, mobile)  
✅ **5 Main Pages** - Home, About, Products, Gallery, Contact  
✅ **No Database Required** - Pure static site for GitHub Pages  
✅ **Fast Loading** - Optimized performance  
✅ **Professional Look** - Modern gradient design with smooth animations  
✅ **Mobile Menu** - Hamburger menu for smaller screens  
✅ **Contact Form** - Integrated email functionality  
✅ **SEO Friendly** - Proper meta tags and structure

## Pages Included

1. **Home (index.html)** - Introduction and key highlights
2. **About (about.html)** - Farm story, expertise, and values
3. **Products (products.html)** - Mango varieties and quality standards
4. **Gallery (gallery.html)** - Farm images and statistics
5. **Contact (contact.html)** - Contact information, form, and FAQs

## File Structure

```
Dhaval Website/
├── index.html          (Home page)
├── about.html          (About page)
├── products.html       (Products page)
├── gallery.html        (Gallery page)
├── contact.html        (Contact page)
├── styles.css          (All styling)
├── script.js           (JavaScript functionality)
├── README.md           (This file)
└── .gitignore          (Git ignore file)
```

## Customization Guide

### Edit Business Information

Replace these placeholders with your actual details:

**Contact Numbers:**
- In `contact.html`, replace `+91 98765 43210` with your phone number

**Email Addresses:**
- In `contact.html`, replace `info@keriwalagirwala.com` and `orders@keriwalagirwala.com`

**Location:**
- Already set to "Bagasara, Porbandar District, Gujarat"

**Business Hours:**
- Edit the business hours section in `contact.html`

**Social Media Links:**
- Update Facebook, Instagram, and WhatsApp links in footer of all pages

### Change Colors

Edit these CSS variables in `styles.css` (lines 8-15):
```css
--primary-color: #f59e0b;        /* Orange - Main color */
--secondary-color: #10b981;      /* Green - Accent */
--dark-color: #1f2937;           /* Dark gray - Text */
```

### Add Your Images

Replace placeholder images:
1. Add actual farm/mango images
2. Update gradient placeholders in gallery with real images
3. Update hero section background if needed

## How to Deploy on GitHub Pages

### Step 1: Create GitHub Account
1. Go to [github.com](https://github.com)
2. Sign up for a free account

### Step 2: Create New Repository
1. Click "New" repository button
2. Name it: `keriwalagirwala` (or any name)
3. Add description: "Keriwala from Girwala - Mango Farm Website"
4. Choose "Public"
5. Click "Create repository"

### Step 3: Upload Files
**Option A - Using GitHub Web Interface:**
1. In your new repository, click "Add file" → "Upload files"
2. Drag and drop all files from the website folder
3. Click "Commit changes"

**Option B - Using Git Command Line:**
```bash
# Navigate to website folder
cd "c:\Users\ABCD\Downloads\Dhaval Website"

# Initialize git repository
git init

# Add all files
git add .

# Commit changes
git commit -m "Initial website commit"

# Connect to GitHub repository
git remote add origin https://github.com/YOUR_USERNAME/keriwalagirwala.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages
1. Go to repository Settings
2. Scroll to "Pages" section
3. Under "Branch", select "main"
4. Click "Save"
5. Wait a few seconds for your site to deploy

### Step 5: Access Your Website
Your website will be available at:
- `https://YOUR_USERNAME.github.io/keriwalagirwala`

(Replace YOUR_USERNAME with your GitHub username)

## Domain Setup (Optional)

To use a custom domain like `www.keriwalagirwala.com`:

1. **Buy a domain** from registrars like:
   - GoDaddy
   - Namecheap
   - Bluehost

2. **Configure DNS Settings:**
   - In your domain registrar's DNS settings, add these records:
     - Type: A
     - Name: @
     - Value: 185.199.108.153
     - Type: A
     - Name: @
     - Value: 185.199.109.153
     - Type: A
     - Name: @
     - Value: 185.199.110.153
     - Type: A
     - Name: @
     - Value: 185.199.111.153

3. **Add Custom Domain to GitHub:**
   - Go to Repository Settings → Pages
   - Under "Custom domain", enter your domain
   - Save

4. **Wait for DNS propagation** (24-48 hours)

## Updating Website Content

### To update any page:
1. Edit the HTML file in VS Code
2. Save the file
3. Upload to GitHub (using Git or web interface)
4. Wait a few seconds for changes to appear

### Example: Change About Page
1. Open `about.html`
2. Find the text you want to change
3. Edit it
4. Save and upload to GitHub

## Contact Form Setup

The contact form works in two ways:

1. **Simple Email (Current Setup)**
   - Clicking "Send" opens user's default email client
   - User can review and send the message
   - No server needed

2. **Advanced Setup (Optional)**
   - Use services like Formspree, Basin, or Netlify Forms
   - Follow their documentation to integrate

## Performance Tips

✅ **Fast Loading:**
- Website is optimized for speed
- Uses modern CSS and minimal JavaScript
- No heavy frameworks or libraries

✅ **SEO Optimized:**
- Proper meta tags in all pages
- Semantic HTML structure
- Mobile-friendly design

## Mobile Optimization

The website is fully responsive:
- Desktop: Full layout with side-by-side content
- Tablet: Adjusted grid layouts
- Mobile: Single column layout with hamburger menu

Test on different devices:
- Open website on phone/tablet
- All content should be readable
- Menu should work properly

## Browser Compatibility

Works on:
✅ Chrome 90+
✅ Firefox 88+
✅ Safari 14+
✅ Edge 90+
✅ Mobile browsers

## Maintenance

### Regular Updates
- Update mango season dates as needed
- Add new product information
- Update contact details if they change

### Analytics (Optional)
Add Google Analytics to track visitors:
1. Create Google Analytics account
2. Get your Tracking ID
3. Add this to `<head>` of all pages:
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR_TRACKING_ID');
</script>
```

## Support & Help

For issues or questions:
1. Check if files are properly uploaded to GitHub
2. Clear browser cache and refresh
3. Test on different browser
4. Check GitHub deployment logs

## License

This website template is free to use for your mango farm business.

---

**Last Updated:** January 2026
**Status:** Ready for GitHub Pages Deployment
