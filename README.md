# Portfolio Website - Resume & Bio-data

A simple, beginner-friendly multi-page website showcasing Resume and Bio-data information.

## Files Structure

```
Web_assign/
│
├── index.html          # Home page
├── resume.html         # Resume page with professional information
├── biodata.html        # Bio-data page with personal information
├── styles.css          # CSS styling file
├── script.js           # JavaScript/jQuery functionality
│
├── registration.html   # Online registration form
├── registration.css     # Registration form styling
├── registration.js     # Registration form JavaScript/jQuery
├── process_registration.php  # PHP file to process and display form data
│
└── README.md           # This file

```

## Features

- **Multiple Pages**: Home, Resume, and Bio-data pages
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Modern Styling**: Clean and professional CSS design
- **Interactive Elements**: jQuery-powered animations and effects
- **Easy Navigation**: Simple navigation menu between pages

## Technologies Used

- HTML5
- CSS3
- JavaScript
- jQuery 3.6.0 (loaded from CDN)

## How to Use

1. **Local Testing**:
   - Open `index.html` in a web browser
   - Navigate between pages using the menu

2. **Edit Content**:
   - Open any HTML file in a text editor
   - Replace placeholder information with your own details
   - Customize colors and styles in `styles.css`

## Hosting on Cloud Platforms

### Option 1: GitHub Pages (Free & Easy)

1. Create a GitHub account at [github.com](https://github.com)
2. Create a new repository (name it `portfolio-website` or similar)
3. Upload all files to the repository
4. Go to Settings → Pages
5. Select the main branch as source
6. Your site will be live at: `https://yourusername.github.io/repository-name/`

### Option 2: Netlify (Free)

1. Go to [netlify.com](https://www.netlify.com)
2. Sign up for a free account
3. Drag and drop your project folder onto Netlify
4. Your site will be live instantly with a custom URL

### Option 3: Vercel (Free)

1. Go to [vercel.com](https://vercel.com)
2. Sign up for a free account
3. Import your project (GitHub or upload)
4. Deploy with one click

### Option 4: Firebase Hosting (Free)

1. Install Firebase CLI: `npm install -g firebase-tools`
2. Login: `firebase login`
3. Initialize: `firebase init hosting`
4. Deploy: `firebase deploy`

## Customization Guide

### Changing Colors

Edit `styles.css` and look for color values:
- Primary color: `#667eea` (purple)
- Secondary color: `#2c3e50` (dark blue)
- Background: `#f4f4f4` (light gray)

### Adding Your Information

1. **Resume Page**: Edit `resume.html` and replace:
   - Name, contact information
   - Work experience
   - Education details
   - Skills and certifications

2. **Bio-data Page**: Edit `biodata.html` and replace:
   - Personal information table
   - Contact details
   - Educational background
   - Hobbies and interests

3. **Home Page**: Edit `index.html` and update:
   - Welcome message
   - Contact information
   - Any additional sections

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Notes

- This is a beginner-level project with simple, clean code
- No images are included as per requirements
- All styling is done with CSS
- jQuery is loaded from CDN (requires internet connection)

## Registration Form Application

### Overview
A complete online registration form application with form validation, data processing, and formatted display.

### Files
- **registration.html** - Registration form with all input fields
- **registration.css** - Styling for the registration form
- **registration.js** - JavaScript/jQuery for form validation and interactivity
- **process_registration.php** - PHP backend to process form submission and display results

### Features
- ✅ Complete registration form with validation
- ✅ Real-time form validation using JavaScript/jQuery
- ✅ PHP backend to process form data
- ✅ Beautiful formatted display of submitted information
- ✅ Responsive design for all devices
- ✅ Error handling and user feedback

### How to Test Locally

**For PHP Testing (requires PHP server):**

1. Install PHP on your computer (if not already installed)
2. Open terminal/command prompt in the project folder
3. Run: `php -S localhost:8000`
4. Open browser and go to: `http://localhost:8000/registration.html`

**Alternative - Using XAMPP/WAMP:**
1. Install XAMPP or WAMP
2. Copy project files to `htdocs` folder (XAMPP) or `www` folder (WAMP)
3. Start Apache server
4. Open: `http://localhost/Web_assign/registration.html`

### Form Fields
- First Name & Last Name
- Email Address
- Phone Number
- Date of Birth
- Gender
- Address
- City, State, Pincode
- Course/Program
- Interests (multiple selection)
- Terms and Conditions agreement

### Hosting with PHP Support

**Important:** The registration form requires PHP support. Use these hosting platforms:

#### Option 1: 000webhost (Free PHP Hosting)
1. Go to [000webhost.com](https://www.000webhost.com)
2. Sign up for free account
3. Upload all files via File Manager or FTP
4. Access your site at: `https://yourname.000webhostapp.com`

#### Option 2: InfinityFree (Free PHP Hosting)
1. Go to [infinityfree.net](https://www.infinityfree.net)
2. Create free account
3. Upload files via File Manager
4. Your site will be live instantly

#### Option 3: Heroku (Free with limitations)
1. Install Heroku CLI
2. Create `composer.json` file (for PHP)
3. Deploy using: `git push heroku main`

#### Option 4: GitHub Pages (HTML only - No PHP)
- GitHub Pages doesn't support PHP
- For PHP, use 000webhost, InfinityFree, or similar

### Testing Without PHP
If you want to test the form validation only (without PHP):
1. Open `registration.html` directly in browser
2. Form validation will work
3. Form submission will show browser error (expected - PHP needed)

## Support

For questions or issues, refer to:
- HTML/CSS documentation: [MDN Web Docs](https://developer.mozilla.org)
- jQuery documentation: [jQuery.com](https://jquery.com)
- PHP documentation: [PHP.net](https://www.php.net)

---

**Happy Coding!** 🚀

