ElectroShopX - E-commerce Website
# Project Overview
ElectroShopX is a modern, responsive e-commerce website specializing in electronics and gadgets. The website features a clean design with dark/light mode toggle, product categories, customer testimonials, and contact functionality.

# Live Demo
[Site:](https://mern-stack-preview.vercel.app/)

# Features
1. Responsive Design
Mobile-first approach with Tailwind CSS

Fully responsive across all device sizes

Hamburger menu for mobile navigation

2. Dark/Light Mode Toggle
Built-in dark mode using Tailwind CSS

Smooth theme switching with localStorage persistence

Consistent color scheme across both themes

3. Product Categories
Electronics Accessories (Headphones, Power Banks, Speakers, Smartwatches)

Computer & Accessories (Laptops, Webcams, Mouse, Keyboards)

Camera & Photography (DSLRs, Drones, Action Cameras, Tripods)

4. User Interface Elements
Sticky navigation header

Hero section with call-to-action buttons

Product cards with:

Discount badges

Star ratings

Price comparisons

Add to cart buttons

Customer testimonials section

Newsletter subscription form

Contact form with validation

5. Performance Optimizations
Optimized images (assumed from assets folder)

Minimal CSS with Tailwind utility classes

Fast loading times

# Technologies Used
Frontend
HTML5 - Semantic markup

Tailwind CSS - Utility-first CSS framework

Font Awesome - Icons library

JavaScript - Interactive functionality

Libraries & Tools
Tailwind CSS CDN

Font Awesome CDN

Custom JavaScript for dark mode toggle

# Project Structure
text
ElectroShopX/
│
├── index.html              # Main HTML file
├── assets/                 # Static assets
│   ├── images/            # Product images
│   │   ├── iphone-right.png
│   │   ├── headphone.jpeg
│   │   ├── powerbank.avif
│   │   └── ... (other product images)
│   └── user-images/       # Customer testimonial images
│
├── README.md              # This documentation file
└── (Future additions)
    ├── style.css         # Additional custom styles
    ├── script.js         # JavaScript functionality
    └── products.json     # Product data

# Design Features
Color Scheme
Primary: Black (#000000)

Secondary: Cyan (#00DDFF)

Accent Colors: Red, Blue, Green

Dark Mode: Slate color palette

# Typography
Font Family: Roboto (via Google Fonts)

Font Weights: Regular, Medium, Semibold, Bold

Hierarchy: Clear typographic scale using Tailwind's text sizes

# Components
Navigation Bar

Logo with brand name

Desktop navigation links

Mobile hamburger menu

Shopping cart icon

User profile icon

Dark mode toggle

Product Cards

Product image with overlay badges

Product title and description

Star rating system

Price with discount comparison

Add to cart button

Testimonial Cards

Customer profile images

Star ratings

Customer feedback text

# Installation & Setup
Local Development
Clone the repository

cd ElectroShopX
Open in browser

Simply open index.html in any modern web browser

No build process required as using CDNs

📱 Responsive Breakpoints
Mobile: < 640px

Tablet: 640px - 1024px

Desktop: > 1024px

# Future Enhancements
Phase 1 (Immediate)
Add shopping cart functionality

Implement product filtering

Add search functionality

Integrate payment gateway

Phase 2 (Short-term)
User authentication system

Product wishlist feature

Order tracking system

Customer reviews submission

Phase 3 (Long-term)
Admin dashboard

Inventory management


# Known Issues & Fixes
Fixed Issues
Sticky Navigation Overlap: Header was being overlapped by hero image when scrolling

Solution: Removed sticky positioning from hero image and increased header z-index

Current Limitations
Static product data (hardcoded in HTML)

No backend integration

Cart functionality not implemented

Form submissions not connected to backend
# Key Points
HTML/CSS
Semantic HTML5 structure

Tailwind CSS utility classes

Responsive grid layouts

Flexbox for alignment

Dark mode implementation

CSS transitions and transforms

Best Practices Implemented
Mobile-first responsive design

Accessibility considerations

Performance optimization

Clean, maintainable code structure

Consistent naming conventions

# Author
ElectroShopX Development Team

Website: [Site](https://nimeshshrestha.com.np/)

Email: electroshopx@gmail.com

Location: Sundhara, Lalitpur

# Acknowledgments
Tailwind CSS for the amazing utility framework
Font Awesome for icons
Google Fonts for typography


