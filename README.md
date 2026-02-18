# DigiTech Transformation Website

**Developer:** Junaid Ul Haque Sheikh
**Contact:** +92 332 3605926 | +92 334 3046525
**Email:** junaidsheikh0002@gmail.com

## Live Deployment Links

- **Main Domain:** [https://digitechtransformation.com/](https://digitechtransformation.com/)
- **Vercel:** [https://digitechtransformation.vercel.app](https://digitechtransformation.vercel.app)
- **Netlify:** [https://digitechtransformation.netlify.app](https://digitechtransformation.netlify.app)
- **GitHub:** [https://github.com/junaidsheikh0002/junaidulhaquesheikh0001](https://github.com/junaidsheikh0002/junaidulhaquesheikh0001)

---

A modern, responsive e-commerce enabled website for DigiTech Transformation - Pakistan's leading digital skills institute.

## Features

- 🎨 **Modern UI/UX** - Beautiful gradient design with smooth animations
- 🛒 **E-commerce Functionality** - Full shopping cart with Add to Cart feature
- 📱 **Fully Responsive** - Works on all devices (desktop, tablet, mobile)
- 💬 **WhatsApp Integration** - Direct checkout and contact via WhatsApp
- 🎯 **Program Filtering** - Filter courses by category
- 📊 **Dynamic Statistics** - Animated counter for impact stats
- ✉️ **Contact Form** - Lead generation form
- 🧭 **Smooth Navigation** - Sticky navbar with smooth scrolling

## Products/Shop Section

The website includes a fully functional e-commerce section with:
- 6 Digital Products with images
- Product ratings and reviews
- Discounted pricing display
- Add to Cart functionality
- Shopping cart modal
- WhatsApp checkout integration

## Contact Information

- **Name:** Junaid Ul Haque Sheikh
- **WhatsApp:** +92 332 3605926 / +92 334 3046525
- **Email:** info@digitechtransformation.pk
- **Location:** Karachi, Sindh, Pakistan

## Quick Start

### Local Development

1. Simply open `index.html` in your browser, or
2. Use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (npx)
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. Visit `http://localhost:8000`

## Deployment Instructions

### Option 1: Deploy to Vercel

**URL:** https://digitechtransformation.vercel.app

#### Method A: Vercel Dashboard (Recommended)

1. Go to [vercel.com](https://vercel.com)
2. Sign up/Login with GitHub
3. Click "Add New Project"
4. Import your GitHub repository
5. Vercel will auto-detect the static site configuration
6. Click "Deploy"
7. Your site will be live at: `https://digitechtransformation.vercel.app`

#### Method B: Vercel CLI

```bash
# Install Vercel CLI
npm install -g vercel

# Navigate to project directory
cd D:\Digitech_Transformation_Websites_0001

# Deploy
vercel

# Follow the prompts:
# - Set up and deploy? Y
# - Which scope? (select your account)
# - Link to existing project? N
# - Project name? digitechtransformation
# - Directory? ./
# - Override settings? N

# Deploy to production
vercel --prod
```

#### Custom Domain on Vercel

1. Go to your project on Vercel Dashboard
2. Navigate to "Settings" > "Domains"
3. Add your domain: `digitechtransformation.com`
4. Update DNS records as instructed:
   - Type: `A` or `CNAME`
   - Name: `@` or `www`
   - Value: (provided by Vercel)

---

### Option 2: Deploy to Netlify

**URL:** https://digitechtransformation.netlify.app

#### Method A: Netlify Dashboard (Recommended)

1. Go to [netlify.com](https://netlify.com)
2. Sign up/Login with GitHub
3. Click "Add new site" > "Import an existing project"
4. Connect to GitHub and select your repository
5. Netlify will auto-detect the `netlify.toml` configuration
6. Click "Deploy site"
7. Your site will be live at: `https://digitechtransformation.netlify.app`

#### Method B: Netlify CLI

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Navigate to project directory
cd D:\Digitech_Transformation_Websites_0001

# Login to Netlify
netlify login

# Deploy
netlify deploy

# For production deployment
netlify deploy --prod
```

#### Method C: Drag & Drop (Simplest)

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop your project folder
3. Your site will be deployed instantly!

#### Custom Domain on Netlify

1. Go to your site on Netlify Dashboard
2. Navigate to "Domain settings"
3. Click "Add custom domain"
4. Enter: `digitechtransformation.com`
5. Update DNS records:
   - Type: `A`
   - Name: `@`
   - Value: `75.2.60.5` (Netlify's load balancer)
   - Type: `CNAME`
   - Name: `www`
   - Value: `digitechtransformation.netlify.app`

---

### Option 3: Deploy to GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings > Pages
3. Select source branch (main/master)
4. Your site will be live at: `https://yourusername.github.io/digitechtransformation`

---

### Option 4: Traditional Web Hosting

1. Upload all files to your web hosting via FTP/cPanel
2. Files to upload:
   - `index.html`
   - `styles.css` (if separate)
   - `script.js` (if separate)
   - `images/` folder
   - `vercel.json` or `netlify.toml` (not required but good practice)

## File Structure

```
Digitech_Transformation_Websites_0001/
├── index.html              # Main HTML file with all sections
├── styles.css              # External CSS (if needed)
├── script.js               # External JavaScript (if needed)
├── vercel.json             # Vercel deployment config
├── netlify.toml            # Netlify deployment config
├── README.md               # This file
└── images/
    ├── 635744251_...jpg    # Product images
    ├── 636098075_...jpg
    ├── 636669470_...jpg
    ├── 637417452_...jpg
    ├── 638035858_...jpg
    └── 635744251_... (1).jpg
```

## Website Sections

1. **Navigation** - Sticky header with cart icon
2. **Hero** - Main banner with CTA buttons
3. **About** - Mission, vision, and promise
4. **Programs** - Course listings with filter
5. **Shop** - E-commerce products section ⭐ NEW
6. **Incubation** - Business incubation timeline
7. **Why Choose Us** - Features and benefits
8. **Career Support** - Student support services
9. **Target Audience** - Who we serve
10. **Impact** - Statistics and testimonials
11. **Testimonials** - Success stories slider
12. **CTA** - Call to action section
13. **Contact** - Contact form and info
14. **Footer** - Links and contact details

## Shopping Cart Features ⭐ NEW

- Add products to cart
- View cart in slide-out modal
- Update quantities
- Remove items
- Real-time total calculation
- Checkout via WhatsApp with order details
- Cart count badge in navigation

## WhatsApp Integration

The website integrates with WhatsApp for:
- Quick contact via floating WhatsApp button
- Checkout orders directly through WhatsApp
- Pre-filled order messages with cart details

WhatsApp Numbers:
- Primary: +92 332 3605926
- Secondary: +92 334 3046525

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Poppins)

## Customization

### Update Products

Edit the product cards in `index.html` (search for `<!-- shop/e-commerce -->` section):

```html
<div class="product-card">
    <div class="product-image">
        <img src="images/your-image.jpg" alt="Product Name">
        <div class="product-overlay">
            <button class="btn btn-primary btn-sm add-to-cart" 
                    data-product="Product Name" 
                    data-price="99.99" 
                    data-image="images/your-image.jpg">
                <i class="fas fa-cart-plus"></i> Add to Cart
            </button>
        </div>
    </div>
    <!-- ... product info ... -->
</div>
```

### Update Contact Information

Search and replace in `index.html`:
- Phone numbers
- Email address
- Social media links

## Troubleshooting

### Images not loading?
- Check image paths are correct
- Ensure images are in the `images/` folder
- Check file names match exactly (case-sensitive on some servers)

### Cart not working?
- Ensure JavaScript is enabled
- Check browser console for errors
- Verify all IDs match in HTML and JavaScript

### Deployment issues?
- Check all files are uploaded
- Verify configuration files (`vercel.json`, `netlify.toml`)
- Check deployment logs on the platform

## License

© 2024 DigiTech Transformation. All rights reserved.

## Support

For questions or support, contact:
- WhatsApp: +92 332 3605926 / +92 334 3046525
- Email: info@digitechtransformation.pk

---

**Developed with ❤️ for DigiTech Transformation**
