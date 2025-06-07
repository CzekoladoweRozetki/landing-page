# Red Fox Digital - Professional E-commerce Platform Website

A modern, bilingual website for Red Fox Digital, showcasing next-generation e-commerce platform solutions. Built with DaisyUI, Tailwind CSS, and Alpine.js.

## 🚀 Features

### ✨ Design & UI
- **Modern Professional Design** - Clean, corporate aesthetic with company branding
- **Responsive Layout** - Optimized for desktop, tablet, and mobile devices
- **Custom Color Scheme** - Brand colors derived from company logo (#c9261e)
- **Smooth Animations** - Engaging hover effects and transitions
- **Dynamic Hero Graphics** - Animated rocket shopping cart with advanced floating animation

### 🌍 Internationalization
- **Bilingual Support** - Polish (default) and English translations
- **Dynamic Language Switching** - Seamless language toggle with state persistence
- **Localized Content** - All sections fully translated including navigation

### 📱 Navigation & UX
- **Fixed Navigation** - Always accessible header with company logo
- **Mobile-Optimized Menu** - Hamburger menu with proper touch interactions
- **Multiple Contact Points** - Navbar CTA, floating button, hero section, and dedicated contact section
- **Smooth Scrolling** - Enhanced page navigation between sections

### 🏢 Content Sections

#### 1. Hero Section
- Gradient background with company colors
- Animated rocket shopping cart (400px desktop, responsive scaling)
- Dynamic floating animation with rotation and scaling effects
- Dual CTA buttons: "Learn More" + "Contact"
- Decorative background elements with code snippets

#### 2. About Section
- Company introduction and mission
- Large company logo display
- Professional content layout

#### 3. **Experts Section** ⭐ *NEW*
- **Team Expertise Showcase** - Highlighting years of e-commerce experience
- **Experience Statistics**: 15+ years, 200+ projects, 50+ satisfied clients
- **Technical Competencies**: Development, Frontend, Performance, Security
- **Credibility Building** - Demonstrates team's proven track record

#### 4. Solutions Section
- Three main offerings: Modular Framework, Custom Experience, High Productivity
- Interactive cards with hover animations
- Icon-based visual representation

#### 5. Technologies Section
- Split layout: Proven (PHP/Symfony) vs Modern (FrankenPHP/SolidJS)
- Color-coded technology cards
- Hover effects on technology showcases

#### 6. Benefits Section
- Four key advantages: Speed, Scalability, 24/7 Support, Security
- Circular icon containers with emoji representations
- Quantified benefits (60% faster development)

#### 7. Contact Section
- Prominent call-to-action
- Gradient background matching brand
- Direct email integration

#### 8. Footer
- Company information and copyright
- Gradient background styling

### 🎨 Advanced Styling
- **CSS Custom Properties** - Brand color variables
- **Enhanced Logo Sizing** - Responsive logo from 2rem to 4rem across devices
- **Mobile Menu System** - Alpine.js powered dropdown with click-outside closing
- **Floating Contact Button** - Always-visible contact access point
- **Advanced Hero Animation** - 4-point dynamic float with rotation and scaling

### ⚙️ Technical Implementation
- **Static HTML** - No backend dependencies, easy deployment
- **CDN Libraries** - Tailwind CSS, DaisyUI, Alpine.js via CDN
- **Custom CSS** - Extensive responsive styling in `assets/styles.css`
- **Modern JavaScript** - Alpine.js for interactivity and state management
- **Mobile-First Design** - Progressive enhancement approach

## 📁 Project Structure

```
red-fox-digital/
├── index.html              # Main website file
├── README.md               # Project documentation
├── assets/
│   ├── styles.css          # Custom CSS styles
│   ├── red_fox_logo.svg   # Company logo
│   └── wozek.webp         # Hero section rocket cart image
└── server logs            # Local development server logs
```

## 🛠️ Local Development

### Quick Start
1. **Clone or download** the project files
2. **Navigate** to the project directory
3. **Start local server**:
   ```bash
   python -m http.server 8000
   ```
4. **Open browser** to `http://localhost:8000`

### Requirements
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Python 3.x (for local server)
- No additional dependencies required

### Development Workflow
- Edit `index.html` for content changes
- Modify `assets/styles.css` for styling updates
- All changes visible with browser refresh
- No build process required

## 🎯 Key Improvements Implemented

### Logo & Branding
- ✅ Increased logo size to 4rem (64px) on desktop
- ✅ Responsive scaling: 3.5rem tablet, 3rem mobile, 2.5rem small mobile
- ✅ Proper vertical centering with flexbox
- ✅ Hover scaling effects for interactivity

### Hero Section Enhancements
- ✅ Added dynamic rocket shopping cart graphic
- ✅ Advanced 5-second floating animation with rotation and scaling
- ✅ Enhanced background graphics with code snippets
- ✅ Dual CTA button strategy for better conversion

### Mobile Experience
- ✅ Fixed mobile menu functionality with Alpine.js
- ✅ Proper click-outside-to-close behavior
- ✅ Touch-optimized navigation
- ✅ Responsive text and button sizing

### Expert Credibility Section
- ✅ New dedicated section showcasing team experience
- ✅ Statistical credibility markers (years, projects, clients)
- ✅ Technical competency visualization
- ✅ Professional presentation of expertise

### Animation & Performance
- ✅ Enhanced hero cart animation with 4-point movement cycle
- ✅ Smooth hover transitions on all interactive elements
- ✅ Optimized CSS with hardware acceleration
- ✅ Efficient Alpine.js state management

## 🌐 Browser Support

- ✅ **Chrome/Chromium** - Full support
- ✅ **Firefox** - Full support  
- ✅ **Safari** - Full support
- ✅ **Edge** - Full support
- ✅ **Mobile Browsers** - Optimized experience

## 📧 Contact Integration

The website includes multiple contact touchpoints:
- **Navbar Contact Button** (desktop)
- **Mobile Menu Contact Option**
- **Hero Section CTA Button**
- **Floating Contact Button** (always visible)
- **Dedicated Contact Section**

All contact points link to: `contact@redfox.digital`

## 🔄 Recent Updates

### Latest Version Features:
1. **Enhanced Hero Animation** - Dynamic rocket cart with advanced 4-point floating
2. **Expert Credibility Section** - New section highlighting team experience
3. **Improved Mobile Navigation** - Fixed Alpine.js dropdown functionality  
4. **Responsive Logo Sizing** - Optimized for all device sizes
5. **Professional Presentation** - Enhanced credibility and trust indicators

## 📝 Customization Guide

### Adding New Sections
1. Add HTML structure in `index.html`
2. Add translations to both `pl` and `en` objects
3. Add navigation links if needed
4. Style with CSS in `assets/styles.css`

### Updating Content
- **Text Changes**: Update translations objects in `index.html`
- **Styling**: Modify `assets/styles.css`
- **Images**: Replace files in `assets/` directory

### Color Scheme
Primary colors defined in CSS custom properties:
- `--primary-red: #c9261e` (from company logo)
- `--secondary-orange: #ea580c`
- `--dark-gray: #1f2937`
- `--light-gray: #f9fafb`

## 📊 Performance Notes

- **Minimal Dependencies** - Only essential CDN libraries
- **Optimized Images** - WebP format for hero graphics
- **Efficient CSS** - Custom properties and minimal specificity
- **Fast Loading** - No heavy frameworks or libraries
- **SEO Friendly** - Semantic HTML structure and meta tags

## 🎉 Deployment Ready

The website is production-ready and can be deployed to any static hosting service:
- **Netlify** - Drag and drop deployment
- **Vercel** - Git integration
- **GitHub Pages** - Direct repository hosting
- **Traditional Web Hosting** - Upload files via FTP

---

**Red Fox Digital** - Next-Generation E-commerce Platforms
*Copyright © 2024 - All rights reserved* 