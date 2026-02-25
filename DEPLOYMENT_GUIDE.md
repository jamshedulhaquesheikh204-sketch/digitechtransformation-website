# 🚀 DigiTech Transformation - Deployment Guide

## Website Information

**Owner:** Junaid Ul Haque Sheikh  
**Role:** Web Developer (Intern / Trainee)  
**Location:** Shaheed Makdhoom Bilawal Society, Near Safoora Chowrangi, Karachi, Pakistan

---

## 📞 Contact Information

### WhatsApp Numbers
- +92 335 9033554
- +92 334 3046525
- +92 332 3605926
- +92 332 0213589
- +92 337 2135310
- +92 336 8068664

### Email
- digitechtransformation@gmail.com

---

## 🌐 Social Media Links

- **Facebook:** https://www.facebook.com/profile.php?id=100064065330176
- **YouTube:** https://www.youtube.com/@JunaidUlHaqueSheikh-g3z
- **TikTok:** https://www.tiktok.com/@junaid.ul.haque.s65
- **Facebook Group:** https://www.facebook.com/groups/958910999994384
- **Fiverr Portfolio:**
  - https://www.fiverr.com/users/junaidsheikh000/portfolio/Njk5NmRmNDI4NzY1ZGMwMDAxOGRhYWIw
  - https://www.fiverr.com/users/junaidsheikh000/portfolio/Njk4Yzc5MzJiMTM4NzQwMDAxZWE0Nzk3
  - https://www.fiverr.com/users/junaidsheikh000/portfolio/Njk4Yzc3ODI0NGYwNDQwMDAxMDAxNzc4
  - https://www.fiverr.com/users/junaidsheikh000/portfolio/Njk5NmUyYjU3MjllODUwMDAxNGYxY2M1

---

## 🎯 Target Deployment URLs

1. **Custom Domain:** https://digitechtransformation.com
2. **Vercel:** https://digitechtransformation-junaid-ul-haque-sheikh-0001.vercel.app
3. **Netlify:** https://digitechtransformation-junaid-ul-haque-sheikh-0001.netlify.app
4. **GitHub:** https://github.com/junaidsheikh0002/junaidulhaquesheikh0001

---

## 📁 Project Files

All files are located in: `D:\Digitech_Transformation_Websites_0001\`

### Main Pages
- `index.html` - Homepage
- `about.html` - About Us
- `courses.html` - Courses Listing
- `incubation.html` - Incubation Program
- `counselling.html` - Counselling Services
- `digital-marketing-agency.html` - Digital Marketing Agency
- `csr.html` - Corporate Social Responsibility
- `careers.html` - Career Opportunities
- `programs.html` - Programs Details
- `gallery.html` - Photo Gallery
- `shop.html` - E-commerce Shop (with Add to Cart)
- `contact.html` - Contact Page

### Assets
- `style.css` - Main Stylesheet
- `script.js` - JavaScript Functions
- `images/` - All Images

---

## 🚀 Deployment Steps

### Option 1: Deploy to GitHub + Vercel (Recommended)

#### Step 1: Push to GitHub

1. **Open Command Prompt as Administrator**
   ```
   Click Start → Type "cmd" → Right-click → Run as Administrator
   ```

2. **Navigate to your project folder**
   ```bash
   cd D:\Digitech_Transformation_Websites_0001
   ```

3. **Initialize Git (if not already done)**
   ```bash
   git init
   ```

4. **Add all files**
   ```bash
   git add .
   ```

5. **Commit your changes**
   ```bash
   git commit -m "Initial commit - DigiTech Transformation Website"
   ```

6. **Add remote repository**
   ```bash
   git remote add origin https://github.com/junaidsheikh0002/junaidulhaquesheikh0001.git
   ```

7. **Push to GitHub**
   ```bash
   git branch -M main
   git push -u origin main
   ```

   **⚠️ If you get an authentication error:**
   - You'll need to create a Personal Access Token
   - Go to: https://github.com/settings/tokens
   - Create a new token with "repo" permissions
   - Use the token instead of your password when pushing

#### Step 2: Deploy to Vercel

1. **Go to Vercel**
   - Visit: https://vercel.com
   - Click "Sign Up" or "Login"
   - Login with your GitHub account

2. **Import Your Repository**
   - Click "Add New Project"
   - Select "Import Git Repository"
   - Find `junaidulhaquesheikh0001` in the list
   - Click "Import"

3. **Configure Project**
   - **Framework Preset:** Other
   - **Root Directory:** `./` (leave as default)
   - **Build Command:** (leave empty)
   - **Output Directory:** (leave empty)

4. **Deploy**
   - Click "Deploy"
   - Wait for deployment to complete (~1-2 minutes)

5. **Set Custom Domain**
   - Go to Project Settings → Domains
   - Add: `digitechtransformation.com`
   - Follow DNS configuration instructions
   - Update DNS records at your domain registrar:
     ```
     Type: A
     Name: @
     Value: 76.76.21.21
     ```

---

### Option 2: Deploy to Netlify

#### Method A: Drag & Drop (Easiest)

1. **Go to Netlify**
   - Visit: https://netlify.com
   - Sign up/Login

2. **Drag & Drop**
   - Go to "Sites" tab
   - Drag the entire folder `D:\Digitech_Transformation_Websites_0001`
   - Drop it on the Netlify page
   - Wait for upload to complete

3. **Configure Site Name**
   - Click "Site Settings"
   - Click "Change site name"
   - Enter: `digitechtransformation-junaid-ul-haque-sheikh-0001`

4. **Add Custom Domain**
   - Go to Domain Settings
   - Add: `digitechtransformation.com`
   - Update DNS records as instructed

#### Method B: Connect GitHub

1. **Login to Netlify** with GitHub

2. **Connect Repository**
   - Click "Add new site" → "Import an existing project"
   - Select "GitHub"
   - Authorize Netlify
   - Select your repository: `junaidulhaquesheikh0001`

3. **Deploy Settings**
   - **Branch:** main
   - **Build command:** (leave empty)
   - **Publish directory:** (leave empty)

4. **Deploy**
   - Click "Deploy site"

---

### Option 3: GitHub Pages

1. **Go to GitHub Repository**
   - https://github.com/junaidsheikh0002/junaidulhaquesheikh0001

2. **Enable GitHub Pages**
   - Click "Settings"
   - Click "Pages" in left sidebar
   - Under "Source", select "Deploy from a branch"
   - Branch: `main`
   - Folder: `/ (root)`
   - Click "Save"

3. **Get Your URL**
   - Your site will be live at:
   - `https://junaidshekh0002.github.io/junaidulhaquesheikh0001/`

