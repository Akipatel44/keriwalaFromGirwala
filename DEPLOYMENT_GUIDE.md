# GitHub Pages Deployment Checklist

## Pre-Deployment Checklist

### ✓ File Verification
- [x] index.html created
- [x] about.html created
- [x] products.html created
- [x] gallery.html created
- [x] contact.html created
- [x] styles.css created
- [x] script.js created
- [x] README.md created

### ✓ Content Verification
- [x] All pages have proper navigation
- [x] Contact information is accurate
- [x] Business location: Bagasara, Porbandar District, Gujarat
- [x] All links are working
- [x] Responsive design tested

## Step-by-Step Deployment Instructions

### **STEP 1: Prepare Your Files**
1. Make sure all files are in the folder: `c:\Users\ABCD\Downloads\Dhaval Website`
2. Files should include: index.html, about.html, products.html, gallery.html, contact.html, styles.css, script.js

### **STEP 2: Create GitHub Account**
1. Go to https://github.com/signup
2. Create free account
3. Verify your email
4. Complete profile setup

### **STEP 3: Create Repository**
1. After login, click "+" icon → "New repository"
2. Repository name: `keriwalagirwala` (or any name you like)
3. Description: "Premium Mango Farm Website - Bagasara, Gujarat"
4. Select "Public" (important for GitHub Pages)
5. Click "Create repository"

### **STEP 4: Upload Files to GitHub**
**EASY METHOD (No Git Command Line):**

1. Open your GitHub repository page
2. Click "Add file" → "Upload files"
3. Drag and drop all files from your website folder
4. Make sure `index.html` is at the root level
5. Add commit message: "Initial website upload"
6. Click "Commit changes"

**OR using Git Command Line:**

```bash
# Open PowerShell/Command Prompt
# Navigate to your website folder
cd "c:\Users\ABCD\Downloads\Dhaval Website"

# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Initial website commit"

# Add remote
git remote add origin https://github.com/YOUR_USERNAME/keriwalagirwala.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### **STEP 5: Enable GitHub Pages**
1. In your repository, go to "Settings" (top right)
2. Scroll down to "Pages" section (on the left menu)
3. Under "Source", select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click "Save"
5. Wait 1-2 minutes for deployment

### **STEP 6: Access Your Website**
Your website will be live at:
```
https://YOUR_USERNAME.github.io/keriwalagirwala
```

Example:
```
https://johndoe.github.io/keriwalagirwala
```

## Customization Before Deployment

### Edit Contact Information:
In `contact.html`, replace:
- `+91 98765 43210` → Your actual phone number
- `+91 98765 43211` → Your second phone number (if any)
- `info@keriwalagirwala.com` → Your email
- `orders@keriwalagirwala.com` → Your order email

### Edit Business Hours:
In `contact.html`, find:
```html
<h3>Business Hours</h3>
<p>Monday - Saturday: 8:00 AM - 6:00 PM</p>
<p>Sunday: 9:00 AM - 4:00 PM</p>
```
Update to your actual hours.

### Add Your Images:
1. Take photos of your mango farm and mangoes
2. Compress images (use online tool like compressor.io)
3. Save as: `farm1.jpg`, `mangoes.jpg`, etc.
4. Upload to GitHub with your files
5. In HTML, replace placeholder divs with: `<img src="mangoes.jpg" alt="Fresh Mangoes">`

## Testing After Deployment

✅ **Test These:**
1. All navigation links work
2. Website is mobile-responsive (test on phone)
3. Contact form opens email
4. All images load properly
5. Footers have correct info

## Updates After Deployment

To update content later:

1. Edit the HTML file locally
2. Save changes
3. Open GitHub, navigate to the file
4. Click "Edit" button (pencil icon)
5. Paste your updated code
6. Click "Commit changes"
7. Changes appear on your website in 1-2 minutes

OR use Git to update:
```bash
cd "c:\Users\ABCD\Downloads\Dhaval Website"
git add .
git commit -m "Update website content"
git push
```

## Custom Domain Setup (Optional)

If you want a domain like `www.keriwalagirwala.com`:

1. **Buy domain from:**
   - GoDaddy (~$10/year)
   - Namecheap (~$8/year)
   - Bluehost
   - Any domain registrar

2. **Point domain to GitHub:**
   - In domain registrar DNS settings, add:
     ```
     A Record: @ → 185.199.108.153
     A Record: @ → 185.199.109.153
     A Record: @ → 185.199.110.153
     A Record: @ → 185.199.111.153
     ```

3. **In GitHub Settings → Pages:**
   - Add custom domain: `www.keriwalagirwala.com`
   - Click Save

4. **Wait 24-48 hours** for DNS to propagate

## Troubleshooting

### Website not appearing?
- Wait 3-5 minutes after deployment
- Check repository Settings → Pages shows "Your site is published"
- Verify all files are uploaded to GitHub

### Images not showing?
- Make sure image files are uploaded to GitHub
- Use correct filename in HTML
- Images should be in same folder as HTML files

### Links not working?
- Check that filenames match exactly
- Ensure all HTML files are in root directory
- Verify relative paths are correct

### Contact form not working?
- Make sure contact.html is uploaded
- Clear browser cache
- Try different browser
- Verify email client is configured on computer

## Monthly Maintenance

- ✅ Update product availability based on season
- ✅ Change banner text for seasonal promotions
- ✅ Update contact information if needed
- ✅ Review and respond to contact form inquiries
- ✅ Add new farm/product photos

---

**Website Status:** ✅ Ready for GitHub Pages
**Technology:** HTML5 + CSS3 + JavaScript (100% GitHub Pages Compatible)
**Cost:** FREE (GitHub Pages is free)
**Maintenance:** Minimal (just update text as needed)

