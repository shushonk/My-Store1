# **Ultimate Mega Store - Complete E-commerce Solution** 🛍️

A fully functional, feature-rich e-commerce website built with pure HTML, CSS, and JavaScript. Deploy instantly on GitHub Pages!

![Store Preview](https://images.unsplash.com/photo-1441986300917-64674bd600d8?w=1200)

## ✨ **Live Demo**
[View Live Store](https://YOUR-USERNAME.github.io/mega-store)

## 📋 **Table of Contents**
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [Deployment to GitHub Pages](#-deployment-to-github-pages)
- [Project Structure](#-project-structure)
- [Usage Guide](#-usage-guide)
- [Customization](#-customization)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [License](#-license)

## 🚀 **Features**

### 🛍️ **Shopping Features**
- **30+ Products** with real product images
- **Product Categories** - Men's Fashion, Women's Fashion, Electronics, Footwear, Accessories, Sports, Home & Living, Toys, Books, Office Supplies
- **Advanced Filtering** - Filter by category, price range
- **Sorting Options** - Price (Low to High/High to Low), Name (A-Z/Z-A), Rating
- **Search Functionality** - Real-time product search
- **Product Badges** - Sale, Hot, Bestseller, New arrivals
- **Wishlist** - Save favorite items (persists in localStorage)
- **Shopping Cart** - Sidebar cart with quantity management
- **Product Details Modal** - Full product information with image gallery

### 💳 **Checkout Features**
- Real-time cart total calculation
- Tax calculation (10%)
- Shipping cost calculation
- Free shipping threshold ($50)
- Order summary
- Persistent cart using localStorage

### 🎨 **User Interface**
- **Hero Carousel** - Auto-playing promotional banners
- **Category Showcase** - Visual category cards with item counts
- **Customer Reviews** - Real customer testimonials
- **Newsletter Subscription** - Email capture
- **Features Section** - Free shipping, returns, secure payment
- **Responsive Design** - Works on all devices (mobile, tablet, desktop)
- **Toast Notifications** - User-friendly alerts
- **Loading Animations** - Smooth transitions and hover effects

### 🔧 **Technical Features**
- 100% Pure HTML, CSS, JavaScript (No frameworks)
- localStorage for data persistence
- Font Awesome icons (6.0.0)
- Google Fonts (Poppins)
- Mobile-first responsive design
- No external dependencies

## 💻 **Technologies Used**

- **HTML5** - Structure and content
- **CSS3** - Styling, animations, responsive design
- **JavaScript (ES6+)** - All functionality and interactions
- **Font Awesome** - Icons and visual elements
- **Google Fonts** - Typography
- **localStorage** - Client-side data persistence
- **Unsplash** - Product and hero images

## 📦 **Installation**

### Local Development

1. **Clone the repository**
```bash
git clone https://github.com/YOUR-USERNAME/mega-store.git
cd mega-store
```

2. **Open in browser**
```bash
# Simply open index.html in your browser
open index.html
# OR
start index.html  # Windows
# OR
xdg-open index.html  # Linux
```

3. **Start coding**
- Edit `index.html` to customize
- All code is in a single file for easy deployment

## 🌐 **Deployment to GitHub Pages**

### Step-by-Step Guide

#### **Step 1: Create GitHub Repository**
```bash
1. Go to https://github.com
2. Click the "+" icon (top right) → "New repository"
3. Repository name: "mega-store" (or your choice)
4. Description: "Complete e-commerce store"
5. Choose "Public"
6. Click "Create repository"
```

#### **Step 2: Upload Files**

**Option A: Direct Upload (Easiest)**
```bash
1. On your new repository page
2. Click "Add file" → "Upload files"
3. Drag and drop your index.html file
4. Scroll down and click "Commit changes"
```

**Option B: Using Git Commands**
```bash
# Initialize git repository
git init

# Add all files
git add index.html

# Commit changes
git commit -m "Initial commit: Add complete e-commerce store"

# Add remote repository
git remote add origin https://github.com/YOUR-USERNAME/mega-store.git

# Push to GitHub
git push -u origin main
```

#### **Step 3: Enable GitHub Pages**
```bash
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll to "Pages" section (left sidebar)
4. Under "Branch", select "main" (or "master")
5. Click "Save"
6. Wait 2-3 minutes for deployment
```

#### **Step 4: Your Store Is Live!**
```bash
Your site will be available at:
https://YOUR-USERNAME.github.io/mega-store/

Example: https://john123.github.io/mega-store/
```

### ✅ **Deployment Checklist**
- [ ] File is named `index.html`
- [ ] Repository is set to **Public**
- [ ] Selected correct branch in Pages settings
- [ ] Waited 2-3 minutes for deployment
- [ ] Tested the live URL

## 📁 **Project Structure**
```
mega-store/
│
├── index.html          # Complete store (all code in one file)
├── README.md           # This documentation
└── assets/            # (Optional) If you add images locally
    ├── images/
    └── icons/
```

## 📖 **Usage Guide**

### **Customer Features**
1. **Browsing Products**
   - Scroll through product grid
   - Use category cards to filter
   - Search for specific products
   - Sort by price, name, or rating

2. **Product Interaction**
   - Click "View" to see product details
   - View image gallery with thumbnails
   - Check colors, sizes, and stock
   - Read product descriptions

3. **Shopping Cart**
   - Click "Add to Cart" on any product
   - View cart by clicking cart icon
   - Adjust quantities in cart
   - See real-time total calculation
   - Proceed to checkout

4. **Wishlist**
   - Click heart icon to save items
   - View wishlist count
   - Items persist after page refresh

### **Admin/Developer Features**
1. **Adding Products**
   ```javascript
   // Add new product to products array
   {
     id: 33,
     name: "New Product",
     price: 49.99,
     originalPrice: 69.99,
     category: "Category Name",
     rating: 4.5,
     reviews: 100,
     stock: 50,
     sku: "PR-033",
     brand: "BrandName",
     colors: ["Red", "Blue"],
     sizes: ["S", "M", "L"],
     description: "Product description",
     images: ["image-url1", "image-url2"],
     badge: "New" // or "Sale", "Hot", "Bestseller"
   }
   ```

2. **Customizing Categories**
   ```javascript
   // Categories auto-populate from products
   // Add new category icons in getCategoryIcon()
   ```

3. **Styling Changes**
   - All CSS is in `<style>` section
   - Easy to modify colors, fonts, layouts

## 🎨 **Customization**

### **Change Colors**
```css
/* Primary Colors */
:root {
  --primary: #3498db;      /* Main blue */
  --secondary: #2c3e50;    /* Dark blue */
  --accent: #f1c40f;       /* Yellow */
  --success: #27ae60;      /* Green */
  --danger: #e74c3c;       /* Red */
}

/* Modify in <style> section */
header { background: linear-gradient(135deg, #2c3e50, #3498db); }
.btn-primary { background: #3498db; }
```

### **Change Products**
```javascript
// Edit products array in JavaScript section
const products = [
  { 
    id: 1,
    name: "Your Product",
    price: 29.99,
    // ... other properties
  },
  // Add more products
];
```

### **Add New Categories**
```javascript
// Categories are auto-generated
// Just add products with new category names
// Add icon mapping in getCategoryIcon()
function getCategoryIcon(category) {
  const icons = {
    "Your New Category": "fa-icon-name",
    // Add more mappings
  };
}
```

## 📸 **Screenshots**

| Section | Preview |
|---------|---------|
| **Homepage** | Hero carousel, category cards, products |
| **Product Grid** | Filter bar, product cards with badges |
| **Product Details** | Image gallery, full details, add to cart |
| **Shopping Cart** | Sidebar cart with totals |
| **Mobile View** | Fully responsive layout |

*(Add actual screenshots here)*

## 🤝 **Contributing**

Contributions are welcome! Here's how:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. **Push to branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

## 📝 **License**

This project is licensed under the MIT License - see below:

```
MIT License

Copyright (c) 2026 MegaStore

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 🙏 **Acknowledgments**

- Images from [Unsplash](https://unsplash.com)
- Icons from [Font Awesome](https://fontawesome.com)
- Fonts from [Google Fonts](https://fonts.google.com)
- Inspiration from modern e-commerce platforms

## 📧 **Contact**

- **Project Link**: [https://github.com/YOUR-USERNAME/mega-store](https://github.com/YOUR-USERNAME/mega-store)
- **Live Demo**: [https://YOUR-USERNAME.github.io/mega-store](https://YOUR-USERNAME.github.io/mega-store)
- **Report Issues**: [GitHub Issues](https://github.com/YOUR-USERNAME/mega-store/issues)

---

### ⭐ **Show your support**
Give a ⭐ if you like this project!

### 🚀 **Quick Deploy**
[![Deploy to GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-blue)](https://YOUR-USERNAME.github.io/mega-store)

---

**Made by Shashank V with ❤️ for the open-source community**