---

## ✅ Pre-Deployment Checklist

- [ ] All HTML files are valid
- [ ] All images are in the `images/` folder
- [ ] CSS file (`style.css`) is linked correctly
- [ ] JavaScript file (`script.js`) is working
- [ ] All contact numbers are updated
- [ ] All social media links are correct
- [ ] Shop page has Add to Cart functionality
- [ ] Footer is consistent across all pages
- [ ] Mobile responsive design is working

---

## 🛒 E-commerce Features (Already Implemented)

Your `shop.html` includes:

✅ **Product Images** - All products have images  
✅ **Add to Cart** - Functional shopping cart  
✅ **Cart Counter** - Shows number of items  
✅ **Product Filters** - Filter by category  
✅ **Wishlist** - Save favorite products  
✅ **Checkout Button** - WhatsApp checkout integration  
✅ **Toast Notifications** - Add to cart confirmations  
✅ **Responsive Design** - Works on all devices  

---

## 📱 WhatsApp Integration

All WhatsApp links point to: `https://wa.me/923359033554`

The checkout button in shop.html sends cart details to WhatsApp.

---

## 🎨 Website Features

### Navigation (All Pages)
- Home
- Incubation
- Courses
- Counselling
- Digital Marketing Agency
- CSR
- Careers
- About Us
- Programs
- Gallery
- Shop
- Contact

### Footer (All Pages)
- Quick Links
- Programs List
- Contact Information (all 6 phone numbers)
- Social Media Links
- Office Hours: Mon-Sat 9AM - 8PM

### Special Features
- WhatsApp Float Button (all pages)
- Scroll to Top Button (all pages)
- Mobile Responsive Navigation
- Image Gallery (46+ images)
- E-commerce Shop with Cart

---

## 🔧 Troubleshooting

### Git Push Fails
```bash
# Try pulling first
git pull origin main

# Then push again
git push -u origin main
```

### Authentication Issues
- Create GitHub Personal Access Token
- Use token instead of password
- Token URL: https://github.com/settings/tokens

### Deployment Fails on Vercel/Netlify
- Check that `index.html` exists in root
- Verify all file paths are correct
- Check browser console for errors

---

## 📞 Need Help?

If you need assistance with deployment:

1. **Vercel Support:** https://vercel.com/support
2. **Netlify Support:** https://answers.netlify.com/
3. **GitHub Support:** https://support.github.com/

---

## 📄 License

© 2026 DigiTech Transformation. All Rights Reserved.

**Created by:** Junaid Ul Haque Sheikh  
**Position:** Web Developer (Intern / Trainee)

---

## 🌟 After Deployment

Once deployed, share your links:

1. **Vercel:** https://digitechtransformation-junaid-ul-haque-sheikh-0001.vercel.app
2. **Netlify:** https://digitechtransformation-junaid-ul-haque-sheikh-0001.netlify.app
3. **GitHub:** https://github.com/junaidshekh0002/junaidulhaquesheikh0001
4. **Custom Domain:** https://digitechtransformation.com

---

**Good luck with your deployment! 🚀**
