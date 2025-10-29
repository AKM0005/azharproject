# EarthwormX Website

A modern, eco-friendly website for EarthwormX - specialists in Miyawaki forests, land restoration, and sustainable farming solutions.

## 🌱 Features

- **Responsive Design**: Fully mobile-optimized with hamburger navigation
- **SEO Optimized**: Complete meta tags for social media sharing (Open Graph, Twitter Cards)
- **Accessible**: WCAG-compliant with proper ARIA labels and alt text
- **Performance**: Lazy loading images, smooth scrolling, and optimized assets
- **Contact Form**: Integrated with Formspree for easy message handling
- **Social Media Integration**: Links to Instagram, Facebook, LinkedIn, and Twitter
- **Dark Mode Ready**: Theme colors configured for light/dark modes

## 📋 Setup Instructions

### 1. Contact Form Setup

The contact form uses [Formspree](https://formspree.io/) for handling submissions.

**Steps:**
1. Go to [formspree.io](https://formspree.io/) and create a free account
2. Create a new form project
3. Copy your form endpoint (looks like `https://formspree.io/f/YOUR_FORM_ID`)
4. In `index.html`, find line ~347 and replace `YOUR_FORM_ID` with your actual Formspree ID:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" ...>
   ```

### 2. Update Contact Information

Replace placeholder contact details with your actual information:

**In both `index.html` and `about.html` footers:**
- Email: Replace `info@earthwormx.com` with your email
- Phone: Replace `+1 (234) 567-890` with your phone number

### 3. Update Social Media Links

Update social media URLs in both `index.html` and `about.html` footers:
- Instagram: `https://instagram.com/earthwormx` → your Instagram URL
- Facebook: `https://facebook.com/earthwormx` → your Facebook page
- LinkedIn: `https://linkedin.com/company/earthwormx` → your LinkedIn company page
- Twitter: `https://twitter.com/earthwormx` → your Twitter handle

### 4. Update Domain and Canonical URLs

In both `index.html` and `about.html`, update:
```html
<link rel="canonical" href="https://www.earthwormx.com/"/>
```
Replace `www.earthwormx.com` with your actual domain.

### 5. Customize Images (Optional)

The hero slider currently uses placeholder images. To use your own:
1. Host your images (recommended: use a CDN or image hosting service)
2. Replace the image URLs in `index.html` around lines 154-156
3. Update the `og:image` and `twitter:image` meta tags with your preferred social share image

## 🚀 Deployment

### Option 1: Static Hosting (Recommended)

Deploy to services like:
- **Netlify**: Drag and drop your folder to netlify.com/drop
- **Vercel**: Connect your GitHub repo for automatic deployments
- **GitHub Pages**: Push to a repo and enable GitHub Pages
- **Cloudflare Pages**: Fast global CDN hosting

### Option 2: Traditional Web Hosting

1. Upload all files to your web host via FTP/SFTP
2. Ensure `index.html` is in the root directory
3. Configure your domain to point to your hosting

## 📱 Mobile Navigation

The website includes a hamburger menu that automatically appears on mobile devices (screens < 768px). No additional configuration needed.

## 🎨 Customization

### Colors

The website uses a nature-inspired color palette defined in the Tailwind config:
- Primary Green: `#4B5320`
- Background Light: `#FDFBF5`
- Background Dark: `#2A3F31`
- Card Light: `#EAE0D5`
- Accent Mud: `#8B7D6B`

To change colors, update the Tailwind config in both HTML files (around line 15-30).

### Fonts

Currently using:
- Display: Playfair Display (serif)
- Body: Kalam (handwritten/cursive)

To change fonts, update the Google Fonts link and Tailwind config.

## ✅ Features Implemented

- ✅ Mobile-responsive hamburger navigation
- ✅ Working contact form with Formspree integration
- ✅ Complete SEO meta tags (title, description, keywords, OG, Twitter)
- ✅ Improved accessibility (ARIA labels, better alt text, proper semantic HTML)
- ✅ Social media links in footer
- ✅ Smooth scrolling navigation
- ✅ Hero image slider with auto-rotate
- ✅ Lazy loading for images
- ✅ Form validation and submission feedback
- ✅ Mobile touch target optimization (44px minimum)
- ✅ FAQ sections with accordion functionality
- ✅ Impact metrics showcase
- ✅ Services overview with detailed descriptions
- ✅ Process visualization

## 📞 Support

For questions about implementation or customization, refer to:
- Tailwind CSS docs: https://tailwindcss.com/docs
- Formspree docs: https://help.formspree.io/
- Web.dev best practices: https://web.dev/

## 🌍 Browser Support

- Chrome (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Edge (latest 2 versions)
- Mobile Safari (iOS 12+)
- Chrome Mobile (Android 8+)

---

**Built with ❤️ for a greener planet 🌱**

