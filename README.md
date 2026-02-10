# 📱 TechHub - Premium Online Mobile Store

A sleek, elegant, and fully functional e-commerce website for an online mobile store built with HTML, CSS, and JavaScript. Features a modern UI with product filtering, shopping cart, and checkout functionality.

## ✨ Features

### User Interface
- **Modern Design** - Gradient backgrounds, smooth animations, and elegant styling
- **Responsive Layout** - Works seamlessly on desktop, tablet, and mobile devices
- **Interactive Navigation** - Sticky navbar with shopping cart indicator
- **Product Cards** - Beautiful cards with hover effects and badges

### Shopping Functionality
- **Browse Products** - 8 premium smartphones with detailed specifications
- **Filter System** - Filter by brand (Apple, Samsung, Google, OnePlus) and price range
- **Shopping Cart** - Add/remove items, real-time cart updates
- **Price Calculation** - Automatic subtotal, tax, and total calculation
- **Checkout** - Order confirmation with total amount

### Product Information
- Brand identification
- Detailed specifications
- Original and sale prices
- Product badges (New, Hot, Sale, etc.)
- Visual product representation

## 🎨 Design Features

- **Color Scheme** - Professional dark theme with accent colors
  - Primary: Navy Blue (#1a1a2e)
  - Secondary: Dark Blue (#16213e)
  - Highlight: Red (#e94560)

- **Animations**
  - Smooth transitions on hover
  - Card lift effects
  - Slide animations for modals
  - Loading animations

- **Responsive Design**
  - Mobile-first approach
  - Flexible grid layout
  - Touch-friendly buttons
  - Adaptive navigation

## 📲 How to Use

1. **Open the Website**
   - Simply open `index.html` in your web browser

2. **Browse Products**
   - Click "Shop Now" or "Shop" in the navigation
   - Scroll through available smartphones

3. **Filter Products**
   - Use the filter section to narrow by brand or price
   - Filters update products immediately

4. **Add to Cart**
   - Click "Add" button on any product
   - Item count updates in the navbar

5. **View Cart**
   - Click the shopping cart icon (🛒) in the navbar
   - See all items, prices, and totals

6. **Remove Items**
   - Click "Remove" button on any cart item
   - Cart updates automatically

7. **Checkout**
   - Click "Proceed to Checkout" button
   - Enter payment confirmation
   - Order is processed and cart clears

## 📦 Available Products

1. **iPhone 15 Pro Max** - $1,199
   - 12GB RAM | 256GB Storage | 48MP Camera

2. **Galaxy S24 Ultra** - $1,299
   - 12GB RAM | 512GB Storage | 200MP Camera

3. **Pixel 8 Pro** - $999
   - 12GB RAM | 256GB Storage | AI Magic Eraser

4. **OnePlus 12** - $799
   - 12GB RAM | 256GB Storage | Fast Charging

5. **iPhone 15** - $799
   - 6GB RAM | 128GB Storage | 48MP Camera

6. **Galaxy A54** - $449
   - 6GB RAM | 128GB Storage | 50MP Camera

7. **Pixel 8** - $799
   - 8GB RAM | 256GB Storage | Premium Design

8. **OnePlus 12R** - $459
   - 8GB RAM | 128GB Storage | 120Hz Display

## 💻 Technical Details

- **Language**: HTML5
- **Styling**: CSS3 (Embedded)
- **Interactivity**: Vanilla JavaScript (No external libraries)
- **Responsive**: CSS Grid and Flexbox

### File Structure
```
mobile-store/
├── index.html (Complete website with CSS and JavaScript)
└── README.md (This file)
```

## 🎯 Main Sections

1. **Navigation Bar** - Logo, menu links, shopping cart with counter
2. **Hero Section** - Welcome message with call-to-action button
3. **Filter Section** - Brand and price range filters
4. **Products Grid** - Responsive grid of product cards
5. **Shopping Cart Modal** - Pop-up cart with items and checkout
6. **Footer** - Contact info and company details

## 🚀 Quick Start

1. Download or clone this repository
2. Navigate to the `mobile-store` folder
3. Open `index.html` in your web browser
4. Start shopping!

No server or dependencies required - it's a pure frontend application!

## 🎨 Customization

### Add New Products
Edit the `products` array in the JavaScript section:
```javascript
const products = [
    {
        id: 9,
        brand: 'YourBrand',
        name: 'Product Name',
        specs: 'Specifications',
        price: 999,
        originalPrice: 1099,
        badge: 'Badge Text',
        image: '📱'
    }
];
```

### Change Colors
Modify CSS variables in the `:root` section:
```css
:root {
    --primary-color: #1a1a2e;
    --secondary-color: #16213e;
    --accent-color: #0f3460;
    --highlight-color: #e94560;
}
```

### Modify Tax Rate
Find and change the tax calculation (currently 10%):
```javascript
const tax = subtotal * 0.1;
```

## 📋 Browser Compatibility

- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)
- Mobile Browsers

## 📝 Notes

- All functionality is client-side (no backend required)
- Shopping cart data is stored in browser memory (clears on refresh)
- This is a demo/prototype - production version would need backend integration
- Tax is fixed at 10% (easily customizable)

## 🔒 Features for Production

To make this production-ready, you would need to add:
- Backend API for product data
- Database for inventory management
- User authentication
- Payment gateway integration
- Order persistence
- Email notifications
- User accounts and order history

## 📧 Support

For questions or customization requests, contact through the website footer.

---

**TechHub** - Your Premium Mobile Store | Built with ❤️ using HTML, CSS & JavaScript