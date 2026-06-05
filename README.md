# Academy Heights School Website

A modern, responsive school website built with HTML, CSS, and JavaScript.

## 📋 Overview

This is a comprehensive school website for "Academy Heights," featuring all essential sections for a professional educational institution.

## ✨ Features

### Sections Included:
1. **Navigation Bar** - Sticky header with smooth scrolling
2. **Hero Section** - Eye-catching welcome banner
3. **About Section** - Mission, vision, and values
4. **Programs Section** - Elementary, Middle, High School, STEM, Arts, and Athletics
5. **Faculty Section** - Meet the educators and leadership team
6. **Admissions Section** - 4-step application process
7. **Contact Section** - Contact information and inquiry form
8. **Footer** - Social media links and copyright

### Technical Features:
- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Smooth scroll animations
- ✅ Intersection Observer for scroll-triggered effects
- ✅ Modern gradient backgrounds
- ✅ Hover animations and transitions
- ✅ Form validation
- ✅ Accessibility-friendly HTML structure
- ✅ Clean, maintainable CSS with CSS variables
- ✅ Interactive JavaScript functionality

## 🎨 Design Elements

### Color Scheme:
- **Primary Color**: #1e3c72 (Dark Blue)
- **Secondary Color**: #2a5298 (Medium Blue)
- **Accent Color**: #f39c12 (Gold/Orange)
- **Light Background**: #f8f9fa (Light Gray)

### Typography:
- Font Family: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- Responsive font sizes for all devices

## 📁 File Structure

```
.
├── index.html       # Main HTML file
├── styles.css       # Complete styling
├── script.js        # JavaScript functionality
└── README.md        # This file
```

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SonalAllen/SonalAllen.main.git
   cd SonalAllen.main
   ```

2. **Switch to the school-website branch:**
   ```bash
   git checkout school-website
   ```

3. **Open in browser:**
   - Open `index.html` in your preferred web browser
   - Or use a local server: `python -m http.server 8000`

## 💻 Browser Compatibility

- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Customization Guide

### Change School Name:
- Update "Academy Heights" in `index.html` (Line 7, 24, and throughout)
- Update in `styles.css` if needed

### Update Colors:
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #1e3c72;
    --secondary-color: #2a5298;
    --accent-color: #f39c12;
    /* ... */
}
```

### Modify Content:
- Edit school information in the "About" section
- Update faculty members in the "Faculty" section
- Customize programs listed
- Update contact information

### Add Images:
Replace emoji icons with actual images:
```html
<!-- Instead of emoji -->
<div class="program-icon">📚</div>

<!-- Use image -->
<img src="path/to/image.png" alt="description" class="program-icon">
```

## 📝 Form Handling

The contact form currently:
- Validates input fields
- Validates email format
- Shows success message
- Resets form after submission

**Note:** For production, implement backend email handling or use a service like Formspree, Netlify Forms, or EmailJS.

## 🔧 JavaScript Functionality

- **Smooth Scrolling**: Click navigation links for smooth page scroll
- **Form Validation**: Validates all contact form fields
- **Scroll Animations**: Cards animate in as you scroll
- **Active Navigation**: Highlights current section in navbar
- **Apply Now Buttons**: Direct users to admissions section

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## ⚡ Performance Optimizations

- Lightweight CSS with CSS variables
- Smooth animations with hardware acceleration
- Efficient JavaScript with no external dependencies
- Optimized media queries

## 🚀 Deployment Options

### GitHub Pages:
1. Push to main branch
2. Go to Settings > Pages
3. Select main branch as source

### Netlify:
1. Drag and drop folder or connect repository
2. Deploy automatically

### Vercel:
1. Connect GitHub repository
2. Auto-deploys on push

## 📧 Contact Information

Update the contact section with your actual details:
- Address
- Phone Number
- Email
- Office Hours

## 📄 License

This project is open source and available for educational use.

## 🤝 Contributing

Feel free to fork, modify, and improve this school website template!

## 📚 Future Enhancements

- [ ] Add blog/news section
- [ ] Integrate calendar for events
- [ ] Add student portal
- [ ] Implement online admissions
- [ ] Add photo gallery
- [ ] Implement real-time notifications
- [ ] Add multilingual support
- [ ] SEO optimization

---

**Created with ❤️ for educational institutions**